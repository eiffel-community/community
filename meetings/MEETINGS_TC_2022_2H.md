###### tags: `Technical Committee`

# Technical Committee Meetings 2022 2H

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2022-12-15 Meeting](#December-15-2022)
    * [2022-12-01 Meeting](#December-1-2022)
    * [2022-11-24 Meeting](#November-24-2022)
    * [2022-11-17 Meeting](#November-17-2022)
    * [2022-11-03 Meeting](#November-3-2022)
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

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/i0Hf5jlySEyIJ8oOuwm2pw) in order to prevent notes getting out of sync.

### December 15, 2022

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
    * 0.2 scoping in progress with a Feb 2023 target. 0.3 targeted for April/May 2023.
* Meetings during upcoming holidays
    * Next weeks extra TC meeting? Canceled
    * Meetings during w52 and 1 canceled
    * Next ordinary TC meeting on Jan 12th
* Monthly Community meetings
    * January meeting postponed to Jan 19th
    * Topic for Jan 19th: Protocol issue backlog cleanup
    * Action Emil: Update meeting invite to state the topic. On the Jan 12 TC meeting we'll decide which issues to actually talk about.
        * Done
    * Action Emil: Create a project board for the protocol to handle priorities for the protocol issues. Readable by all in the community and writeable by protocol maintainers.
        * Done: https://github.com/orgs/eiffel-community/projects/6/views/1
* Update to TC members list
    * Azeem will leave the TC now due to overbooked seats from Ericsson.
    * Action Magnus: Follow [checklist](https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md) to revert Azeems's authorities etc
* https://www.youtube.com/@EiffelCommunity now shows more videos
* Scope and purpose of security officer issue ([github.com/eiffel-community/community#141](https://github.com/eiffel-community/community/issues/141))
    * Initial PR merged, still work TBD regarding maintainers' responsibilities and Dependabot.
* Eiffel TC Task board(s)
    * Add a dedicated protocol board with all protocol issues and clean up the [current TC board](https://github.com/orgs/eiffel-community/projects/3/views/4) to only contain "[community issues](https://github.com/search?l=&p=1&q=state%3Aopen+repo%3Aeiffel-community%2Feiffel-playground+repo%3Aeiffel-community%2Fcommunity+repo%3Aeiffel-community%2Feiffel-repository-template+repo%3Aeiffel-community%2Feiffel-community.github.io+repo%3Aeiffel-community%2F.github&ref=advsearch&type=Issues)"?
        * We'll add a new public board for protocol issues but more to prioritize them, e.g. for protocol workshops.
        * The existing TC board shouldn't get all protocol issues but rather those with a community impact, e.g. the YAML conversion, experimental versions, etc, but _not_ straight-up protocol changes like "add link type X to event Y".
    * Should e.g. [ER PR#12](https://github.com/eiffel-community/eiffel-event-repository/pull/12) really be on the TC board?
        * Maybe not, but let's keep it for now.
* TC being member of all maintainer Google groups (see AP below)
    * What role? A group cannot be a manager/owner
    * ![](https://i.imgur.com/KyFILA2.png)
    * Suggestion: Add all TC members individually, as owners, to each group
        * Yes. But no. See next point.
    * What about synch between the Google group and corresponding GitHub group? Could we script the updates of google groups?
        * Decision: Deprecate mailing lists in favor of GitHub discussions/issues/PRs. They're hardly used and mostly created administrative overhead. Draft issue created.
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: [Common branching strategy?](https://github.com/eiffel-community/community/issues/150)
* Out of time, postponed: PRs and issues

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
    * Update 2022-11-03: Emil and Mattias will talk to Nordix.
    * Update 2022-11-17: New Nordix contact established.
    * Update 2022-12-01: We now have access to a k8s cluster via a jumphost. No inbound access from the internet though.
* TC: Add all TC members to all existing Eiffel Google groups
    * **Update 2022-12-12:** With what role? See also https://github.com/eiffel-community/community/pull/155
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* ~~Magnus: Run through checklist for Azeem.~~
    * ~~2022-08-08: Almost done; the YouTube ownership invite is still pending.~~
    * ~~**Update 2022-12-12:** Azeem will leave TC. Should this action be considered done?~~
        * ~~Yes.~~
* ~~TC: Announce new Dependabot policy on mailing list.~~
    * ~~**Update 2022-12-12:** To be handled through https://github.com/eiffel-community/community/issues/153~~
* TC: Investigate if we can obtain legal assistance from Software Center.
* Emil: Send invite for separate meeting to discuss event linking vs. CDevents.
    * **Update 2022-12-12:** https://www.when2meet.com/?17987352-Gk4R3
* Emil: Update Jan 19 community meeting invite to state the topic. On the Jan 12 TC meeting we'll decide which issues to actually talk about.
* Magnus: Follow [checklist](https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md) to revert authorities for Azeem.
* Emil: Create a project board for the protocol to handle priorities for the protocol issues. Readable by all in the community and writeable by protocol maintainers.

### December 1, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, not present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, present
* Others
    * Per-Arne Landström
    * Jonathan Dartland

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
    * [cdevents.dev](https://cdevents.dev/) refresh ongoing
    * Event linking is being discussed again. Link use cases need to be described.
* Monthly Community meeting
    * Revisit the topic of the December meeting
        * Keep previous topics (deployment events, DORA, beta events).
        * Action Emil: Send invite for separate meeting to discuss event linking vs. CDevents.
    * Date of the January meeting
        * Postpone the community meeting series and the extra TC meeting series two weeks, i.e. the January community meeting takes place on January&nbsp;19.
* Release notes and labels ([github.com/eiffel-community/eiffel#336](https://github.com/eiffel-community/eiffel/pull/336))
    * Tobias suggested a &lt;details&gt; element for listing all remaining PRs apart from those labeled protocol and protocol-incompat.
    * Draft issue created to document exactly how the protocol and protocol-incompat labels should be used as that isn't entirely clear.
* [Usage of EnvironmentDefined](https://github.com/eiffel-community/eiffel/issues/337)
* Out of time, postponed: https://www.youtube.com/@EiffelCommunity now shows more videos
* Out of time, postponed: Scope and purpose of security officer issue ([github.com/eiffel-community/community#141](https://github.com/eiffel-community/community/issues/141))
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: [Common branching strategy?](https://github.com/eiffel-community/community/issues/150)
* Out of time, postponed: PRs and issues

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
    * Update 2022-11-03: Emil and Mattias will talk to Nordix.
    * Update 2022-11-17: New Nordix contact established.
    * Update 2022-12-01: We now have access to a k8s cluster via a jumphost. No inbound access from the internet though.
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* TC: Announce new Dependabot policy on mailing list.
* Azeem: Investigate if we can obtain legal assistance from Software Center.
* Emil: Send invite for separate meeting to discuss event linking vs. CDevents.

### November 24, 2022

#### Participants
* TC Attendees
    * Azeem Ahmad, not present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, not present
* Others
    * Claes Richárd, Nasdaq
    * Jonathan Dartland, Nasdaq

#### Agenda and Notes

- What are the general and specific takeaways from the summit?
- What support would Nasdaq’s need from Eiffel Community/TC to benefit even more from their Eiffel deployment?
    - Environment events are of interest.
    - How does e.g. Eiffel Intelligence respond to protocol changes?
    - Who/What validates events? Where should it take place?
- What would Nasdaq like to see happening next in the Eiffel Community, w.r.t. protocol updates, meetups/summits, online discussions, etc.?

### November 17, 2022

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
    * Refresh of https://cdevents.dev/ ongoing.
    * Link discussion still going on.
* We now have a handle for the Eiffel community `@EiffelCommunity`. You can see it from https://www.youtube.com/handle if you are logged in.
* Monthly Community meeting
    * Good attendance on Nov 10th. 14 people from 5 organizations (Axis, Ericsson, EST, LiU, Nasdaq)
    * Recordings: https://www.youtube.com/playlist?list=PLU5MfFmhN7pz2mHqjBJPASqy_1n4zScG0
    * Topics for next meeting on Dec 8th?
        * Proposal documented on HackMD doc
* New edition of the protocol - Arica
    * Good to go
* Review requests
    * Do we have an issue with our review request process?
    * Are people using the notification panel or how are review requests tracked?
    * We're just lazy... We could ping each other on Slack if an urgent review is needed
* How do we include new people in the Community?
    * Continue asking people who show interest for more information about the nature of their interest.
* [Dependabot PRs](https://github.com/pulls?q=is%3Apr+is%3Aopen+archived%3Afalse+sort%3Aupdated-desc+user%3Aeiffel-community+dependabot) - What to do about these?
    * Action Emil: Make sure the maintainer guidelines are updated with the need to act on Dependabot updates/alerts.
    * Repositories that are de facto inactive and don't update their dependencies should be considered for demotion to dormant.
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: [Common branching strategy?](https://github.com/eiffel-community/community/issues/150)
* Out of time, postponed: PRs and issues

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
    * Update 2022-11-03: Emil and Mattias will talk to Nordix.
    * Update 2022-11-17: New Nordix contact established.
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* TC: Announce new Dependabot policy on mailing list.
* Azeem: Investigate if we can obtain legal assistance from Software Center.
* ~~Emil: Invite Nasdaq to a follow-up meeting next week.~~
* ~~Emil: Make sure the maintainer guidelines are updated with the need to act on Dependabot updates/alerts.~~
    * ~~Draft issue created.~~

### November 3, 2022

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
    * CDEvents v0.1.1 was announced at KubeCon.
    * Adapter between GitHub Action and CDEvents was discussed on Tuesday.
* New edition of the protocol
    * All changes in Arica are ready. Let's cut this new edition.
* How do we deal with pre-v1 experimental event types?
    * There are a number of things to sort out. Draft issue created.
* State of ArangoDB
    * Interesting option, but neither Axis nor Ericsson have the bandwidth to move forward with an in-depth evaluation.
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: [Common branching strategy?](https://github.com/eiffel-community/community/issues/150)
* Out of time, postponed: PRs and issues

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
    * Update 2022-11-03: Emil and Mattias will talk to Nordix.
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* Magnus: Run through checklist for Azeem.
    * 2022-08-08: Almost done; the YouTube ownership invite is still pending.
* TC: Announce new Dependabot policy on mailing list.
* Azeem: Investigate if we can obtain legal assistance from Software Center.
* TC: Invite Nasdaq to a follow-up meeting in before EOY.


### October 20, 2022

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
    * Closing in on the 0.1 release.
    * Custom data discussions ongoing. Can currently either be an arbitrary JSON object or a string.
* Summit follow-up
    * Action TC: Invite Nasdaq to a follow-up meeting in 1–2 months.
* We currently have many issues in https://github.com/eiffel-community/eiffel/issues. Should we take an extra TC meeting or a community meeting to screen all issues to see if they still are applicable?
    * Yes, but not at the next extra TC meeting (Oct 27). Let's do it on Nov 24. Also issues in community repo and others we're maintainers of.
    * Next week we focus on getting the Arica edition out the door.
* https://github.com/eiffel-community/eiffel-jira-plugin/pulls has two open PRs but no maintainer have looked at them. What do we do?
    * Move repository to the new dormant state. Draft issue created.
* Out of time, postponed: State of ArangoDB
* Out of time, postponed: How do we deal with pre-v1 experimental events types?
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: PRs and issues

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
