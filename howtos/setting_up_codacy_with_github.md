# How to setup Codacy for an Eiffel project

This walkthrough is based on Emelie Pettersons walkthrough on [Eiffel Intelligence issue #320](https://github.com/eiffel-community/eiffel-intelligence/pull/320)

You login with you GitHub account. When you login Codacy will request for some permissions to your
 GitHub account. This is to able to fetch all you public repositories into Codacy. For more
 information take a look at their help page [Which permissions does Codacy need from my account?](https://support.codacy.com/hc/en-us/articles/115003405529-Which-permissions-does-Codacy-need-from-my-account-)

After you have logged in you will need to import project to work with. If this is the first time
 it is recommended to start by importing your own fork to try out. You will however need to import
 the real project later on.

When you have imported a project, Codacy will put an notification on each pull request in the
 status part. If you want to have more interaction checkout the *Integrations* tab under the
 Setting page. In GitHub you can find this integration in *Webhooks* tab under the Settings page.

At this point you have integrated Codacy into GitHub so it is performing style checks for your
 project on each Pull Request as this it the default behavior for the Webhook.

For here on it is assumed we are working the project and not the fork

## Transfer the project

To enable other people to change settings you will have to transfer the project to an organization.
 The recommendation is to name the organization same as the maintainers team in GitHub. If there
 is no organization to fit you need you will need to [create one](https://support.codacy.com/hc/en-us/articles/360009209594-Creating-and-renaming-an-organization).
 When you have created the organization be sure to invite members from the GitHub maintainers
 team. The [transfer](https://support.codacy.com/hc/en-us/articles/207994835-How-do-I-transfer-delete-a-project-from-my-account-)
 option is found in the setting page for the project.

After you have transferred the project and want to make changes, you will first have to navigate to
 the organizations page and then to the project to access the settings page.

## Add coverage
In order to start showing coverage report for the project you will probably first time need to
 upload coverage manually. This step is not necessary but it will enable you to get the link to the
 coverage badge before Travis is run. To upload the coverage manually please see this guide

### Manually upload coverage reports

**Note:** This can be done in your own fork if you want to try it out but it will also be needed
 for the upstream repository if you want get the badge.

First you have to generate the coverage. Check that the POM file contains the needed plugin,
 something like this:

```
<plugin>
	<groupId>org.codehaus.mojo</groupId>
	<artifactId>cobertura-maven-plugin</artifactId>
	<version>2.7</version>
	<configuration>
		<formats>
			<format>html</format>
			<format>xml</format>
		</formats>
	</configuration>
</plugin>
```

When cobertura is in the POM you can trigger it with:

```
mvn cobertura:cobertura -B
```

You will now have the coverage in `target/site/cobertura`. To upload the report you can use the following lines but with your token set

```
export CODACY_PROJECT_TOKEN=%Project_Token%
curl -Ls -o codacy-coverage-reporter-assembly.jar https://github.com/codacy/codacy-coverage-reporter/releases/download/6.0.2/codacy-coverage-reporter-6.0.2-assembly.jar
java -jar codacy-coverage-reporter-assembly.jar report -l Java -r target/site/cobertura/coverage.xml
```

If you have tried out with your own fork be sure that you are using the correct API key.

### Setup automatic coverage report
In order to have coverage report done for each pull request you will need to setup a TravisCI link.
 First create a Project API token as shown in [this tutorial](https://support.codacy.com/hc/en-us/articles/207279819-Coverage).
 Insert the Project API token as a environment variable in Travis as show in [this guide](https://docs.travis-ci.com/user/environment-variables/#defining-variables-in-repository-settings).
 **Note** When you are inserting the API token it will be visible for all who have access to the
 Travis job.

In order to always create the coverage you will need to add the above commands in the docker file
 as described in [this guide](https://github.com/codacy/codacy-coverage-reporter#travis-ci). Don't
 forget to trigger the coverage generation in the Travis file.

Note that the coverage will only be run on the merge back to master due to security risks. You can
 read more about this under the [pull request and security restrictions](https://docs.travis-ci.com/user/pull-requests/#pull-requests-and-security-restrictions)
 page on TravisCI.

Finally in order to show the status of the project you will need to add two badges in the README
 file. The links to the badges can be found in the setting page.

