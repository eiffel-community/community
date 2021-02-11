# Technical Committee Meetings

[![HacmKD documents](https://hackmd.io/badge.svg)](https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2021-02-11 Meeting](#February-11-2021)
    * [2021-01-28 Meeting](#January-28-2021)
    * [2020-12-07 Meeting](#December-7-2020)
    * [2020-11-23 Meeting](#November-23-2020)
    * [2020-11-09 Meeting](#November-9-2020)
    * [2020-10-26 Meeting](#October-26-2020)
    * [2020-10-12 Meeting](#October-12-2020)
    * [2020-09-28 Meeting](#September-28-2020)
    * [2020-09-14 Meeting](#September-14-2020)

## Logistics

* **When:** 13:00 - 14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_MDljZGI1ZDEtOGRhYS00NzlmLTlkZTgtNTM4OGMwNmU3ZTVh%40thread.v2/0?context=%7b%22Tid%22%3a%22d2585e63-66b9-44b6-a76e-4f4b217d97fd%22%2c%22Oid%22%3a%22b5142d0f-6dad-4704-99f5-29b74621c34a%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ) in order to prevent notes getting out of sync.

### February 11, 2021

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, **not present**
* Fredrik Fristedt, Axis, present
* Kristofer Hallén, Ericsson, present
* Mattias Linnèr, Ericsson, present
* Christian Madsen, Grundfos, **not present**
* Raja Maragani, Ericsson/TCS, present
* Henning Roos, Ericsson, present
* Ola Söder, Axis, **not present**
* Daniel Ståhl, Ericsson, present
* David Westberg, Volvo, present
* Ewelina Wilkosz, Eficode, **not present**

**Community Attendees**
* Magnus Bäck, Axis Communications

#### Agenda and Notes
* Rollcall, All
* Agenda Bashing, All
* Action Item Review, All
* Status of Community Governance Documentation, All
    * Election Process: https://github.com/eiffel-community/community/pull/82 
    * [Fatih] Will amend the PR and update based on comments received. If you haven't reviewed yet please do so their comments could be taken into account when the work proceeds.
    * Some comments remain to be answered/finished and more reviews are needed.
* Open PRs, All
    * [github.com/eiffel-community/eiffel#254](https://github.com/eiffel-community/eiffel/pull/254): three maintainer approvals; merge?
        * Merged
    * [github.com/eiffel-community/eiffel#253](https://github.com/eiffel-community/eiffel/pull/253): release of Paris edition
        * Waiting for reviews
    * [github.com/eiffel-community/eiffel-community.github.io#18](https://github.com/eiffel-community/eiffel-community.github.io/pull/18): messed up github.io headers
        * Merged
* Copyright headers in project files. See http://www.apache.org/licenses/LICENSE-2.0 and https://github.com/eiffel-community/eiffel-repository-template/issues/14. Henning and Mattias.
    * Consensus on that the template should not say Ericsson (and not a specific year either)
    * Should license statement be added to all files, including README files etc? Ericsson people should check with Gunnar Nilsson on how to handle this from Ericsson perspective. Daniel has added a comment in the ticket.

#### Action Items
  * ~~Mattias to send a PR to Sepia to add ER Swagger specification[github.com/eiffel-community/eiffel-event-repository#11](https://github.com/eiffel-community/eiffel-event-repository/pull/11)~~
* Magnus to call meeting to discuss ER with Emil, Mattias, Kristofer, Fredrik, Tobias
* ~~Magnus to update https://github.com/eiffel-community/eiffel/pull/253 with name Paris~~
* Magnus to file a PR to Sepia for best practices for routing key. 
     * [Issue created](https://github.com/eiffel-community/eiffel-sepia/issues/8), but no PR yet.
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* ~~Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member. Closing as no work was needed~~
* Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
* ~~Update the project lifecycle document to add mail requirement to maillist for increased visibility, Fatih [PR79](https://github.com/eiffel-community/community/pull/79)
    [Fatih] **This AP can be closed.** PR merged.~~ 
* Document the term and the process to appoint security officers as part of TC creation, Fatih
    * [Fatih] Still pending unfortunately. Will come back to this as soon as possible.
* ~~Send PRs to repos to apply badges to the repos, Fatih [Fatih] **This AP can be closed.** I believe most of the PRs applying badges have been merged.For the ones that are still open or the repos that miss the badge can be fixed when we notice them.~~
    * eiffel-community/eiffel - being graduated so sandbox badge won't be applied
    * The repos below either have non-standard readmes or no readmes at all. Readmes will be created using readme from the template repository which contains the sandbox badge as well.
        * eiffel-community/eiffel-persistence-technology-evaluation
        * eiffel-community/eiffelactory
        * eiffel-community/ml-jmespath-generator
        * eiffel-community/eiffel-jira-plugin
        * eiffel-community/simple-event-sender
        * eiffel-community/eiffel-easy2use
        * eiffel-community/eiffel-store
        * eiffel-community/eiffel-playground
* Mattias: Look into if all files need a copyright/license statement or not, inline with this comment: https://github.com/eiffel-community/eiffel-repository-template/issues/14#issuecomment-777427403

### January 28, 2021

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, present
* Fredrik Fristedt, Axis, present
* Kristofer Hallén, Ericsson, present
* Mattias Linnèr, Ericsson, present
* Christian Madsen, Grundfos, **not present**
* Raja Maragani, Ericsson/TCS, **not present**
* Henning Roos, Ericsson, present
* Ola Söder, Axis, **not present**
* Daniel Ståhl, Ericsson, present
* David Westberg, Volvo, **not present**
* Ewelina Wilkosz, Eficode, **not present**

**Community Attendees**
* Magnus Bäck, Axis Communications

#### Agenda and Notes
* Rollcall, All
    * Quorum reached
* Agenda Bashing, All
    * Agenda approved
* Action Item Review, All
* Status of Community Governance Documentation, All
    * EB: Concern: [Meeting poll](https://doodle.com/poll/hrcvgz8uiggwneda?utm_source=poll&utm_medium=link) answered by 5 BTC members only, and community PRs take long to get reviewed. What could we do to increase the level of commitment? Emil
    * FD: We need to continuously monitor the health of the community and act if things need improvement.
* [Eiffel Protocol Graduation](https://github.com/eiffel-community/community/pull/78) is still not approved? Emil
    * Agree: Eiffel Protocol is approved to be moved to graduated stage.
* Info/discussion: A [new Eiffel protocol release - Agen-2](https://github.com/eiffel-community/eiffel/pull/253) is about to be released, Emil
    * EB: The proposal is to release Agen as a patch release since there are few/small changes.
    * DS: We had version policy.
    * EB: We shouldn't take up a new revision for bugfix releases but there isn't a clear process around this.
    * EB: Things are released at will. Should we have some structure with regards to releases in general - e.g., twice a year?
    * DS: Suggestion is to just stick with the names. If it is about the new event versions, we step.
    * DS: The current process around versioning, naming, editions is documented on https://github.com/eiffel-community/eiffel/blob/master/eiffel-syntax-and-usage/versioning.md
    * EB: We could take the next name.
* Discussion: How can we establish a standard for RabbitMQ topics for Eiffel exchanges to improve interoperability between producers and consumers ([Slack thread](https://eiffel-workspace.slack.com/archives/CQD817AHY/p1611324003004100)) Magnus
    * MB: Right now there is no standard around topics, causing difficulties for filtering.
    * MB: RemREM has something for this but it is not very well documented which requires you to dive into code deeper.
    * MB: It would be beneficial to have some kind of standard around this and documented.
    * MB: This is not part of the Eiffel Protocol so where/how should we deal with this?
    * DS: This could be in "infrastructure configuration reporitory", proposing canonical configuration, essentially saying this is adviced way of configuring it.
    * HR: Sepia was created for this purpose?
    * FF: There was a discussion around having best practices documented/good to know.
    * MB: That kind of repository could contain information about other practices as well such as different repositories.
    * EB: Examples in protocol could be renamed to best practices perhaps. (e.g., what is a good way to link series of events)
    * MB: Concurs - examples could be renamed to recommendations. Examples talk about how the events look like but not much about how to use them for.
    * EB: [All Sepia maintainers](https://github.com/orgs/eiffel-community/teams/eiffel-sepia-maintainers/members) are from a single company and it would be good to broaden maintainers list with more people from different companies.
* Discussion: The question of a standard API for event repositories was brought up at a previous TC meeting and an action was given to Emil and Tobias, but this was dropped. Let's try again? ([Slack thread](https://eiffel-workspace.slack.com/archives/CQD817AHY/p1603952501067200)) Magnus
    * MB: The event repository implementation is not public and everyone has their own event repository.
    * MB: How should we have some progress on this topic to start discussions?
* Events in CI/CD Workstream in CDF SIG Interoperability, Emil
    * EB: It was proposed to make Events in CI/CD a top level SIG. A PR is currently being worked on to propose the SIG.
    * EB: Draft charter for the SIG was brought up to CDF Technical Oversight Committee and the feedback was very good.
    * ML: Cloudevents is something the group is looking into as well.
* Open PRs, All
    * Agree: This PR can be merged: https://github.com/eiffel-community/community/pull/80

#### Action Items
* Mattias to send a PR to Sepia to add ER Swagger specification
* Magnus to call meeting to discuss ER with Emil, Mattias, Kristofer, Fredrik, Tobias
* Magnus to update https://github.com/eiffel-community/eiffel/pull/253 with name Paris
* Magnus to file a PR to Sepia for best practices
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices
* ~~Kristofer to drive planning for Eiffel Summit 2021~~
* ~~Send mail to Eiffel maillist, pointing the inclusive language initiative, Fredrik~~
* Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member
* Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
* ~~Conclude the badging discussion and then start applying badges, https://github.com/eiffel-community/eiffel-repository-template/issues/9~~
* Update the project lifecycle document to add mail requirement to maillist for increased visibility, Fatih [PR79](https://github.com/eiffel-community/community/pull/79)
* Document the term and the process to appoint security officers as part of TC creation, Fatih
* Send PRs to repos to apply badges to the repos, Fatih
    * eiffel-community/eiffel - being graduated so sandbox badge won't be applied
    * The repos below either have non-standard readmes or no readmes at all. Readmes will be created using readme from the template repository which contains the sandbox badge as well.
        * eiffel-community/eiffel-persistence-technology-evaluation
        * eiffel-community/eiffelactory
        * eiffel-community/ml-jmespath-generator
        * eiffel-community/eiffel-jira-plugin
        * eiffel-community/simple-event-sender
        * eiffel-community/eiffel-easy2use
        * eiffel-community/eiffel-store
        * eiffel-community/eiffel-playground

### December 7, 2020

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, present
* Fredrik Fristedt, present
* Kristofer Hallén, Ericsson, present
* Mattias Linnèr, Ericsson, present
* Christian Madsen, Grundfos, **not present**
* Raja Maragani, Ericsson/TCS, present
* Henning Roos, Ericsson, **not present**
* Ola Söder, Axis, present
* Daniel Ståhl, present
* David Westberg, present
* Ewelina Wilkosz, **not present**

#### Agenda and Notes
* Rollcall, All
    * Quorum reached
* Agenda Bashing, All
    * Agenda approved
* Action Item Review, All
* Status of Community Governance Documentation, All
    * Close to be accepted - missing 1 approval **WIP:** Security/Vulnerability reporting and response processes *(PRs available)* [PR72](https://github.com/eiffel-community/community/pull/72) and [PR15](https://github.com/eiffel-community/eiffel-community.github.io/pull/15)
    * **WIP:** Community Vision, Mission, Goals *(PR available)* [PR80](https://github.com/eiffel-community/community/pull/80) and [PR17](https://github.com/eiffel-community/eiffel-community.github.io/pull/17)
    * **WIP:** Election procedure *(PR available)* [PR82](https://github.com/eiffel-community/community/pull/82)
* Date for Next Meeting?
    * Agreed: January 18th is the next meeting date
* Formation of TC - part of TC charter, All
    * No of members in TC: BTC had 5 meetings with average attendance of 8 from TC members 
    * Company cap: This is a common practice applied by the communities to ensure diversity. We could start with something and then we expect to lower it over time. (start with 3 for example and reduce to 2 over time)
    * Company Cap: Representing a certain company regardless of affiliation?
    * Question: What happens a TC member changes employment? Will the person need to step down from TC?
    * Question: Having company cap my prevent representation from a company with fewer voters.
    * Question: Why do we need company cap (diversity, etc) needs to be documented?
    * Agreed: Update the governance document and incldue 8 as no of TC members and 3 as the company/affiliation cap.
* How to handle approvals to community processes?, All
    * Currently the changes could come in in the form of issue and/or PR which is time consuming.
    * Should we use PRs solely to remove an extra step?
    * For the things that do not result in PRs, they could be included in TC meeting and decisions could be taken quickly? (can consider silence as +1)
    * Proposal (can't take decisions this meeting): Use issues to describe the problem. Issues do not have to be approved. Create PRs to describe solutions.
    * It is better to look at actual solution rather than the issue.
    * Agreed: Issues will continue to be used but no approval should be expected for them. The PR implementing what is documented in the issue is what gets reviewed/approved/declined.
    * Question: What to do with the issues where the corresponding PRs are not accepted? Who marks the issues as invalid or close with no action?
* Eiffel summit next year, Kristofer
    * The last event happened in May 2020.
    * Should we plan something for new year?
    * Software Center, CDF, and other communities can be invited to the event.
* Eiffel Protocol Graduation needs approval: https://github.com/eiffel-community/community/pull/78, https://github.com/eiffel-community/eiffel/pull/247
* Meeting with Scania on Eiffel
    * Reach out to Kristofer and Emil if you want to be part of the discussion
* Eiffel Lucia/Fika
    * 14th of December. The invitation is on Slack.
* \<addme\>

#### Action Items
* Kristofer to drive planning for Eiffel Summit 2021
* Send mail to Eiffel maillist, pointing the inclusive language initiative, Fredrik
* Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member
* Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
* Conclude the badging discussion and then start applying badges, https://github.com/eiffel-community/eiffel-repository-template/issues/9
* Update the project lifecycle document to add mail requirement to maillist for increased visibility, Fatih [PR79](https://github.com/eiffel-community/community/pull/79)
* Document the term and the process to appoint security officers as part of TC creation, Fatih
* Send PRs to repos to apply badges to the repos, Fatih
* ~~Add link to eiffel-community.github.io for security page, Fredrik~~
* ~~Daniel to document Community Vision, Mission, Goals and include it on eiffel-community.github.io [PR80](https://github.com/eiffel-community/community/pull/80) and [PR17](https://github.com/eiffel-community/eiffel-community.github.io/pull/17)~~
* ~~Fatih to document election procedure as part of governance [PR82](https://github.com/eiffel-community/community/pull/82)~~
~~* Follow up November 23 meeting items since decisions could not be taken. Fatih
* ~~Eiffel summit next year? Kristofer~~

### November 23, 2020

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, present
* Fredrik Fristedt, **not present**
* Kristofer Hallén, Ericsson, present
* Mattias Linnèr, Ericsson, present
* Christian Madsen, Grundfos, **not present**
* Raja Maragani, Ericsson/TCS, **not present**
* Henning Roos, Ericsson, present
* Ola Söder, Axis, **not present**
* Daniel Ståhl, present
* David Westberg, **not present**
* Ewelina Wilkosz, **not present**

#### Agenda and Notes
* Rollcall, All
    * Quorum **NOT** reached
* Agenda Bashing, All
* Action Item Review, All
* Status of Community Governance Documentation, All
    * **Done:** [Governance](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md)
    * **Done:** [License](https://github.com/eiffel-community/community/blob/master/LICENSE)
    * **Done:** [Project Maintainers](https://github.com/eiffel-community/community/blob/master/CONTACT.md)
    * **Done:** [Project Lifecycle](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md)
    * **Done:** [Project List](https://github.com/eiffel-community/community/blob/master/PROJECTS.md)
    * **Done:** [Code of Conduct](https://github.com/eiffel-community/.github/blob/master/CODE_OF_CONDUCT.md)
    * **Done:** [Contribution Guidelines](https://github.com/eiffel-community/.github/blob/master/CONTRIBUTING.md)
    * **Missing:** [Technical Committee Charter](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee) *(pieces of this is in governance document but few things such as election process require to be decided and documented)*
    * **Missing:** Security/Vulnerability reporting and response processes *(not available yet)*
    * **Missing:** Community Vision, Mission, Goals *(not available yet)*
    * **Missing:** Election procedure - part of governance
* Formation of TC - part of TC charter, All
    * No of members in TC: BTC had 5 meetings with average attendance of 8 from TC members 
    * Company cap: This is a common practice applied by the communities to ensure diversity. We could start with something and then we expect to lower it over time. (start with 3 for example and reduce to 2 over time)
* How to handle approvals to community processes?, All
    * Currently the changes could come in in the form of issue and/or PR which is time consuming.
    * Should we use PRs solely to remove an extra step?
    * For the things that do not result in PRs, they could be included in TC meeting and decisions could be taken quickly? (can consider silence as +1)
    * Proposal (can't take decisions this meeting): Use issues to describe the problem. Issues do not have to be approved. Create PRs to describe solutions.  

#### Action Items
* Send mail to Eiffel maillist, pointing the inclusive language initiative, Fredrik
* Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member
* Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
* Conclude the badging discussion and then start applying badges, https://github.com/eiffel-community/eiffel-repository-template/issues/9
* ~~Create a PR to graduate Eiffel Protocol, Emil [Pull request #78](https://github.com/eiffel-community/community/pull/78)~~
* Update the project lifecycle document to add mail requirement to maillist for increased visibility, Fatih [Pull request #79](https://github.com/eiffel-community/community/pull/79)
* ~~Update project lifecycle with instructions of adding badges, Mattias [Pull request #76](https://github.com/eiffel-community/community/pull/76)~~
* ~~Update template repository with default sandbox logo/icon, Henning~~
* Document the term and the process to appoint security officers as part of TC creation, Fatih
* ~~Create a google group for Eiffel Security, Kristofer [Issue #60](https://github.com/eiffel-community/community/issues/60)~~
* ~~Axis and Ericsson to drive the ER topic, Tobias & Emil~~
* Send PRs to repos to apply badges to the repos, Fatih
* Add link to eiffel-community.github.io for security page, Fredrik
* Daniel to document Community Vision, Mission, Goals and include it on eiffel-community.github.io
* Fatih to document election procedure as part of governance
* Follow up November 23 meeting items since decisions could not be taken. Fatih
* Eiffel summit next year? Kristofer

### November 9, 2020

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, present
* Fredrik Fristedt, Axis, present
* Kristofer Hallén, Ericsson, present
* Mattias Linnèr, Ericsson, present
* Christian Madsen, Grundfos, **not present**
* Raja Maragani, Ericsson/TCS, **not present**
* Henning Roos, Ericsson, present
* Ola Söder, Axis, **not present**
* Daniel Ståhl, present
* David Westberg, present
* Ewelina Wilkosz, **not present**

#### Agenda and Notes
* Rollcall, All
    * Quorum reached
* Agenda Bashing, All
    * Agenda approved
* Action Item Review, All
* [Eiffel Community Security & Vulnerability Process](https://github.com/eiffel-community/community/issues/61), Fredrik & Kristofer
    * PR is open for review: https://github.com/eiffel-community/community/pull/72
    * Security officers/contacts - Kristofer, Fredrik
* Event Repository, Tobias Persson/All
    * Which event repository API should be the standard interface for all event repositories?
    * Should we work together to come up with something new?
    * Should this be documented somewhere in the community?
    * The topic could be discussed outside of TC meeting to look for options
    * People from broader community could take part in this discussion
    * It is a good opportunity to work on this collaboratively to put the pieces in place as a community
    * This would also allow bringing experiences from others
    * Event data aggragation could be seen as an item under this discussion
    * Lack of ER caused some difficulties so this would help with it
* [Project Lifecycle Stages](https://github.com/eiffel-community/eiffel-repository-template/issues/9), All
    * Starting to apply badges to the projects to increase visibility?
    * Everyone is urged to review https://github.com/eiffel-community/eiffel-repository-template/issues/9
    * PR would be good. 
* Guidelines for publishing community videos/recordings, All
    * Do we need to have guidelines for community for publishing videos/recordings?
    * The guidelines will be documented as part of the creation of the next community recording 

#### Action Items
* Send mail to Eiffel maillist, pointing the inclusive language initiative, Fredrik
* ~~ETOS project to reach out to Daniel Stahl whenever they think they want to have a video~~
* ~~Fatih to add topic on having guidance on community videos/recordings to next meeting~~
* Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member
* ~~Pass Kubernetes deployment details on community repo, Tobias~~
* Fatih to get Tobias in touch with Nordix for Kubernetes cluster installation
* Conclude the badging discussion and then start applying badges, https://github.com/eiffel-community/eiffel-repository-template/issues/9
* ~~Prepare graduation proposal for Eiffel Protocol project, Emil [Issue 77](https://github.com/eiffel-community/community/issues/77)~~
* Create a PR to graduate Eiffel Protocol, Emil
* Update the project lifecycle document to add mail requirement to maillist for increased visibility, Fatih
* Update project lifecycle with instructions of adding badges, Mattias [Pull request #76](https://github.com/eiffel-community/community/pull/76)
* Update template repository with default sandbox logo/icon, Henning
* Document the term and the process to appoint security officers as part of TC creation, Fatih
* Create a google group for Eiffel Security, Kristofer
* Axis and Ericsson to drive the ER topic, Tobias & Emil
* Send PRs to repos to apply badges to the repos, Fatih

### October 26, 2020

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, present
* Fredrik Fristedt, Axis, **not present**
* Kristofer Hallén, Ericsson, **not present**
* Mattias Linnèr, Ericsson, present
* Christian Madsen, Grundfos, **not present**
* Raja Maragani, Ericsson/TCS, **not present**
* Henning Roos, Ericsson, present
* Ola Söder, Axis, **not present**
* Daniel Ståhl, present
* David Westberg, present
* Ewelina Wilkosz, **not present**

**Community Attendees**

#### Agenda and Notes
* Rollcall, All
    * Quorum **NOT** reached
* Agenda Bashing, All
    * Agenda is approved
* Action Item Review, All
* [Eiffel Community Security & Vulnerability Process](https://github.com/eiffel-community/community/issues/61), Fredrik & Kristofer
    * PR is open for review: https://github.com/eiffel-community/community/pull/72
    * ML: Proposed to create security.html upon approval of the PR.
    * HR: A placeholder could be created related to this PR so the link is not broken.
* [Eiffel Community Infrastructure](https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ?view), Mattias & Fatih
    * Progress summary
    * Do we need project dependency handling?
    * Links to jobs: https://jenkins.nordix.org/view/Eiffel/
    * The documentation about this work is kept on: https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ?view
* [Project Lifecycle Stages](https://github.com/eiffel-community/eiffel-repository-template/issues/9), All
    * Starting to apply badges to the projects to increase visibility?
    * Everyone is urged to review https://github.com/eiffel-community/eiffel-repository-template/issues/9
* How to work with items and approval process/way of working
    * This needs to be settled over time based on pacticing the processes for few months

#### Action Items
* Send mail to Eiffel maillist, pointing the inclusive language initiative, Fredrik
* ~~Kristofer and Fredrik to look at security vulnerability process, Fredrik and Kristofer~~
* ~~Daniel Stahl to help doodling things/videos for community videos, Daniel Stahl~~
* ETOS project to reach out to Daniel whenever they think they want to have a video
    * EB: Should we have some recommendations of ways to creating videos to set the way forward?
    * DS: I'm happy to help.
* Fatih to add topic on having guidance on community videos/recordings to next meeting
* Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member
* Pass Kubernetes deployment details on community repo, Tobias
* Conclude the badging discussion and then start applying badges, https://github.com/eiffel-community/eiffel-repository-template/issues/9
* Prepare graduation proposal for Eiffel Protocol project, Emil
* Update project lifecycle with instructions of adding badges, Mattias

### October 12, 2020

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, present
* Fredrik Fristedt, Axis, present
* Kristofer Hallén, Ericsson, present
* Mattias Linnèr, Ericsson, **not present**
* Christian Madsen, Grundfos, **not present**
* Raja Maragani, Ericsson/TCS, **not present**
* Henning Roos, Ericsson, present
* Ola Söder, Axis, present
* Daniel Ståhl, **not present**
* David Westberg, present
* Ewelina Wilkosz, **not present**

**Community Attendees**
* Tobias Persson, Axis Communications

#### Agenda and Notes
  - Rollcall, All
      - Quorum reached
  - Agenda Bashing, All
      - Agenda approved
  - Action Item Review, All
  - Reflections from [cdCon](https://events.linuxfoundation.org/cdcon/), All
      - FF: It was interesting to hear what people were discussing about such as having JSON schema to help with interoperability issues.
      - FF: They kind of described Eiffel without knowing about it.
      - EB: Attended the both days. It was intersting and there were a lot of talks about events everywhere. People may have different opinions about events.
      - EB: There was a presentation about Keptn from Dynatrace - Event driven CD. There were interesting talks.
      - EB: SIG Interoperability held BoF session and there were new people in the session. They may join to SIG.
      - KH: Were there more people you haven't seen before?
      - EB: People talk about interoperability but they are not aware of existence of the SIG.
      - EB: Tekton presentation was given by Andreas Frittoli and he looks forward to standardizing sending events for others to see their actions.
      - EB: Events in CI/CD meeting this evening 18:30.
      - EB: 1300 registrants and 800 accessed to the conference portal.
  - [Eiffel Community Security & Vulnerability Process](https://github.com/eiffel-community/community/issues/61), Fredrik & Kristofer
      - Working on the initial document.
      - Other communities don't seem to describe what happens once the issue is filed. (internal process)
      - Few steps need to be documented in order to explain the process so everyone knows how it works.
      - How projects themselves could publish identified/fixed security issues. (shortcut for projects)
  - [Inclusive Language Initiative and Impacts on Eiffel Community](https://github.com/eiffel-community/community/issues/68), Fatih & All
      - Discussion on whether community feels the need to work on adopting more inclusive language
      - Heads up on potential impacts introduced by other communities and organisations on Eiffel Community
      - If we start changing things and adapt inclusive language, we need to document this clearly in governance and project guidelines.
  - [Eiffel Community Infrastructure](https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ?view), Mattias & Fatih
      - Proxy for Docker Hub is created and podman is verified to use the proxy. Documentation is available [here](https://wiki.nordix.org/display/DEV/Docker+Hub+Proxy).
      - Builds for initial list of projects are created on Nordix: https://jenkins.nordix.org/view/Eiffel/
      - Projects are contacted to review and provide feedback
          - [Issue created for eiffel-gerrit-herald](https://github.com/eiffel-community/eiffel-gerrit-herald/issues/12)
          - [Issue created for eiffel-intelligence](https://github.com/eiffel-community/eiffel-intelligence/issues/478)
          - [Issue created for eiffel-intelligence-frontend](https://github.com/eiffel-community/eiffel-intelligence-frontend/issues/292)
          - [Issue created for eiffel-remrem-generate](https://github.com/eiffel-community/eiffel-remrem-generate/issues/178)
          - [Issue created for eiffel-remrem-publish](https://github.com/eiffel-community/eiffel-remrem-publish/issues/206)
  - Eiffel Community Organization Contacts, Henning
      - Who has right to add/invite people to Eiffel Organization on GitHub?
      - Any volunteers to help with this?
      - Issue https://github.com/eiffel-community/community/issues/71 tries to address this
  - Project Lifecycle Stages - How do we mark our repositories? Do we have badges or should we use lables? [Documenation](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#project-lifecycle-stages) states it _is_ clearly marked allthough very few (None) are marked.
      - There is an existing discussion on this topic: https://github.com/eiffel-community/eiffel-repository-template/issues/9
  - CDF SIG Interoperability Whitepaper
      - Ericsson contributed a case study on Eiffel to the whitepaper
      - Link to the whitepaper: https://docs.google.com/document/d/1Bgr6EHhW4wUTphU8xyMg87qzSee43PEA_gGdMnPHq9Q/edit#

#### Action Items
  - Send mail to Eiffel maillist, pointing the inclusive language initiative, Fredrik
  - ~~Clarify which repos the BTC should have permission on and [document it](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-members). [PR](https://github.com/eiffel-community/community/issues/69) created.~~
  - ~~Document quorum requirements~~
      - Already documented in the [governance](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee):  *Quorum for Technical Committee meetings requires at least a majority of all voting members of the Technical Committee to be present.*
  - Kristofer and Fredrik to look at security vulnerability process
  - ~~Henning to create eiffel-playground repo and create maintainers group with Mattias and Fatih as initial members~~
  - Daniel Stahl to help doodling things/videos for community videos
  - ~~Fatih and Henning to add topic/issue on community infra/organization champions/contacts with a simple/short process.~~ [PR](https://github.com/eiffel-community/community/issues/71).
  - Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member
  - Pass Kubernetes deployment details on community repo, Tobias
  - Conclude the badging discussion and then start applying badges, https://github.com/eiffel-community/eiffel-repository-template/issues/9
  - Prepare graduation proposal for Eiffel Protocol project, Emil


### September 28, 2020

#### Participants

**TC Attendees**
* Emil Bäckmark, Ericsson, present
* Fatih Degirmenci, Ericsson Software Technology, present
* Fredrik Fristedt, Axis, present
* Kristofer Hallén, Ericsson, present
* Mattias Linnèr, Ericsson, present
* Christian Madsen, Grundfos, present
* Raja Maragani, Ericsson/TCS, present
* Henning Roos, Ericsson, present
* Ola Söder, Axis, **not present**
* Daniel Ståhl, **not present**
* David Westberg, present
* Ewelina Wilkosz, **not present**

**Community Attendees**
* Isac Holm
* Martin Lundberg
 
#### Agenda and Notes
  - Rollcall
      - Quorum reached
  - Agenda Bashing
      - Agenda is approved
  - Action Item Review
      - Action items reviewed
  - [Responsibilities of TC Members and Chair](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee)
      - This topic came up based on Daniel’s comment - who does what: https://github.com/eiffel-community/community/issues/57#issuecomment-693175796
      - We already appointed people - TC
      - Monitoring community repository, maillist for the questions, issues, and PRs and providing opinion
      - Taking part in and driving TC activities such as establishing processes and procedures - examples to this are documenting security and vulnerability process, working with infrastructure
      - Joining meetings
      - More details on TC responsibilities are documented in [governance](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee)
      - Chair monitors maillist/community repo, bumps threads, and pulls in people accordingly as well as what's documented in [governance](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-chair)
  - [Eiffel Community Security & Vulnerability Process](https://github.com/eiffel-community/community/issues/61)
      - Looking for volunteers
      - Kristofer Hallen and Fredrik Fristedt volunteer
  - [Eiffel Community Infrastructure](https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ?view)
      - Seeking approval for [creating eiffel-playground repo](https://github.com/eiffel-community/community/issues/62)
      - Repo creation is approved
  - New Project: [ETOS](https://github.com/eiffel-community/community/issues/57)
      - The project was proposed by Axis
      - Axis intends to use the open source version of the project once the project is fully migrated to GitHub
      - There may be bumps as a small issue has been identified but it should be working fairly well
      - The project is interesting for David and it is in their watchlist
      - If desired, a demo/discussion can be set up for the interested people/organizations
      - It may be good to have a short video published on Eiffel Youtube channel but it may be too much for a video
      - A condensed version of the demo is a possibility depending on the priorities
      - It may be valuable to have this type of recordings/demos for other/all Eiffel projects as well
      - The project is up & running
  - Github roles within maintainer groups and community membership
      - Particulary the [community-maintainer list](https://github.com/orgs/eiffel-community/teams/eiffel-community-maintainers/members) and [eiffel community members](https://github.com/orgs/eiffel-community/people)
      - Each member in a maintainer group can have one of two different roles, member and maintainer.
      - *Members* (as well as *maintainers*) of a maintainer group can work with issues/PRs (accept, label, merge etc) of the associated repositories.
      - *Maintainers* of a maintainer group can also add & delete members of their maintainer group and change their roles
      - Who should be *maintainers* for Eiffel Community organization [maintainer list](https://github.com/orgs/eiffel-community/teams/eiffel-community-maintainers/members?query=role%3Amaintainer)
      - TC chair can be natural member of the team as maintainer
      - TC can appoint/empower few community members as the people to help with administering the Eiffel Organization
      - A suggestion is to allow maintainers to take care of their own maintainer list
  - cdCon - Inaugural summit for CD Foundation
      - October 7-8
      - [Registration is open](https://events.linuxfoundation.org/cdcon/) and free of charge
      - [Ewelina has a talk!](https://sched.co/dqOc)
  - Process/ guidelines on how to contribute and how to join into the community is lacking
      - Information on how to join and contribute needs to be more visable
      - How to add new member to a repository as member?
      - There was very little information about how one can join to Eiffel Community
      - This needs to be documented
      - Other communities have instructions about how to join to community
      - The governance document can be updated to tell people how to join the community https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#contributors
 
#### Action Items
  - ~~Update eiffel-community/community repo with the list of BTC members, Henning Roos~~
  - ~~[Update governance document](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-members) and list members and chair of the BTC~~
  - Clarify which repos the BTC should have permission on and [document it](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-members)
      - Update the governance and replace the repos with the link to the repos with a label community - https://github.com/search?q=topic%3Acommunity+org%3Aeiffel-community+fork%3Atrue
  - ~~Make code of conduct and contributions guidelines more visible~~
      - https://github.com/eiffel-community/community#code-of-conduct-and-contributing
      - template repository is also updated according to this
      - TC advises projects to make these guidelines more visible
  - ~~All BTC members to join [Maillist/Google Group](https://groups.google.com/g/eiffel-community)~~ 
  - Document quorum requirements
  - Kristofer and Fredrik to look at security vulnerability process
  - Henning to create eiffel-playground repo and create maintainers group with Mattias and Fatih as initial members
  - Daniel Stahl to help doodling things/videos for community videos
  - Fatih and Henning to add topic/issue on community infra/organization champions/contacts with a simple/short process
  - Fredrik to propose an update to README.md in community repo and governance document about how one can join to the community as member


### September 14, 2020

#### Participants
  - Kristofer Hallén, Ericsson
  - Fatih Degirmenci, Ericsson Software Technology
  - Christian Ekberg, Ericsson
  - Daniel Ståhl, Ericsson
  - Edvin Agnas, Volvo
  - Fredrik Fristedt, Axis
  - Christian Madsen, Grundfos
  - Henning Roos, Ericsson
  - Maniette Daniel, Volvo
  - Martin Kitchen, Grundfos
  - Ola Söder, Axis
  - Mattias Linner, Ericsson
  - Emil Bäckmark, Ericsson
  - Raja Maragani, Ericsson/TCS
  - David Westberg, Volvo

#### Agenda and Notes
  - Rollcall and Introductions
      - Everyone introduced themselves.
  - Agenda Bashing
      - Agenda is approved.
  - Appoint a chairman for the meeting
      - Kristofer Hallén nominated Fatih Degirmenci as the chair for the meeting.
      - Fatih Degirmenci accepted the nomination.
      - The group agrees.
  - Appoint a secretary for the meeting
      - Emil Bäckmark is the secretary for the meeting.
  - Decide on the bootstrap committee responsibilities
      - Fatih clarified the Boostrap process and the BTC responsibilities based on https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#community-bootstrap-process
      - PRs on the community needs simple majority of acceptance from the BTC members.
      - Agreed and understood :)
  - Decide on the members of the bootstrap committee
      - It is expected from BTC members to be able to spend a couple of hours/month for participation in meetings and review of PRs
      - Decided:
          - Fatih Degirmenci, Ericsson Software Technology
          - Ola Söder, Axis
          - Fredrik Fristedt, Axis
          - Daniel Ståhl, Ericsson
          - Emil Bäckmark, Ericsson
          - Raja Maragani, Ericsson/TCS
          - Henning Roos, Ericsson
          - Ewelina Wilkosz, Eficode
          - Mattias Linnèr, Ericsson 
          - Kristofer Hallén, Ericsson
          - David Westberg, Volvo
          - Christian Madsen, Grundfos
      - The people in the BTC should be the same as the maintainers in the Eiffel Community repo, i.e. this list will be reflected on Github after the meeting (AP Henning).
  - Decide if the committee should have regular meetings and if so how frequently
      - Bi-weekly meetings will be held. 1 hour each during office hours CET. The chairman will send invitations to the meeting series in the Google group https://groups.google.com/g/eiffel-community
  - Decide on the chairman for the committee
      - Emil Bäckmark nominated Fatih Degirmenci as the chair for the Boostrap Committee.
      - Fatih Degirmenci accepted the nomination.
      - Decided: Fatih Degirmenci
  - Decide on a deadline for the bootstrap committee to run an election for technical committee
      - According to our doc it should be maximum 1 year: https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#community-bootstrap-process
      - Decided: Until Q1 2021
          - Review the TC preparations during Q4 2020
          - Election during Q1 2021
          - TC come alive end of Q1 2021
  - Status of community process documentation
      - **Done:** [Governance](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md)
      - **Done:** [License](https://github.com/eiffel-community/community/blob/master/LICENSE)
      - **Done:** [Project Maintainers](https://github.com/eiffel-community/community/blob/master/CONTACT.md)
      - **Done:** [Project Lifecycle](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md)
      - **Done:** [Project List](https://github.com/eiffel-community/community/blob/master/PROJECTS.md)
      - **Done but with an AP:** [Code of Conduct](https://github.com/eiffel-community/.github/blob/master/CODE_OF_CONDUCT.md) *(this needs to be moved to community repo)*
          - HR: It should probably not be moved as it is needed to fulfill the Github magic.
          - AP to BTC to sort this out
      - **Done but with an AP:** [Contribution Guidelines](https://github.com/eiffel-community/.github/blob/master/CONTRIBUTING.md) *(this needs to be moved to community repo)*
          - HR: It should probably not be moved as it is needed to fulfill the Github magic.
          - AP to BTC to sort this out
      - **Missing:** [Technical Committee Charter](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee) *(pieces of this is in governance document but few things such as election process require to be decided and documented)*
          - To be created/updated by BTC
      - **Missing:** Security/Vulnerability reporting and response processes *(not available yet)*
          - To be created/updated by BTC
      - **Missing:** Community Vision, Mission, Goals *(not available yet)*
          - To be created/updated by BTC
      - **Missing:** Election procedure - part of governance
  - Maillist/Google group: https://groups.google.com/g/eiffel-community?pli=1

#### Action Items
  - Update eiffel-community/community repo with the list of BTC members, Henning Roos
      - Github users https://github.com/t031276 (David Westberg) and https://github.com/chr-madsen (Christian Madsen) have been invited to become members of https://github.com/orgs/eiffel-community/teams/eiffel-community-maintainers/. They have also been informed via the Eiffel-Community google group.
      - Christian Madsen have accepted the invitation
      - We are still waiting on David Westberg to accept.
      - Please notify me at henning.roos@ericsson.com as soon as possible if t031276 is not the correct github user.
  - [Update governance document](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-members) and list members and chair of the BTC
  - Clarify which repos the BTC should have permission on and [document it](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-members)
  - Make code of conduct and contributions guidelines more visible
  - All BTC members to join [Maillist/Google Group](https://groups.google.com/g/eiffel-community)