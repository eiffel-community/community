###### tags: `Technical Committee`

# Technical Committee Meetings 2022 2H

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2022-10-20 Meeting](#October-20-2022)
    * [2022-10-06 Meeting](#October-6-2022)
    * [2022-09-29 Meeting](#September-29-2022)
    * [2022-09-22 Meeting](#September-22-2022)
    * [2022-09-08 Meeting](#September-8-2022)
    * [2022-08-25 Meeting](#August-25-2022)
    * [2022-08-11 Meeting](#August-11-2022)

## Logistics

* **When:** 13:00 - 14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_OTc1NDIzNTUtYzJiMy00OThiLTkwZDUtYTdkODVhOGNjYzI3%40thread.v2/0?context=%7b%22Tid%22%3a%2292e84ceb-fbfd-47ab-be52-080c6b87953f%22%2c%22Oid%22%3a%2249725723-aa8c-4dcf-b9d0-b974e8a25702%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg) in order to prevent notes getting out of sync.

### Next

* June 2023: Elect security officers - https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#security-officers
    * This should be covered by a post-election checklist.
* [Dependabot PRs](https://github.com/pulls?q=is%3Apr+is%3Aopen+archived%3Afalse+sort%3Aupdated-desc+user%3Aeiffel-community+dependabot)

### October 20, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, present / not present
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
    * The TC GitHub project: https://github.com/orgs/eiffel-community/projects/3/views/4
* Updates from CDF sig-events, Emil & Mattias
    * Closing in on the 0.1 release.
    * Custom data discussions ongoing. Can currently either be an arbitrary JSON object or a string.
* Summit follow-up
    * Action TC: Invite Nasdaq to a follow-up meeting in 1–2 months.
* We currently have many issues in https://github.com/eiffel-community/eiffel/issues. Should we take an extra TC meeting or a community meeting to screen all issues to see if they still are applicable?
    * Yes, but not at the next extra TC meeting (Oct 27). Let's do it on Nov 24. Also issues in community repo and others we're maintainers of.
    * Next week we focus on getting the Arica edition out the door.
* https://github.com/eiffel-community/eiffel-jira-plugin/pulls has two open PRs but no maintainer have looked at them. What do we do?
    * Move repository to the new dormant state. Draft issue created.
* State of ArangoDB
* How do we deal with pre-v1 experimental events types?
* Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* PRs and issues

#### Action Items
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
    * Update 2022-01-27: Probably simple to fix, Tobias to ping Robert at Nordix.
    * Update 2022-02-17: Tobias has pinged Robert. Waiting for response.
    * Update 2022-09-29: Robert has promised to fix the problem this month.
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the summit.
* ~~Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.~~
    * ~~This can be transformed into an issue~~
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* TC: Announce new Dependabot policy on mailing list.
* Azeem: Investigate if we can obtain legal assistance from Software Center.
* TC: Invite Nasdaq to a follow-up meeting in 1–2 months.

### October 6, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, not present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, present

* Others
    * Kristofer Hallén, first 15 minutes
    * Fredrik Fristedt

#### Agenda and Notes

* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
* Action Item Review, All
    * The TC GitHub project: https://github.com/orgs/eiffel-community/projects/3/views/4
    * Who transforms the draft issues to real ones?
        * Draft issues should always have an assignee. That person is responsible for writing the actual issue.
* Updates from CDF sig-events, Emil & Mattias
    * Event versions will have major.minor.patch versioning.
    * 0.1 will be announced at CD Summit in Detroit on Oct 25.
    * Package URLs will be mandatory as artifact id.
* Summit preparations
* The Dependabot setting from last TC meeting had no effect, or?
    * Ask security officers to sort out why maintainers get alert but not organization owners.
    * Action security officers: Update the security process to handle Dependabot alerts and maintainer responsibilities. Draft issue created.
* Next Community workshop
    * Proposal: Cancel the meeting on Oct 13th, focus Nov 10th on Axis visualization solution and Jalander's Eiffel/CDEvents PoC
    * So decided. Ola Söder from Axis should be invited.
* Add state "dormant" to project lifecycle stages?
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md
    * For example Easy2Use, Jira plugin
    * Reference: https://github.com/hyperledger/tsc/blob/gh-pages/project-lifecycle.md#project-lifecycle
    * Draft issue created.
* Eiffel name copyright/trademark, [see mail thread](https://groups.google.com/g/eiffel-tc/c/820cEy2mkKU/m/bXzAs3TOAAAJ?utm_medium=email&utm_source=footer)
    * Action Azeem: Investigate if we can obtain legal assistance from Software Center.
* Out of time, postponed: We currently have 32 issues in https://github.com/eiffel-community/eiffel/issues. Should we take an extra TC meeting or a community meeting to screen all issues to see if they still are applicable?
* Out of time, postponed: https://github.com/eiffel-community/eiffel-jira-plugin/pulls has two open PRs but no maintainer have looked at them. What do we do?
* Out of time, postponed: State of ArangoDB
* PRs and issues

#### Action Items
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
    * Update 2022-01-27: Probably simple to fix, Tobias to ping Robert at Nordix.
    * Update 2022-02-17: Tobias has pinged Robert. Waiting for response.
    * Update 2022-09-29: Robert has promised to fix the problem this month.
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* TC: Announce new Dependabot policy on mailing list.
* ~~Emil: Update invite for next extra TC meeting to include security officers so that we can discuss exactly how to deal with alerts.~~
* ~~Emil: Create pull request for populating summit agenda with responsible speaker/moderator for each session.~~
    * ~~[github.com/eiffel-community/eiffel-community.github.io#36](https://github.com/eiffel-community/eiffel-community.github.io/pull/36)~~
* Azeem: Investigate if we can obtain legal assistance from Software Center.

### September 29, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, not present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, not present
    * Tobias Persson, present

#### Agenda and Notes

* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
* Action Item Review, All
    * The TC GitHub project: https://github.com/orgs/eiffel-community/projects/3/views/4
    * Who transforms the draft issues to real ones?
* Updates from CDF sig-events, Emil & Mattias
    * Event versioning being discussed. Individual events will have major.minor versions, protocol as a whole will have major.minor.patch versioning. DRAFT versions will be used (similar to Maven-style SNAPSHOT versioning).
* Summit preparations
    * Action Emil: Create pull request for populating summit agenda with responsible speaker/moderator for each session.
* The Dependabot setting from last TC meeting had no effect, or?
    * Ask security officers to sort out why maintainers get alert but not organization owners.
* Do we want a linter for our MarkDown?
    - https://github.com/eiffel-community/eiffel/pull/304/checks gives a lot of errors
    - Yes, good idea. We just need to sort out the line length issue.
* New Slack pricing plans
    - https://slack.com/blog/news/pricing-and-plan-updates
    - Are there any decent options to Slack?
    - New 90-day retention has been in effect for a few weeks now and we're fine with it. No action will be taken for now.
* Generate HTML pages from our MarkDown files?
    * CDEvents as an example
    * Yes, we should do that. The files could be published to the existing github.io page.
* Graphite.dev
    * Any good news?
    * Graphite has been dropped from the GitHub organization since nobody is using it.
* Out of time, postponed: Add state "dormant" to project lifecycle stages?
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md
    * For example Easy2Use, Jira plugin
* Out of time, postponed: Eiffel name copyright/trademark, [see mail thread](https://groups.google.com/g/eiffel-tc/c/820cEy2mkKU/m/bXzAs3TOAAAJ?utm_medium=email&utm_source=footer)
* Out of time, postponed: We currently have 32 issues in https://github.com/eiffel-community/eiffel/issues. Should we take an extra TC meeting or a community meeting to screen all issues to see if they still are applicable?
* Out of time, postponed: https://github.com/eiffel-community/eiffel-jira-plugin/pulls has two open PRs but no maintainer have looked at them. What do we do?
* Out of time, postponed: State of ArangoDB
* PRs and issues

#### Action Items
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
    * Update 2022-01-27: Probably simple to fix, Tobias to ping Robert at Nordix.
    * Update 2022-02-17: Tobias has pinged Robert. Waiting for response.
    * Update 2022-09-29: Robert has promised to fix the problem this month.
* ~~Magnus: Propose new policy of how to deal with the issue requirement for new development.~~
    * ~~https://github.com/eiffel-community/community/issues/138~~
* ~~TC: Write issue about describing process for archiving projects and do archive eiffel-remrem-shared~~
    * ~~remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30 (library not actually used but there are still references to it)~~
    * ~~https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-archived~~
    * ~~Update 2022-09-05: eiffel-remrem-shared has been archived. Draft issue to document process written.~~
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* ~~Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?~~
    * ~~Draft issue created.~~
* Magnus: Announce podcast episode on LinkedIn.
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* ~~Mattias: Locate good place to post potential master thesis projects.  **Updated**~~
    - ~~Can we for now create a HackMD document to track ideas on Master Thesis subjects?~~
    - ~~We could link to it from the community README.md page. No!~~
    - ~~Mattias to create HackMD document and announce it.~~
        - ~~https://hackmd.io/os5oiqOOT_WW64yi8s_X1Q but how do we find/remember it?~~
* TC: Announce new Dependabot policy on mailing list.
* Emil: Update invite for next extra TC meeting to include security officers so that we can discuss exactly how to deal with alerts.
* Emil: Create pull request for populating summit agenda with responsible speaker/moderator for each session.
 
### September 22, 2022

Meeting canceled

### September 8, 2022

Meeting canceled

### August 25, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, not present
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
    * The TC GitHub project: https://github.com/orgs/eiffel-community/projects/3/views/4
* Updates from CDF sig-events, Emil & Mattias
    * Demo on Aug 24 of integration between Eiffel and CDEvents, building upon the old PoC of CDEvents.
* Appoint Security Officers
    * Suggestion to appoint past security officers Kristofer Hallén and Fredrik Fristedt to a new term that ends 2023-05-31, i.e. after the next TC has taken its place.
        * Hereby decided.
* Summit preparations
    * First meeting held with Nasdaq on Aug 22. Follow-ups will be held every other Monday. See [summit document](https://hackmd.io/@eiffel-community/H118K7P59).
* Follow-up from community meeting about deployment events on Aug 18th
    * No concrete outcome from last meeting.
    * To make the discussion move forward we should try structuring and scoping things better so we're not talking in circles. Maybe we can try copying CDEvents' deployment events and see if they'd work? Spending maybe on hour on that would probably help follow-up discussions a lot.
* Next community meeting Sep 15th. What topic?
    * First half to work on the summit agenda.
    * Second half to have the meta discussion about deployment events.
* Next week's extra TC meeting. What to bring up?
    * Sort out how to handle security alerts. Requires Security Officers to be part of the meeting. Emil will check if they can attend.
    * Look into the summit agenda.
    * If there's time, look into the deployment event meta discussion.
* The Dependabot setting from last TC meeting had no effect, or?
    * Ask security officers to sort out why maintainers get alert but not organization owners.
* Out of time, postponed: Do we want a linter for our MarkDown?
    - https://github.com/eiffel-community/eiffel/pull/304/checks gives a lot of errors
* Out of time, postponed: New Slack pricing plans
    - https://slack.com/blog/news/pricing-and-plan-updates
    - Are there any decent options to Slack?
* Out of time, postponed: Generate HTML pages from our MarkDown files?
    * CDEvents as an example
* Out of time, postponed: Graphite.dev
    * Any good news?
* Out of time, postponed: Add state "dormant" to project lifecycle stages?
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md
    * For example Easy2Use, Jira plugin
* Out of time, postponed: Eiffel name copyright/trademark, [see mail thread](https://groups.google.com/g/eiffel-tc/c/820cEy2mkKU/m/bXzAs3TOAAAJ?utm_medium=email&utm_source=footer)
* Out of time, postponed: PRs and issues

#### Action Items
* ~~Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.~~
     * ~~Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet~~
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
    * Update 2022-01-27: Probably simple to fix, Tobias to ping Robert at Nordix.
    * Update 2022-02-17: Tobias has pinged Robert. Waiting for response.
* Magnus: Propose new policy of how to deal with the issue requirement for new development.
* TC: Write issue about describing process for archiving projects and do archive eiffel-remrem-shared
    * remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30 (library not actually used but there are still references to it)
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-archived
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?
* Magnus: Announce podcast episode on LinkedIn.
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* Mattias: Locate good place to post potential master thesis projects.
    - Can we for now create a HackMD document to track ideas on Master Thesis subjects?
    - We could link to it from the community README.md page. No!
    - Mattias to create HackMD document and announce it.
* ~~Emil/Magnus: Set up separate meeting series with Nasdaq to plan summit practicalities.~~
* ~~Emil: Send meeting invite for the monthly community meetings.~~
* ~~Magnus: Ask current security officers (Kristofer Hallén, Fredrik Fristedt) if they want to continue.~~
    * ~~Update 2022-08-25: Questions posed, both candidates accepted.~~
* ~~Magnus: Create issue to update GOVERNANCE.md with dates of current term of security officers.~~
    * ~~https://github.com/eiffel-community/community/issues/137~~
* ~~Tobias: Talk to Fredrik Fristedt about ensuring that the security mailing list accepts messages.~~
    - ~~Email has been fixed~~
* ~~TC: Add item on new-TC-member checklist to enable some kind of notification (immediate and/or digest) of Dependabot alerts.~~
    * ~~Draft task added on https://github.com/orgs/eiffel-community/projects/3/views/4.~~
* TC: Announce new Dependabot policy on mailing list.
* Emil: Update invite for next extra TC meeting to include security officers so that we can discuss exactly how to deal with alerts.

### August 11, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, not present
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
    * Discussions around developing a reference architecture for CD, which may involve CDevents.
    * SDKs for CDevents being created; Go, Python, and Java.
* Discuss how to plan the October summit
    * Action Emil/Magnus: Set up separate meeting series with Nasdaq to plan summit practicalities.
    * Discuss contents on TC meetings and document on https://hackmd.io/@eiffel-community/H118K7P59.
* Planning of future [monthly community meetings](https://hackmd.io/@eiffel-community/HkT_NdBUF)
    * Action Emil: Send meeting invite for the monthly meetings.
    * Next week's meeting to cover two topics: first hour summit planning, second hour deployment events.
* Follow-up from community meeting about deployment events on June 30th
    * What's the way forward?
    * Continue discussion next week.
* Security officers need to be re-elected
    - https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#security-officers
    - TC appoints security officers.
    - Action Magnus: Ask current officers (Kristofer Hallén, Fredrik Fristedt) if they want to continue.
    - Action Magnus: Create issue to update GOVERNANCE.md with dates of current term of security officers.
* Can't send mails to eiffel-community-security@googlegroups.com
    - Action Tobias: Talk to Fredrik about ensuring that mailing list works.
* Dependabot alerts
    - Some repos have alerts/PRs creation activated. Should we have it for all Eiffel repos?
    - Enable for all? https://github.com/organizations/eiffel-community/settings/security_analysis
    - Enable per repo? https://github.com/eiffel-community/eiffel-easy2use/settings/security_analysis
    - Make sure TC people always get notifications?
    - Add notifications in your profile: https://github.com/settings/notifications
    - Should security officers subscribe to such notifications? https://github.com/eiffel-community/.github/blob/master/SECURITY.md
    - Action TC: Add item on new-TC-member checklist to enable some kind of notification (immediate and/or digest) of Dependabot alerts.
    - Decision: Dependabot alerts enabled for new and all existing repos. PRs enabled for new repos.
    - Action TC: Announce aforementioned new policy on mailing list.
    - Action Emil: Update invite for next extra TC meeting to include security officers so that we can discuss exactly how to deal with alerts.
* Should we create issues for all TC APs that becomes a PR in the protocol repo?
    - E.g. https://github.com/eiffel-community/eiffel/pull/297
    - You can include PRs in a milestone but is it better with an issue?
    - Decision: For actions that we expect will become PRs, create a draft issue in the TC GitHub board and assign the issue. The assignee gets to complete the issue. Other actions will be kept in the TC meeting MoM action list.
* Out of time, postponed: Do we want a linter for our MarkDown?
    - https://github.com/eiffel-community/eiffel/pull/304/checks gives a lot of errors
* Out of time, postponed: New Slack pricing plans
    - https://slack.com/blog/news/pricing-and-plan-updates
    - Are there any decent options to Slack?
* Out of time, postponed: Generate HTML pages from our MarkDown files?
    * CDEvents as an example
* Out of time, postponed: Graphite.dev
    * Any good news?
* Out of time, postponed: Add state "dormant" to project lifecycle stages?
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md
    * For example Easy2Use, Jira plugin
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
* TC: Write issue about describing process for archiving projects and do archive eiffel-remrem-shared
    * remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30 (library not actually used but there are still references to it)
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-archived
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?
* ~~Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a podcast link there.~~
    * ~~https://github.com/eiffel-community/eiffel-community.github.io/pull/33~~
* Magnus: Announce podcast episode on LinkedIn.
* ~~Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.~~
    * ~~https://github.com/eiffel-community/eiffel-community.github.io/pull/32~~
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* Mattias: Locate good place to post potential master thesis projects.  **UPDATED**
    - Can we for now create a HackMD document to track ideas on Master Thesis subjects? 
    - We could link to it from the community README.md page. No!
    - Mattias to create HackMD document and announce it.
* ~~Emil: Send summit placeholder calendar invite as soon as dates have been confirmed.~~
* ~~Emil/Mattias: Sort out with Ericsson Software Technology whether Nordix can be used for an ArangoDB evaluation. **UPDATED**~~
    * ~~Should be possible~~
* ~~Magnus: Comment in [existing PR](https://github.com/eiffel-community/eiffel-event-repository/pull/12) which features that aren't necessary in a minimal ER lookup API spec.~~
* Emil/Magnus: Set up separate meeting series with Nasdaq to plan summit practicalities.
* Emil: Send meeting invite for the monthly community meetings.
* Magnus: Ask current security officers (Kristofer Hallén, Fredrik Fristedt) if they want to continue.
* Magnus: Create issue to update GOVERNANCE.md with dates of current term of security officers.
* ~~Tobias: Talk to Fredrik Fristedt about ensuring that the security mailing list accepts messages.~~
    - ~~Email has been fixed~~
* TC: Add item on new-TC-member checklist to enable some kind of notification (immediate and/or digest) of Dependabot alerts.
* TC: Announce new Dependabot policy on mailing list.
* Emil: Update invite for next extra TC meeting to include security officers so that we can discuss exactly how to deal with alerts.
