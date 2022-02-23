###### tags: `Technical Committee`

# Technical Committee Meetings 2022

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2022-02-10 Meeting](#February-10-2022)
    * [2022-01-27 Meeting](#January-27-2022)
    * [2022-01-13 Meeting](#January-13-2022)

## Logistics

* **When:** 13:00 - 14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_MDljZGI1ZDEtOGRhYS00NzlmLTlkZTgtNTM4OGMwNmU3ZTVh%40thread.v2/0?context=%7b%22Tid%22%3a%22d2585e63-66b9-44b6-a76e-4f4b217d97fd%22%2c%22Oid%22%3a%22b5142d0f-6dad-4704-99f5-29b74621c34a%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg) in order to prevent notes getting out of sync.

### February 10, 2022

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
* Updates from CDF sig-events, Emil & Mattias
* Summit planning
    * Physical two-day meetup first half of May, focused on workshopping rather than presentations.
    * Lund or Linköping or somewhere in between?
    * Summit in the autumn - physical or combined? 2-3 days. In October?
    * To be followed up next TC meeting
    * Action: TC to propose good dates for meetup
* Show what Ericsson is prioritizing for development https://github.com/orgs/eiffel-community/projects/2/views/1
* What about copyright headers - in what files should they exist? See https://github.com/eiffel-community/eiffel/pull/292#issuecomment-1005838062
    * Mattias: Check mail thread on this subject in Ericsson
    * Magnus: Check in Axis for recommendations
* Should we add a SECURITY.md file ([docs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#supported-file-types))?
    * Yes. Move the one we have in community repo to .github. Action Tobias
* Community meeting: reflections and plan for next
    * To be discussed on next weeks extra TC meeting
* Should we require maintainers to be watchers of the repositories they maintain? https://github.com/watching, example: https://github.com/eiffel-community/eiffel/watchers
    * Yes. To be enforced in a coming guideline/rules for the maintainer role. Action TC
    * Could it be enforced through e.g. Github workflows? Action Magnus
* Out of time, postponed: Planning of the next protocol edition
* Out of time, postponed: PRs and issues

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
    * Update 2022-01-27: Probably simple to fix, Tobias to ping Robert at Nordix.
    * Update 2022-02-17: Tobias has pinged Robert. Waiting for response.
* Magnus: Propose new policy of how to deal with the issue requirement for new development.
* ~~Magnus: Process for how to lift event versions when meta object is updated needs to be added to the protocol meta PR. Ask Sven to do it?~~
    * ~~https://github.com/eiffel-community/eiffel/issues/279~~
* ~~Mattias/Emil: Set up 2FA for your account on the GitHub organization, https://github.com/orgs/eiffel-community/people?query=role%3Aowner~~
* TC: Write issue about describing process for archiving projects and do archive eiffel-remrem-shared
    * remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30 (library not actually used but there are still references to it)
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-archived
* TC: Add all TC members to all existing Eiffel Google groups
* Tobias: Amend the repo creation checklist in the eiffel-repository-template repo to state that TC members should be added as owners to any created Google Groups.
    * https://github.com/eiffel-community/eiffel-repository-template/pull/17
* Magnus: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* ~~Emil/Magnus: Revisit summit planning first half of February.~~
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Mattias: Figure out how to deal with Eiffel-adjacent repos not in the eiffel-community organization. Should they be made visible? How? Prepare a proposal on this.
* Magnus: Create issues in all repos with .travisci.yml files to have them change to GitHub Actions.
* Tobias: Add an organization README file ([docs](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)).
    * https://github.com/eiffel-community/.github/pull/16
* Fatih: Update timeline based on discussion (move elegible candidate earlier and take Easter into account) and get back to TC via mail for final confirmation.
* Fatih: Locate script for finding eligible candidates and create PR in the community repo.
* Magnus: Collect feedback from the interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Mattias: Create proposal for event type categorization.
* Magnus: Can discussion items be added to a GitHub project (along with PRs and issues)?
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil: Confirm with Henning, Daniel, and Kristofer that it's okay to remove them as GitHub organization owners.
* Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?
* Tobias: Move SECURITY.md from the community repo to the .github repo.
    * [github.com/eiffel-community/community#128](https://github.com/eiffel-community/community/pull/128)
    * [github.com/eiffel-community/.github#15](https://github.com/eiffel-community/.github/pull/15)
* Mattias: Check Ericsson email thread about which file types require copyright notices.
* Magnus: Check within Axis for recommendations on which file types require copyright notices.
* TC: Propose good dates for the May meetup.

### January 27, 2022

#### Participants

* TC Attendees
    * Emil Bäckmark, not present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, present
* Community Attendees
    * Fatih Degirmenci, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
* Updates from CDF sig-events, Emil & Mattias
    * We have a [logo](https://github.com/cdfoundation/artwork#cdevents-logos)
    * [Links in CDEvents](https://github.com/cdevents/spec/issues/10)
* GraphQL instead of EI - see mail from Jacky Gao
    * Not entirely clear what's being asked. Clarification request has been posted in [github.com/eiffel-community/eiffel-intelligence#521](https://github.com/eiffel-community/eiffel-intelligence/issues/521).
* Should we add a readme for the organization for introduction. Would go into the .github repo. See https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile for more info and https://github.com/keptn-sandbox as an example.
    * Action TC: Add an organization README file ([docs](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)).
* Discuss proposal for solving [Documentation and schemas should be generated from a common source](https://github.com/eiffel-community/eiffel/issues/282) (material will hopefully be provided by Magnus prior to meeting)
* Eiffel TC elections updates, Fatih
    * See the [doc with the proposed timeline](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw?view#Eiffel-Technical-Committee-Elections-2022)
    * Action Fatih: Update timeline based on discussion (move elegible candidate earlier and take Easter into account) and get back to TC via mail for final confirmation.
    * Action Fatih: Locate script for finding eligible candidates and create PR in the community repo.
* Python podcast follow-up
    * Action Magnus: Gather feedback from the interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Event type categorization - how to follow up [the discussion on the summit](https://hackmd.io/QEwWwRlNQ8mYKXAQKOg16A#Discussion-Event-type-categorization)?
    * Action Mattias: Create proposal for event type categorization.
* Go through https://github.com/orgs/eiffel-community/projects/3/views/1: Should we use it? If so, how?
    * Action Magnus: Can discussion items be added to the project?
    * Action Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Out of time, postponed: Show what Ericsson is prioritizing for development https://github.com/orgs/eiffel-community/projects/2/views/1
* Out of time, postponed: What about copyright headers - in what files should they exist? See https://github.com/eiffel-community/eiffel/pull/292#issuecomment-1005838062
* Out of time, postponed: PRs and issues

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
    * Update 2022-01-27: Probably simple to fix, Tobias to ping Robert at Nordix.
* ~~Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.~~
    * ~~Magnus will book meeting with Tobias and Sven for next week.~~
    * ~~Update 2022-01-27: Meetings between Magnus, Tobias, and Sven held last week. Sven is preparing material and will update the issue.~~
* Magnus: Propose new policy of how to deal with the issue requirement for new development.
* ~~Magnus: Continue examining consequences for JSON validation code when meta is extracted to a separate file.~~
* ~~Magnus: Write script for creating single-file schema files from multi-file schemas.~~
* Magnus: Process for how to lift event versions when meta object is updated needs to be added to the protocol meta PR. Ask Sven to do it?
    * https://github.com/eiffel-community/eiffel/issues/279
* Mattias/Emil: Set up 2FA for your account on the GitHub organization, https://github.com/orgs/eiffel-community/people?query=role%3Aowner
* TC: Write issue about describing process for archiving projects and do archive eiffel-remrem-shared
    * remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30 (library not actually used but there are still references to it)
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Amend the repo creation checklist in the eiffel-repository-template repo to state that TC members should be added as owners to any created Google Groups.
* TC: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* Emil/Magnus: Revisit summit planning first half of February.
* ~~Emil: Ask Daniel and Fatih if they want to continue being election officers.~~
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
* TC: Figure out how to deal with Eiffel-adjacent repos not in the eiffel-community organization. Should they be made visible? How?
* ~~Emil/Magnus: Add Event type categorization to agenda of future TC meeting.~~
* ~~TC: Make sure all current TC members are maintainers of [github.com/eiffel-community/eiffel](https://github.com/eiffel-community/eiffel) and [https://github.com/eiffel-community/eiffel-sepia](https://github.com/eiffel-community/eiffel-sepia).~~
* TC: Create issues in all repos with .travisci.yml files to have them change to GitHub Actions.
* Action TC: Add an organization README file ([docs](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)).
* Action Fatih: Update timeline based on discussion (move elegible candidate earlier and take Easter into account) and get back to TC via mail for final confirmation.
* Action Fatih: Locate script for finding eligible candidates and create PR in the community repo.
* Action Magnus: Collect feedback from the interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Action Mattias: Create proposal for event type categorization.
* Action Magnus: Can discussion items be added to a GitHub project (along with PRs and issues)?
* Action Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.


### January 13, 2022

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
* Updates from CDF sig-events, Emil & Mattias
    * CD Events presentation will be held at Fosdem Feb 5-6.
* By-election for TC?
    * David has left
    * https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#vacancies-in-technical-committee
    * Prepare for TC, Election officers and Security officers elections (2021: https://github.com/eiffel-community/community/blob/master/ELECTIONS.md)
    * No by-election planned. The main goal is to find candidates to the ordinary election later in the spring. If we find a candidate who likes to join right away we can consider a by-election.
    * Action Emil: Ask Daniel and Fatih if they want to continue being election officers.
* Python podcast follow-up
    * Interview scheduled for January 20. Magnus and Daniel Ståhl will participate.
* Set agenda for community meeting on source change events (or other topic?)
    * Next community meeting on February 3 will be about source change events. Magnus, Tobias, and Sven will prepare material.
    * The meeting after that (March 3) will concern the meta breakout. The next TC meeting on January 20 will be a working meeting to talk about the meta breakout.
* Deal with [summary/outcome](https://hackmd.io/QEwWwRlNQ8mYKXAQKOg16A#Session-recap) from the summit
    * Maintainer role. Proposition to be discussed, enhanced and enforced
        * Action: Look into proposal made in presentation.
    * How to collaborate on visualizations?
        * Added more details to [future monthly meeting topic](https://hackmd.io/mew2t6NqSBe7aRkzQkWNqg?view#Proposed-Future-Topics)
    * Consider [questions from summit](https://hackmd.io/QEwWwRlNQ8mYKXAQKOg16A?view#Eiffel-vs-CDF-SIG-Events) in SIG Events continued discussions.
        * Action Emil/Mattias: Make sure questions from the presentation are taken care of in SIG Events.
    * From Jenkins broadcaster presentation: How to show existing Eiffel repos not in the eiffel community org in github, like this Jenkins plug-in for example? How to deal with community rules for repo structures and maintenance roles?
        * Visible in [Community landscape](https://eiffel-community.github.io/community.html)
        * Action: Figure out how to deal with relevant repos not in the eiffel-community organization.
    * How to collaborate on event repository?
        * Added more details to [future monthly meeting topic](https://hackmd.io/mew2t6NqSBe7aRkzQkWNqg?view#Proposed-Future-Topics)
    * Event type categorization - how to follow up?
        * Action: Add to agenda of future TC meeting.
    * Source change events - to be handled on monthly meeting
    * Break out meta and similar structures - any actions to be taken now or as part of a coming monthly meeting?
        * Topic of next week's TC meeting.
* Additional maintainers for [github.com/eiffel-community/eiffel](https://github.com/eiffel-community/eiffel) and [https://github.com/eiffel-community/eiffel-sepia](https://github.com/eiffel-community/eiffel-sepia).
    * Action: Make sure all current TC members are maintainers of these repos.
* How to force the use of Github Actions in all repos?
    * It was decided on last TC to use it, but how do we make sure it is used? And where should we document such decisions?
    * Eiffel Intelligence uses Travis CI and now have used 27610 of 35100 credits. What are the directive for moving?
    * The Eiffel repo contains a Travis file to create tar files when releasing. Should we move that to Github Actions now? It has not run for the last 2 releases, probably due to lack of Travis credits
    * All repos with Travis file: https://github.com/search?l=&q=org%3Aeiffel-community+filename%3A.travis.yml&type=code
    * Action: Create issues in all repos with .travisci.yml files to have them change to GitHub Actions.
* Out of time, postponed: Go through https://github.com/orgs/eiffel-community/projects/3/views/1
    * Should we use it? If so, how?
* Out of time, postponed: Show what Ericsson is prioritizing for development https://github.com/orgs/eiffel-community/projects/2/views/1
* Out of time, postponed: Should we add a readme for the organization for introduction. Would go into the .github repo. See https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile for more info and https://github.com/keptn-sandbox as an example.
* Out of time, postponed: What about copyright headers - in what files should they exist? See https://github.com/eiffel-community/eiffel/pull/292#issuecomment-1005838062
* Out of time, postponed: PRs and issues

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
* ~~Emil: Go through the discussions in the summit presentations and see if there are things we should create issues from or have monthly community meetings about.~~
* Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.
    * Magnus will book meeting with Tobias and Sven for next week.
* ~~Emil: Check how CDF's Google Calendar works.~~
    * ~~It's most probably tied to a central Google account (on LinuxFoundation?) We should not tie such a calendar to a personal Google account so instead we should probably create an Eiffel Community Google account that we all get access to in one way or another.~~
    * ~~Update 2022-01-13: Too complicated. Leave it for now.~~
* Magnus: Propose new policy of how to deal with the issue requirement for new development.
* Magnus: Continue examining consequences for JSON validation code when meta is extracted to a separate file.
* Magnus: Write script for creating single-file schema files from multi-file schemas.
* Magnus: Process for how to lift event versions when meta object is updated needs to be added to the protocol meta PR. Ask Sven to do it?
    * https://github.com/eiffel-community/eiffel/issues/279
* ~~Emil: Check admin access to YouTube channel. Could all TC members be admins? Or should we all have access to a (new?) admin Google account?~~
* Mattias/Emil: Set up 2FA for your account on the GitHub organization, https://github.com/orgs/eiffel-community/people?query=role%3Aowner
* TC: Write issue about describing process for archiving projects and do archive eiffel-remrem-shared
    * remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Amend the repo creation checklist in the eiffel-repository-template repo to state that TC members should be added as owners to any created Google Groups.
* TC: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* ~~TC: Add recommendation to not use force pushes to code review guidelines.~~
    * ~~https://github.com/eiffel-community/.github/pull/13~~
* Emil/Magnus: Revisit summit planning first half of February.
* Emil: Ask Daniel and Fatih if they want to continue being election officers.
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
* TC: Figure out how to deal with Eiffel-adjaent repos not in the eiffel-community organization. Should they be made visible? How?
* Emil/Magnus: Add Event type categorization to agenda of future TC meeting.
* TC: Make sure all current TC members are maintainers of [github.com/eiffel-community/eiffel](https://github.com/eiffel-community/eiffel) and [https://github.com/eiffel-community/eiffel-sepia](https://github.com/eiffel-community/eiffel-sepia).
* TC: Create issues in all repos with .travisci.yml files to have them change to GitHub Actions.
