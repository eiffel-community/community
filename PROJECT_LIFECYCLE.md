# Project Lifecycle

## Table of Contents

- [Overview](#overview)
- [Projects](#projects)
- [Project Lifecycle Process](#project-lifecycle-process)
- [Project Lifecycle Stages](#project-lifecycle-stages)
- [References](#references)

## Overview

Eiffel Community is home to various projects that enable the members of the community to use, contribute,
and collaborate on Eiffel.

This document describes how Eiffel Community defines the projects, how the projects can be created, maintained,
and archived. In addition to the project lifecyle process, stages which the projects can be admitted or transitioned
into as well as criteria and expectations for the stages are described.

## Projects

The activities of the Eiffel Community are organized into projects targeting different areas within the scope of
Eiffel Community including but not limited to development and maintenance of Eiffel Protocol, development of new
functionality that adheres to the protocol, integration of other technologies, testing, documentation, as well as
the support functions to create and maintain the infrastructure and the toolchain community uses.

List of projects that are currently part of Eiffel Community can be seen from [PROJECTS.md](./PROJECTS.md).

## Project Lifecycle Process

New projects must be formally proposed on GitHub on [Eiffel Community](https://github.com/eiffel-community/community)
repository by creating an issue. The proposals submitted should provide the following information to the best of
their ability.

- name of the project
- project description (what it does, why it is valuable, origin and history)
- project license
- names of initial maintainers
- infrastructure needs such as Git repositories

In addition to formally proposing the project on GitHub, community members proposing the new project are expected
to announce the project proposal on [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community) by
sending an email in order to increase the visibility. The email should contain the same information as the proposal
itself.

Regarding project naming conventions, the Eiffel Community enforces no name convention but meaningful descriptive
names are encouraged.

Projects that are already hosted within Eiffel Community but willing to move to a different stage are also
expected to follow same process as project creation by formally submitting their request on Eiffel
Community repository by creating an issue. Similar to proposing new projects, proposals to move projects
to different lifecycle stage should also be announced on [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community)
by sending an email for increased visibility.

### Project Acceptance Process

Project review and acceptance happen directly on the issue asking for project creation. If community members
require further discussions, ad-hoc meetings can be scheduled to discuss the proposal further but this is not
mandatory.

Simple majority of Eiffel Community Maintainers is required for a project to be accepted to Eiffel Community.

Project maintainers are expected to update [PROJECTS.md](./PROJECTS.md) by sending a pull request to community
repository and include an entry for their project. Project acceptance is concluded upon acceptance of the pull
request. When accepted, the maintainers of the accepted project should create the repository in accordance with the [repository checklist](https://github.com/eiffel-community/eiffel-repository-template/blob/master/repo-checklist.md). When the new repository is created, the Eiffel Community Maintainers will merge the corresponding pull request.

Upon completion of the project creation process, TC Chair sends an email to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community)
in order to announce the creation of the project to the broader community for increased visibility.

## Project Lifecycle Stages

Eiffel Community follows the practice set by other communities and places projects maintained by community under
different stages. This approach allows current and future contributors and users of Eiffel to be able to see how
well a given project is maintained, how much support one can expect from the community when it comes to problems
faced by the users, whether project is actively developed or not, and if the project is used in production.

Discussion around moving projects across different stages are driven by project maintainers. Similar to project
acceptance process, maintainers of a project must submit an issue on Eiffel Community repository to formally
request project review stating their intention to move the project to a different stage from where the project
is at the time of the request. Project review and potential move of it to a different stage happens and is agreed
directly on the issue asking for project review. Ad-hoc meetings can be scheduled to discussion the issue further
but this is not mandatory.

If a project is accepted to be moved to a certain stage, this is clearly marked on project repositories to make it
easier for potential users to see where the project is in its lifecycle. In addition to stating the project lifecycle
stage listed on the project repositories, project maintainers are expected to update [PROJECTS.md](./PROJECTS.md) via
a pull request to community repository, updating the stage of their project for broader visibility. Project review
is concluded upon acceptance of the pull request.

Upon completion of the project lifecycle process, TC Chair sends an email to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community)
in order to announce the changes to project lifecycle stage to the broader community for increased visibility.

### Stage: Sandbox

Sandbox stage is for the projects that are at the early stages of their development lifecycle such as newly created
projects or the projects with heavy initial development going on.

The sandbox stage provides value to the contributors by increasing the visibility of their idea, get additional
contributors, experiment with new concepts, and help advance Eiffel in different directions. However, the projects
in sandbox stage may not be suited for production uses or the project maintainers and contributors may be unable
unable or unwilling to support such use. In this case, the main responsibility falls on the users to ensure their
experiences and findings are shared with the rest of the project and broader Eiffel Community and necessary improvements
are contributed to the projects.

Project admitted to Eiffel Community start their life in Sandbox stage. How long a project can stay in Sandbox stage
depends on the activity and maturity of the project and there is no minimum time is set for the project to seek for
moving to a different stage.

Due to the nature of sandbox projects (eg. experimentation), project can be moved to archive stage at any point in
time if the maintainers deem it necessary.

You should use the [![Sandbox badge](https://img.shields.io/badge/Stage-Sandbox-yellow)](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-sandbox) badge to show the project stage. Place the badge under the logo but before the heading (see e.g. [Eiffel Intelligence README](https://github.com/eiffel-community/eiffel-intelligence/blob/master/README.md)).

```markdown
[![Sandbox badge](https://img.shields.io/badge/Stage-Sandbox-yellow)](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-sandbox)
```

### Stage: Graduated

Graduated stage is for the projects that achieved production level functionality and quality. Eiffel Community
expects projects in Graduated stage to be active, both within the community and towards their users.

In order for a project to be moved to the Graduated stage, the project must demonstrate successful use of it in
production by at least **one** user. In addition to production use, projects applying for Graduated stage must have
maintainers from at least **two** different organizations and a healthy number of committers for the sustainable
development and use of the project. This helps potential users of the projects to know that the project achieved
certain level of maturity, both in its development and real-life use, and there is another organization using
the project successfuly in production. In addition to real-life use, they will also know that the project is
actively maintained and they can turn to community for additional support.

Simple majority within Eiffel Community Maintainers is required for a project to be moved to Graduated stage.

You should use the [![Graduated badge](https://img.shields.io/badge/Stage-Graduated-green)](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-graduated) badge to show the project stage. Place the badge under the logo but before the heading (see e.g. [Eiffel Intelligence README](https://github.com/eiffel-community/eiffel-intelligence/blob/master/README.md)).

```markdown
[![Graduated badge](https://img.shields.io/badge/Stage-Graduated-green)](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-graduated)
```

### Stage: Archived

Archived stage is for the projects that do not expect further development or maintenance and may very well be
in dormant state.

This stage is especially important for users to know that they may use the project but they may not get the
support they expect from the community given that the project is in archived stage. In some case, such users
may be willing to take over the project and bring it back to active state. This is also possible and the users
can state their intention by submitting an issue to Eiffel Community repository,stating their intention to do
so. It the community accepts the request, the project is moved from Archived stage to Sandbox stage.

Simple majority within Eiffel Community Maintainers is required for a project to be moved to Archived stage.

You should use the [![Archived badge](https://img.shields.io/badge/Stage-Archived-orange)](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-archived) badge to show the project stage. Place the badge under the logo but before the heading (see e.g. [Eiffel Intelligence README](https://github.com/eiffel-community/eiffel-intelligence/blob/master/README.md)).

```markdown
[![Archived badge](https://img.shields.io/badge/Stage-Archived-orange)](https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-archived)
```

## References

- https://www.opnfv.org/software/technical-project-governance/project-lifecycle
- https://github.com/cdfoundation/toc/blob/master/PROJECT_LIFECYCLE.md
- https://www.cncf.io/sandbox-projects/
- https://github.com/cncf/toc/blob/master/process/graduation_criteria.adoc
