###### tags: `Technical Committee`

# Technical Committee Meetings 2022

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2022-08-11 Meeting](#August-11-2022)
    * [2022-06-30 Meeting](#June-30-2022)
    * [2022-06-16 Meeting](#June-16-2022)
    * [2022-06-02 Meeting](#June-2-2022)
    * [2022-05-19 Meeting](#May-19-2022)
    * [2022-05-05 Meeting](#May-5-2022)
    * [2022-04-21 Meeting](#April-21-2022)
    * [2022-04-07 Meeting](#April-7-2022)
    * [2022-03-24 Meeting](#March-24-2022)
    * [2022-03-10 Meeting](#March-10-2022)
    * [2022-02-24 Meeting](#February-24-2022)
    * [2022-02-10 Meeting](#February-10-2022)
    * [2022-01-27 Meeting](#January-27-2022)
    * [2022-01-13 Meeting](#January-13-2022)

## Logistics

* **When:** 13:00 - 14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_OTc1NDIzNTUtYzJiMy00OThiLTkwZDUtYTdkODVhOGNjYzI3%40thread.v2/0?context=%7b%22Tid%22%3a%2292e84ceb-fbfd-47ab-be52-080c6b87953f%22%2c%22Oid%22%3a%2249725723-aa8c-4dcf-b9d0-b974e8a25702%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg) in order to prevent notes getting out of sync.

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

### June 30, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, not present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, not present

#### Agenda and Notes

* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
* Updates from CDF sig-events, Emil & Mattias
* Follow-up from community meeting about deployment events on June 23rd
    * What's the way forward?
    * Short minutes available in [github.com/eiffel-community/eiffel#239](https://github.com/eiffel-community/eiffel/issues/239).
* Next week's extra TC meeting
    * Discuss deployment events or something else?
    * Yes, continue deployment event discussion.
* Summit 2022
    * Preliminary to be held in Nasdaq's premises in Stockholm in October
    * https://hackmd.io/MD7RAYeuQH6SJy61jed4ng
    * Action Emil: Send placeholder calendar invite as soon as dates have been confirmed.
* ArangoDB PoC
    * Continuation of https://github.com/eiffel-community/eiffel-persistence-technology-evaluation?
    * Follow-up called for Sep 6th 2022
    * To be performed on Nordix?
    * Action Emil/Mattias: Sort out with Ericsson Software Technology whether Nordix can be used for this evaluation.
* ER Spec
    * https://github.com/eiffel-community/eiffel-event-repository/pull/12
    * Action Magnus: Comment in existing PR which features that aren't necessary in a minimal ER lookup API spec.
* Next protocol release
    * https://github.com/eiffel-community/eiffel/milestone/7
* What projects should be pinned on https://github.com/eiffel-community?
    * [easy2use](https://github.com/eiffel-community/eiffel-easy2use) no longer pinned.
    * We should probably have another introductory repo pinned but currently there's no good candidate.
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
* Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a podcast link there.
* Magnus: Announce podcast episode on LinkedIn.
* Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.
* Magnus: Run through checklist for Azeem.
    * Almost done; the YouTube ownership invite is still pending.
* Mattias: Locate good place to post potential master thesis projects.
* Emil: Send summit placeholder calendar invite as soon as dates have been confirmed.
* Emil/Mattias: Sort out with Ericsson Software Technology whether Nordix can be used for an ArangoDB evaluation.
* Magnus: Comment in [existing PR](https://github.com/eiffel-community/eiffel-event-repository/pull/12) which features that aren't necessary in a minimal ER lookup API spec.

### June 16, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, not present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
* Updates from CDF sig-events, Emil & Mattias
    * CDEventsCon outcome
    * cdCon & CDEvents Contrib Summit outcome
* Follow-up from community meeting about deployment events
    * Minutes posted to [github.com/eiffel-community/eiffel#239](https://github.com/eiffel-community/eiffel/issues/239#issuecomment-1152476287).
* Next community meeting on June 23rd?
    * Decision: Continue deployment event discussion.
* Summer plans for TC
    * Vacations:
        * Emil vacation w28-31
        * Magnus vacation w28-31
        * Azeem vacation w25-30
        * Mattias vacation w25
    * Cancel regular TC meetings on July 14 and 28.
* How to involve new organizations in the community
    * Could they present in a community meeting what they use Eiffel for?
    * Ask if they can present at a community meeting Aug 18 or 25 and we'll adjust the TC meeting schedule based on that.
* Generate diagram with allowed event links?
    * See example from Ericsson
    * Someone in Ericsson has written a set of scripts that generate GraphML files with all event types and their links. Let's look at generating such files automatically once [github.com/eiffel-community/eiffel#282](https://github.com/eiffel-community/eiffel/issues/282) is in place. See also [github.com/eiffel-community/eiffel#281](https://github.com/eiffel-community/eiffel/issues/281).
* Out of time, postponed: ArangoDB PoC
    * Continuation of https://github.com/eiffel-community/eiffel-persistence-technology-evaluation?
    * Follow-up called for Sep 6th 2022
    * To be performed on Nordix?
* Out of time, postponed: Generate HTML pages from our MarkDown files?
    * CDEvents as an example
* Out of time, postponed: Graphite.dev
    * Any good news?
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
* Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a podcast link there.
* ~~Magnus: Is there a LinkedIn post for the podcast episode that we can share with the Eiffel account?~~
    * ~~Apparently not.~~
* ~~Magnus: Announce podcast on mailing list.~~
    * ~~Done.~~
* Magnus: Announce podcast episode on LinkedIn.
* Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.
* ~~Magnus: Add item on https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md to add new TC member as LinkedIn superuser. Also remove billing address item.~~
    * ~~https://github.com/eiffel-community/community/pull/134~~
* ~~Magnus: Add new TC member checklist item for adding Slack ownership and TC Tasks board on GitHub.~~
    * ~~https://github.com/eiffel-community/community/pull/134~~
* Magnus: Run through checklist for Azeem.
    * Almost done; the YouTube ownership invite is still pending.
* ~~Magnus: Contact Ewelina about inviting the TC as owners of the Slack channel.~~
    * ~~2022-06-16: All current TC members are now Slack workspace owners. Magnus is the singular primary owner (the only one who can demote owners).~~
* Mattias: Locate good place to post potential master thesis projects.
* ~~Emil: Move next community meeting from May 27(?) to June 9.~~


### June 2, 2022

Meeting canceled due to too few participants

### May 19, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, present
    * Emil Bäckmark, not present
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
    * Emil attended the SIG events day at KubeCon on May 17.
* Slack channel ownership
    * Action Magnus: Contact Ewelina about inviting the TC as owners.
* [Meetup](https://hackmd.io/@eiffel-community/Hka_ajxf5) recap and follow-up
    * Action Mattias: Locate good place to post potential master thesis projects.
* Next community meeting
    * Action Emil: Move next community meeting from May 27(?) to June 9.
    * Decision: Topic for the meeting is continuing the deployment event discussion.
* PRs and issues

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
* Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a link there.
* Magnus: Is there a LinkedIn post for the podcast episode that we can share with the Eiffel account?
* Magnus: Announce podcast on mailing list.
* Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.
* TC: Add item on https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md to add new TC member as LinkedIn superuser. Also remove billing address item.
* TC: Add new TC member checklist item for adding Slack ownership and TC Tasks board on GitHub.
* Magnus: Run through checklist for Azeem.
    * Almost done; a couple of pending invites that Azeem needs to respond to, and Emil or Daniel needs to add him to the Youtube channel. [PR](https://github.com/eiffel-community/community/pull/133) for GOVERNANCE.md sent.
* Magnus: Contact Ewelina about inviting the TC as owners of the Slack channel.
* Mattias: Locate good place to post potential master thesis projects.
* Emil: Move next community meeting from May 27(?) to June 9.

### May 5, 2022

#### Participants

* TC Attendees
    * Azeem Ahmad, present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved
* Agenda Bashing, All
    * Approved
* Action Item Review, All
* Updates from CDF sig-events, Emil & Mattias
    * Emil to talk about Eiffel at CDEventsCon, as part of KubeCon.
* TC introduction for new members
* Add authorities according to [New TC member checklist](https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md)
    * Action TC: Add new TC member checklist item for adding Slack ownership and TC Tasks board on GitHub.
    * Action Magnus: Run through checklist for Azeem.
* TC co-chair election
    * Decide on meeting or send out for nominations? See [governance process](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-chair-elections-and-voting).
    * Decision: Skip the TC chair election and use the exceptional process where TC itself decides the chairs.
    * Emil and Magnus are both willing to continue as chairs. Nobody opposed these nominations.
    * Decision: Emil and Magnus were elected as chairs.
* [Meetup planning](https://hackmd.io/@eiffel-community/Hka_ajxf5)
* Next community meeting
    * Currently booked at May 26th, but it is public holiday. Cancel or reschedule? June 9th? To be decided on meetup?
    * Decision: Decide during meetup whether to cancel or postpone to June 9th.
* PRs and issues

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
* Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a link there.
* Magnus: Is there a LinkedIn post for the podcast episode that we can share with the Eiffel account?
* Magnus: Announce podcast on mailing list.
* Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.
* TC: Add item on https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md to add new TC member as LinkedIn superuser. Also remove billing address item.
* ~~Emil: Talk to new TC member Azeem about meeting time and make sure he's invited.~~
* TC: Add new TC member checklist item for adding Slack ownership and TC Tasks board on GitHub.
* Magnus: Run through checklist for Azeem.

### April 21, 2022

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
    * [Direktiv](https://github.com/direktiv/direktiv) was presented last week.
* [TC elections](https://hackmd.io/@eiffel-community/H1Oyst_4u)
    * Decide on way forward and document it in a similar way as [was done last year](https://github.com/eiffel-community/community/blob/master/meetings/MEETINGS_BTC.md#April-22-2021)
    * Decision: As per the charter, if there are less than 7 nominees to the TC all candidates are automatically elected. Nominees, and hence future TC members, are:
        * Emil Bäckmark, Ericsson ([nomination](https://groups.google.com/g/eiffel-community/c/uyjewsLYrO8/m/1c6Hn5cRCQAJ))
        * Mattias Linnèr, Ericsson ([nomination](https://groups.google.com/g/eiffel-community/c/uyjewsLYrO8/m/ja3jNKIRCQAJ))
        * Azeem Ahmad, Volvo ([nomination](https://groups.google.com/g/eiffel-community/c/VE0hGRDji1U/m/hT5Xa65PBAAJ))
        * Tobias Persson, Axis ([nomination](https://groups.google.com/g/eiffel-community/c/uyjewsLYrO8/m/jn_gQj9cBAAJ))
        * Magnus Bäck, Axis ([nomination](https://groups.google.com/g/eiffel-community/c/uyjewsLYrO8/m/s0boESXABAAJ))
    * Action Emil: Talk to new TC member Azeem about meeting times and make sure he's invited to future meetings.
* Topic for upcoming April 28 monthly community meeting
    * Cancel due to lack of suitable topics.
* [Meetup planning](https://hackmd.io/@eiffel-community/Hka_ajxf5)
* PRs and issues

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
* Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a link there.
* Magnus: Is there a LinkedIn post for the podcast episode that we can share with the Eiffel account?
* Magnus: Announce podcast on mailing list.
* Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.
* TC: Add item on https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md to add new TC member as LinkedIn superuser. Also remove billing address item.
* Emil: Talk to new TC member Azeem about meeting time and make sure he's invited.

### April 7, 2022

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
    * [Bevy portal](https://www.bevy.com/) being used
* [Meetup planning](https://hackmd.io/@eiffel-community/Hka_ajxf5)
* [TC elections](https://hackmd.io/@eiffel-community/H1Oyst_4u)
* Recap of March 31 monthly community meeting
* Topic for upcoming April 28 monthly community meeting
    * Maybe cancel? No obvious topics and it's two weeks prior to the meetup.
* Planning of the next protocol edition
    * Candidates (added to the [Arica edition milestone](https://github.com/eiffel-community/eiffel/milestone/7)):
        * [Add missing testCase.version member to TERCC event](https://github.com/eiffel-community/eiffel/issues/288): Already merged
        * [How to use CAUSE/CONTEXT in a non-event-driven pipeline](https://github.com/eiffel-community/eiffel/issues/227): Implementation-wise fairly clear but documenting the new link type is difficult. Let's talk about it at the meetup and decide afterwards whether to wait for it.
        * [Add checksum to ArtC's data.fileInformation objects](https://github.com/eiffel-community/eiffel/issues/290): PR remains to be done but should be straight forward.
* Has anybody experience of https://opensource.guide/
    * Looks good but no reason to link to it from our repos.
* Add info about making TC members Super admins on LinkedIn when new TC is elected
    * TC: Create PR for https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md
* PRs and issues

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
* ~~Magnus: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).~~
    * ~~https://github.com/eiffel-community/community/pull/131~~
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* ~~Mattias: Figure out how to deal with Eiffel-adjacent repos not in the eiffel-community organization. Should they be made visible? How? Prepare a proposal on this.~~
    * ~~To handle repositories not part of the Eiffel community e.g. https://plugins.jenkins.io/eiffel-broadcaster/. Create a fork of the repsitory in the Eiffel community.~~
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?
* ~~Magnus: Check within Axis for recommendations on which file types require copyright notices.~~
    * ~~No stated policy. Asked for general guidance in our Teams team for OSS.~~
    * ~~Discussed on TC meeting. No further action at this point. If we see files in PRs without copyright notices it's fine to comment on it but let's not spend more time on it here.~~
* Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a link there.
* Magnus: Is there a LinkedIn post for the podcast episode that we can share with the Eiffel account?
* Magnus: Announce podcast on mailing list.
* Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.
* TC: Add item on https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md to add new TC member as LinkedIn superuser. Also remove billing address item.

### March 24, 2022

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
    * Many upcoming conferences where CDEvents will be a topic.
* Meetup planning
    * https://hackmd.io/wG7lMI0DQhex-c8o6t-3Rg
    * Virtual or physical only?
        * Primarily physical, but we're open to making accommodations for remote participation.
        * Mattias/Emil: Talk to potentially interested Ericsson folks about the agenda to gauge interest.
        * Tobias: Add 1-2 sentences about each agenda item.
        * Mattias: Prepare poll with agenda items and remote/physical preferences.
        * Emil: Announce on March 30
    * Agenda updates?
    * Promote the meetup to the community
        * eiffel-community mailing list
        * Slack
        * LinkedIn
* TC elections - https://hackmd.io/@eiffel-community/H1Oyst_4u
    * Present 2022 Eiffel TC eligible community members list to Eiffel TC
        * No exemption requests so list is complete.
    * Plan to send out nomination mail to community on March 30th
* Monthly meetup March 31st
    * Emil: Update meeting invite
* Where should we add the link to the Python.\_\_init\_\_ podcast?
    * Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a link there.
    * Magnus: Is there a LinkedIn post for the podcast episode that we can share with the Eiffel account?
    * Magnus: Announce on mailing list.
* Should we add the TC mailing list to any of our documents? It's only visible in the summit call.
    * Yes, add email address in the same place where the TC members are listed. There's an existing action to add the addresses of the TC members and we can add the list address there too.
* Fork external repos into eiffel-community?
    * No forks.
    * Mattias: Promote in landscape picture and link to it from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.
* Planning of the next protocol edition
* Has anybody experience of https://opensource.guide/
* Add info about making TC members Super admins on LinkedIn when new TC is elected
* PRs and issues

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
* Magnus: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Mattias: Figure out how to deal with Eiffel-adjacent repos not in the eiffel-community organization. Should they be made visible? How? Prepare a proposal on this.
    * To handle repositories not part of the Eiffel community e.g. https://plugins.jenkins.io/eiffel-broadcaster/. Create a fork of the repsitory in the Eiffel community.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* ~~Mattias: Create proposal for event type categorization.~~
    * ~~Draft PR: https://github.com/eiffel-community/eiffel/pull/297~~
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* ~~Emil: Confirm with Henning, Daniel, and Kristofer that it's okay to remove them as GitHub organization owners.~~
* Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?
* Magnus: Check within Axis for recommendations on which file types require copyright notices.
* ~~TC: Propose good dates for the May meetup.~~
    * ~~(Mattias) First meeting for the new TC is May 5th. Do we want to meet in person then?~~
* ~~Mattias: Send email to mailing list and ask for topic proposals.~~
    * ~~https://groups.google.com/g/eiffel-community/c/zqvCgHjhiO4~~
* Magnus: Convert "Watch the videos" section on https://eiffel-community.github.io/ to "Media" (or similar) and add a link there.
* Magnus: Is there a LinkedIn post for the podcast episode that we can share with the Eiffel account?
* Magnus: Announce podcast on mailing list.
* Mattias: Promote external repos in landscape picture and link to them from https://github.com/eiffel-community. Convert landscape picture to SVG so that we can add clickable links.

### March 10, 2022

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
* Should we grant access to the eiffel-community organization to graphite.dev? (Tobias)
    * Yes.
* Community meeting follow up and plan for next (March 31st)
    * Event Repository evolution? Interesting but requires a lot of preparations.
    * Possibly .NET SDK demo?
    * Protocol workshop and planning of upcoming editions?
    * Action Mattias: Send email to mailing list and ask for topic proposals.
    * Final decision on next week's meeting.
* Fatih will talk about the coming elections (joining at 13:30)
    * [TC election plan](https://hackmd.io/@eiffel-community/H1Oyst_4u) presented and approved.
* Out of time, postponed: Should we add the TC mailing list to any of our documents? It's only visible in the summit call.
* Out of time, postponed: Where should we add the link to the Python.\_\_init\_\_ podcast? Mattias
* Postponed to next week's meeting: May meeting planning
* Out of time, postponed: Fork external repos into eiffel-community?
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
* TC: Write issue about describing process for archiving projects and do archive eiffel-remrem-shared
    * remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30 (library not actually used but there are still references to it)
    * https://github.com/eiffel-community/community/blob/master/PROJECT_LIFECYCLE.md#stage-archived
* TC: Add all TC members to all existing Eiffel Google groups
* Magnus: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Mattias: Figure out how to deal with Eiffel-adjacent repos not in the eiffel-community organization. Should they be made visible? How? Prepare a proposal on this.
    * To handle repositories not part of the Eiffel community e.g. https://plugins.jenkins.io/eiffel-broadcaster/. Create a fork of the repsitory in the Eiffel community.
* ~~Fatih: Update timeline based on discussion (move elegible candidate earlier and take Easter into account) and get back to TC via mail for final confirmation.~~
* ~~Fatih: Locate script for finding eligible candidates and create PR in the community repo.~~
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Mattias: Create proposal for event type categorization.
    * Draft PR: https://github.com/eiffel-community/eiffel/pull/297
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil: Confirm with Henning, Daniel, and Kristofer that it's okay to remove them as GitHub organization owners.
* Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?
* Magnus: Check within Axis for recommendations on which file types require copyright notices.
* TC: Propose good dates for the May meetup.
    * (Mattias) First meeting for the new TC is May 5th. Do we want to meet in person then?
* ~~TC: Sort out the exact quorum requirements.~~
* Mattias: Send email to mailing list and ask for topic proposals.
    * https://groups.google.com/g/eiffel-community/c/zqvCgHjhiO4

### February 24, 2022

#### Participants

* TC Attendees
    * Emil Bäckmark, not present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, not present

#### Agenda and Notes
* Rollcall, All
    * 50% presence, quorum situation somewhat unclear. Assuming no quorum.
    * TC: Sort out the exact requirements.
* Approval of Previous Minutes, All
    * No quorum, skipping.
* Agenda Bashing, All
    * Approved after postponing "May meeting planning" and "Planning of the next protocol edition" to the next meeting.
* Action Item Review, All
* Updates from CDF sig-events, Emil & Mattias
    * Work on defining event fundamentals and possible link between events is ongoing.
* Show and explain the current status of misalignment with REMReM. [REMReM semantics pom.xml](https://github.com/eiffel-community/eiffel-remrem-semantics/blob/2.1.1/pom.xml)
    * eiffel-remrem-semantics v2.1.1 has 2.2.0 in pom.xml, resulting in incorrectly versioned artifacts when building from the v2.1.1 commit. The v2.1.1 unintentionally contains the Paris edition commit that was intended for v2.2.0.
* PRs and issues

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
* ~~Tobias: Amend the repo creation checklist in the eiffel-repository-template repo to state that TC members should be added as owners to any created Google Groups.~~
    * ~~https://github.com/eiffel-community/eiffel-repository-template/pull/17~~
* Magnus: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* TC: Look into proposal made in the maintainer role presentation from the summit.
* Emil/Mattias: Make sure questions from the CDF summit presentation are taken care of in SIG Events.
    * This can be transformed into an issue
* Mattias: Figure out how to deal with Eiffel-adjacent repos not in the eiffel-community organization. Should they be made visible? How? Prepare a proposal on this.
    * To handle repositories not part of the Eiffel community e.g. https://plugins.jenkins.io/eiffel-broadcaster/. Create a fork of the repsitory in the Eiffel community.
* ~~Magnus: Create issues in all repos with .travisci.yml files to have them change to GitHub Actions.~~
    * ~~Done, track via the new [Migration from Travis CI to GitHub Actions](https://github.com/orgs/eiffel-community/projects/4/views/4?layout=board) project.~~
* ~~Tobias: Add an organization README file ([docs](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)).~~
    * ~~https://github.com/eiffel-community/.github/pull/16~~
* Fatih: Update timeline based on discussion (move elegible candidate earlier and take Easter into account) and get back to TC via mail for final confirmation.
* Fatih: Locate script for finding eligible candidates and create PR in the community repo.
* Magnus: Collect feedback from the interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Mattias: Create proposal for event type categorization.
* ~~Magnus: Can discussion items be added to a GitHub project (along with PRs and issues)?~~
    * ~~No, discussion threads can have labels but can't be connected to projects.~~
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil: Confirm with Henning, Daniel, and Kristofer that it's okay to remove them as GitHub organization owners.
* Magnus: Could policies like "repo maintainers should also be watchers" be enforced with e.g. [github.com/github/safe-settings](https://github.com/github/safe-settings) or [github.com/probot/settings](https://github.com/probot/settings)?
* ~~Tobias: Move SECURITY.md from the community repo to the .github repo.~~
    * ~~[github.com/eiffel-community/community#128](https://github.com/eiffel-community/community/pull/128)~~
    * ~~[github.com/eiffel-community/.github#15](https://github.com/eiffel-community/.github/pull/15)~~
* ~~Mattias: Check Ericsson email thread about which file types require copyright notices.~~
    * >Hi Mattias,
      > 
      >Think it very much is up to each and every open source project to decide. However if you have many different individuals/companies doing contributions the files soon become cluttered with copyright statements so one might wan to find other solutions. This blog from LF touches on the subject; https://www.linuxfoundation.org/en/blog/copyright-notices-in-open-source-software-projects/ 
      >
      >The readme file does not need a copyright statement as I see it. The indication of license should suffice.
* Magnus: Check within Axis for recommendations on which file types require copyright notices.
* TC: Propose good dates for the May meetup.
* TC: Sort out the exact quorum requirements.

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
