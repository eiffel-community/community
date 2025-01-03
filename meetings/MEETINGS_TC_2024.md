###### tags: `Technical Committee`

# Technical Committee Meetings 2024

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2024-12-12 Meeting](#December-12-2024)
    * [2024-11-28 Meeting](#November-28-2024)
    * [2024-11-14 Meeting](#November-14-2024)
    * [2024-10-17 Meeting](#October-17-2024)
    * [2024-10-02 Meeting](#October-2-2024)
    * [2024-09-12 Meeting](#September-12-2024)
    * [2024-08-22 Meeting](#August-22-2024)
    * [2024-08-08 Meeting](#August-8-2024)
    * [2024-06-27 Meeting](#June-27-2024)
    * [2024-05-30 Meeting](#May-30-2024)
    * [2024-05-02 Meeting](#May-2-2024)
    * [2024-04-18 Meeting](#April-18-2024)
    * [2024-04-04 Meeting](#April-4-2024)
    * [2024-03-27 Meeting](#March-27-2024)
    * [2024-03-07 Meeting](#March-7-2024)
    * [2024-02-22 Meeting](#February-22-2024)
    * [2024-02-08 Meeting](#February-8-2024)
    * [2024-02-01 Meeting](#February-1-2024)
    * [2024-01-25 Meeting](#January-25-2024)
    * [2024-01-18 Meeting](#January-18-2024)
    * [2024-01-11 Meeting](#January-11-2024)


## Logistics

* **When:** 13:00–14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_OTc1NDIzNTUtYzJiMy00OThiLTkwZDUtYTdkODVhOGNjYzI3%40thread.v2/0?context=%7b%22Tid%22%3a%2292e84ceb-fbfd-47ab-be52-080c6b87953f%22%2c%22Oid%22%3a%2249725723-aa8c-4dcf-b9d0-b974e8a25702%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/NMYEAe3oSnucIP-V9LAkwA) in order to prevent notes getting out of sync.

### December 12, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
    * Approved.
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
* VCC and Eiffel
    * Action Mattias: Check in with Erik Sternersson.
* Archival of Slack discussions
    * As per last meeting: "Slack and the mailing list are enough, we don't need another medium in the form of GitHub Discussions.". Dropping the initiative.
    * Info: Our old data will be removed 28th of January
* Follow up security officers email
    * Ping them again for a response.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.

### November 28, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
    * Approved.
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * A few new people have showed up in #otel-cicd in the CNCF Slack just in the past few days. 
* Next community meeting December 5
    * [Support modeling activities that finish without doing anything #406](https://github.com/eiffel-community/eiffel/issues/406)
  * [Artifacts with multiple names](https://github.com/eiffel-community/eiffel/issues/405) (continue discussion from 2024-11-07 meeting)
  * Initial discussions about including SBOMs and build attestations in the Eiffel graph
* Christmas schedule
    * Dec 26 TC meeting will obviously not take place, otherwise no meetings will be canceled.
* Archival of Slack discussions
    * Have exported all Slack discussions via  [Add archive of all public Slack conversations](https://github.com/eiffel-community/community/pull/206)
        * You could use https://github.com/4350pChris/slack-vuesualizer to then show them
        * We should anonymize the data before we publish it. Perhaps it's enough to not include users.json and drop the user_profile key?
    * Propose to enables discussion on our repos and send the following via Slack and Community List
    >   As Slack will remove the older conversations as per [Updates to message and file history on free workspaces](https://slack.com/intl/en-gb/help/articles/29414264463635-Updates-to-message-and-file-history-on-free-workspaces) we in the TC would like us to move questions and discussion to GitHub. This as we have hit the 90 days limit on discussions we wanted to revisit.
    > 
    > To preserve older discussion we have created [Add archive of all public Slack conversations](https://github.com/eiffel-community/community/pull/206) but it requires us to periodically archive discussion. We feel that using the discussions on GitHub serves the community better.

    * Slack and the mailing list are enough, we don't need another medium in the form of GitHub Discussions.
* How much on "Next" still have relevance?
    * Will be kept for now.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Magnus: How can we model activities that are started but complete early because they determine nothing needs to be done (Slack thread)?~~
    * ~~[Support modeling activities that finish without doing anything #406](https://github.com/eiffel-community/eiffel/issues/406)~~


### November 14, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
    * Approved.
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * Nothing in particular.
* Next community meeting December 5
    * Protocol workshop with the following topics:
        * [Artifacts with multiple names](https://github.com/eiffel-community/eiffel/issues/405)
        * Initial discussions about including SBOMs and build attestations in the Eiffel graph
* CDEvents discussions
    * CDEvents is looking for a modeling language for its schemas https://github.com/cdevents/implementation-wg/issues/5
    * CDEvents is setting up requirements for a message service https://github.com/cdevents/implementation-wg/pull/4
* How can we model activities that are started but complete early because they determine nothing needs to be done ([Slack thread](https://eiffel-workspace.slack.com/archives/CQD817AHY/p1716547052821279))?
    * Action Magnus: Write an issue for this.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Mattias: Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.~~
    * ~~2024-10-17: Not entirely clear what needs to be done here. Follow up and update the action description.~~
    * ~~2024-11-14: Still unclear. Closing for now.~~
* ~~Magnus: File an issue about modeling activities that start and finish early.~~
    * ~~2024-11-15: https://github.com/eiffel-community/eiffel/issues/406~~

### October 17, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, not present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
    * Approved.
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
* Community meetings
    * Next meeting the 7th of Nov.
    * Action Mattias: Check with Volvo if they want to demo their Neo4j implementation.
* How does one contact community members?
* Why do we have sepia on the gh-pages branch but use the master branch for eiffel-community.github.io?
    * No obvious reason. Draft issue created to address this.
* Should the mandatory Eiffel edition field at the bottom of the issue template be optional ([Slack thread](https://eiffel-workspace.slack.com/archives/CQD817AHY/p1723624074046039))?
    * Yes, draft issue created.
* Curation of potential topics for [future community meetings](https://hackmd.io/mew2t6NqSBe7aRkzQkWNqg).
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.
    * 2024-10-17: Not entirely clear what needs to be done here. Follow up and update the action description.
* ~~Magnus: Invite Volvo to a follow-up meeting when they're ready. Include pointer to the community meeting in the email.~~
    * ~~2024-10-04: Done.~~
* ~~Mattias: Check with Volvo if they want to demo their Neo4j implementation.~~

### October 2, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents (Emil)
    * There was a mini summit at Open Source Summit, including an introduction by Andrea Fritolli and a presentation from Ericsson Software Technology about using CDEvents to integrate Flux with other software.
    * Emil won't follow CDEvents very closely going forward.
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * [OTEP 258](https://github.com/open-telemetry/oteps/pull/258), covering trace context propagation via environment variables, should be merged soon.
* Community meetings
    * Action Emil: Send update to next week's community meeting. The topic will be following up on summit topics.
    * Action Magnus: In the follow-up email to Volvo (existing action), include pointer to the community meeting.
    * Volvo has been experimenting with Neo4j. That would be an interesting topic.
* Summit feedback
    * After a reminder last week we've received a few additional responses. Nothing to take immediate action on but we updated the [summit takeaways](https://hackmd.io/@eiffel-community/H17vikIj0) document.
* YouTube videos: Do we need to get explicit permission from all speakers before publishing on the summit page.
    * No, that shouldn't be necessary.
* ActT discussion from Slack
* Out of time, postponed: PRs and issues

#### Action Items
* ~~Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.~~
    * ~~2024-10-02: No longer relevant. We don't have any problems with maintainership right now and it's unclear what this action item even entails.~~
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.
* ~~Mattias: Send a follow-up email to the new summit participants during October.~~
    * ~~2024-10-02: Done.~~
* ~~Magnus: Update summit.html to state that the summit is over.~~
    * ~~2024-10-01: Done.~~
* ~~Magnus: Invite Volvo to a follow-up meeting when they're ready. Include pointer to the community meeting in the email.~~
    * ~~2024-10-04: Done.~~
* ~~Emil: Send update to next week's community meeting. The topic will be following up on summit topics. Also, post to old Slack threads.~~
    * ~~2024-10-02: Done.~~

### September 12, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Emil's Eiffel participation
    * Emil's participation in the community will ramp down. He will remain in the TC and as TC chair but will not prioritize Eiffel meetings.
* Summit follow-up
    * [Summit Takeaways](https://hackmd.io/IOIGKpdcRh2FZVCn3AMO8A) 
    * Did anyone take notes?
        * No, but it's not clear that there was anything noteworthy.
    * How to follow up with new participants?
        * Action Mattias: Send a follow-up email to the new summit participants during October.
    * Write a post on LinkedIn?
        * Yes, let's make a post when the video and slides are available on the community site.
    * Update [summit page](https://eiffel-community.github.io/summit.html)
        * Action Magnus: Update summit.html to state that the summit is over.

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.
* Mattias: Send a follow-up email to the new summit participants during October.
* Magnus: Update summit.html to state that the summit is over.
* Magnus: Invite Volvo to a follow-up meeting when they're ready.

### August 22, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents (Emil)
    * Ericsson Software Technologies staff will no longer work with CDEvents.
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * Recurring meetings in the CI/CD SIG will soon start.
* [Next Eiffel edition](https://github.com/eiffel-community/eiffel/milestone/9)
* Summit
    * Will Edvin own and drive the agenda?
    * Does the venue include breakout rooms? Say, if lots of people drop out on day 2 and we don't feel we need a room for 70 people.
    * Note taker?
    * Sessions that we need to prepare:
        * Eiffel for beginners
        * Effective collaboration strategies among diverse groups
            * Check what the moderator knows about Eiffel.
            * Try to prepare questions.
            * Who will participate?
        * Filtering and Scaling of Eiffel
            * Explain routing keys (Magnus)
            * Explain domain and general infrastructure (Magnus + Emil/Mattias)
            * Pitfalls of ER dependencies when consuming events (Magnus)
        * Contributing to the Eiffel open source community (Emil)
        * What's new in Santiago (Magnus)
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.

### August 8, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG, Magnus
    * OTel semconv v1.27.0 includes the CI/CD attributes from  [github.com/open-telemetry/semantic-conventions#1075](https://github.com/open-telemetry/semantic-conventions/pull/1075).
    * During the work on said PR, several things popped up and were deemed out of scope. See https://github.com/orgs/open-telemetry/projects/79/views/1.
* Summit
    * Meeting with Volvo next Monday.
    * Feedback from last summit: https://hackmd.io/6v4hYbmMRPSk2OHz3dIT-g
    * Announce the Eiffel Summit on LinkedIn?
        * Yes, post it as a LinkedIn event.
* Eiffel Community meeting Aug 29?
    * Shift weeks since Mattias's vacations collide several times during autumn?
        * Swap dates for the extra TC meeting and community meetings, i.e. community meetings take place on Oct&nbsp;10, Nov&nbsp;7, and Dec&nbsp;5.
    * Action Emil: Replace Aug 29 community meeting with a summit preparation meeting and adjust community meeting invites.
* [Next Eiffel edition](https://github.com/eiffel-community/eiffel/milestone/9)
    * Aim for a Sep&nbsp;30 release of the Santiago edition. Four issues currently remain, whereof one (new source tag event) probably needs to be descoped.
* PRs and issues
    * A few of Mattias's open PRs were discussed.

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Emil: Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.
* ~~Magnus: Publish info on mailing list about elected TC Chairs.~~
* ~~Magnus: See if there's a possibility to get a free Slack ride since Eiffel is an open source project.~~
    * ~~Update 2023-08-08: AFAICT there's no FOSS waiver. The CNCF appears to be paying for a Pro plan. We won't do that.~~
* ~~Emil: Replace Aug 29 community meeting with a summit preparation meeting and adjust community meeting invites.~~

### June 27, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, not present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG, Magnus
    * The two PRs for CI/CD attributes and environment variable based context propagation or still open an awaiting reviews.
        * [github.com/open-telemetry/semantic-conventions#1075](https://github.com/open-telemetry/semantic-conventions/pull/1075)
        * [github.com/open-telemetry/oteps#258](https://github.com/open-telemetry/oteps/pull/258)
* Security Officer appointments
    * Fredrik Fristedt and Kristofer Hallén were appointed security officers for a term that ends 2025-06-30.
* Summit
    * Meeting with Volvo tomorrow.
    * Meeting between Axis and Ericsson next week to talk about the agenda for the introduction session.
* New message retention policy for the free tier of Slack.
    * Action Magnus: See if there's a possibility to get a free ride since Eiffel is an open source project.
* Eiffel maintainer need to enable security alerts in each repo they maintain. E.g. you can turn them off in a repo you are maintainer of.
    * Added a comment to https://github.com/eiffel-community/community/issues/153.
* PRs and issues
    * Talked about https://github.com/eiffel-community/community/issues/200. Conclusion was to denote the difference between repos using text rather than a new icon.

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Magnus: Ask current security officers if they want to continue.~~
    * ~~Update 2024-05-30: Both have been asked and Fredrik has accepted.~~
    * ~~Update 2024-06-27: Kristofer has also accepted.~~
* Emil: Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.
* Magnus: Publish info on mailing list about elected TC Chairs.
* ~~Magnus: Prepare summit sign-up form based on last year's.~~
* Magnus: See if there's a possibility to get a free Slack ride since Eiffel is an open source project.

### May 30, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
    * SDK updates for 0.4.0 and 0.4.1 ongoing.
    * Link support in SDKs being discussed. Perhaps only embedded links?
    * Ongoing work to get [Flux](https://fluxcd.io) to send CDEvents.
* Updates from OpenTelemetry CI/CD WG, Magnus
    * Adriel Perkins has opened two PRs for CI/CD attributes and environment variable based context propagation.
        * [github.com/open-telemetry/semantic-conventions#1075](https://github.com/open-telemetry/semantic-conventions/pull/1075)
        * [github.com/open-telemetry/oteps#258](https://github.com/open-telemetry/oteps/pull/258)
* Follow-up of May 16 community meeting
    * The presentation was interesting but there's nothing to follow up.
* Next community meeting
    * No obvious topic. Cancel?
    * Yes. Also, July 4 and August 8 meeting are canceled because of vacations.
* Security Officers elections
    * We haven't received answers from both existing officers so we postpone the appointment.
* Summit
    * Action Magnus: Prepare sign-up form based on last year's.
    * Action Emil: Send w27 invite to discuss the introduction session at the summit. Include Kristofer.
* Out of time, postponed: Gap analysis - CDEvents vs Eiffel. To help CDEvents reach 1.0 we should provide our input on the gap
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Magnus: Ask current security officers if they want to continue.
    * Update 2024-05-30: Both have been asked and Fredrik has accepted.
* ~~Magnus: Update GH pages summit page.~~
* ~~Emil: Add public key distribution recording to YouTube and post it on the mailing list.~~
* Emil: Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.
* Magnus: Publish info on mailing list about elected TC Chairs.
* Magnus: Prepare summit sign-up form based on last year's.
* ~~Emil: Send w27 invite to discuss the introduction session at the summit. Include Kristofer.~~

### May 2, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Next community meeting
    * The May 16 meeting will cover Volvo Cars's event protocol, hosted by Erik Sternersson.
* Updates from CDEvents, Emil
    * CDEvents interest shown at cdCon, e.g. Screwdriver
    * Jenkins plugin/core support discussed
* Updates from OpenTelemetry CI/CD WG, Magnus
    * Mostly talks about semantic convention. Not about sending the information.
* [TC Elections update](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Celebrate the forming of the new TC
    * Appoint TC Chair
        * Emil and Magnus elected on the meeting
    * (Magnus) Publish info about elected TC Chairs
    * (Emil) Update info on web pages / GitHub, according to [post-election checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md). There is mis-alignment on when/how election officers are elected between Governance doc and Election HackMD doc.
* Security Officers elections
    * (Magnus) Ask current SOs if they can stay. If not we need to discuss replacement offline.
* Summit
    * Action Emil: After getting confirmation in the summit slack, send preliminary calender invite for the summit.
    * Action Magnus: Update GH pages summit page.
* Follow-up of April 25 community meeting
    * Good discussions but no actions to take.
    * Action Emil: Add public key distribution recording to YouTube and post it on the mailing list.
* Out of time, postponed: Gap analysis - CDEvents vs Eiffel. To help CDEvents reach 1.0 we should provide our input on the gap
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Emil: Update agenda for May 16 community meeting.~~
* ~~Emil: Talk to election officers about the next steps.~~
* Magnus: Ask current security officers if they want to continue.
* ~~Emil: After getting confirmation in the summit slack, send preliminary calender invite for the summit.~~
* Magnus: Update GH pages summit page.
* Emil: Add public key distribution recording to YouTube and post it on the mailing list.

### April 18, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
    * [CDEvents v0.4 was announced](https://cd.foundation/blog/2024/04/16/cdevents-v04/)
* Updates from OpenTelemetry CI/CD WG, Magnus
    * Adriel has posted a proposal at [github.com/open-telemetry/semantic-conventions#915](https://github.com/open-telemetry/semantic-conventions/issues/915).
* [TC Elections update](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Action Emil: Talk to election officers about the next steps.
* Summit
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Magnus: Prepare agenda for April 25 meeting.~~
* Emil: Talk to election officers about the next steps.

### April 4, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, not present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* TC Elections update
    * Request for nominations sent out (one day too late)
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
    * CDEvents v0.4 about to be released in conjunction with cdCon.
* Updates from OpenTelemetry CI/CD WG, Magnus
* Next Eiffel Community meetings
    * Postpone April 11 meeting until April 25
* Should we document whether to send events from separate services or from within the services where things actually happen (CDEvents-translator case)?
    * This should probably be documented, but it's hard to give concrete guidelines. Ideally, events should be sent as close to the source as possible, except when that isn't possible. We have more pressing documentation tasks, so no action is planned at this time.
* Follow up outcome of meeting about [github.com/eiffel-community/eiffel-intelligence#534](https://github.com/eiffel-community/eiffel-intelligence/issues/534).
    * Nasdaq will attempt to recreate the performance problems in a Nordix environment. That way Ericsson folks can easier help out with the debugging.
* Have we tried /template on issues since we changed the template? https://github.com/orgs/community/discussions/14010#discussioncomment-8416778
    * Apparently this only works for issues (i.e. not draft issues since they aren't tied to a repository) in repositories with old-school template, not the new form-based ones. This means that it currently doesn't work for the protocol repo. Being able to insert a template with `/template` would've been nice, but we prefer using the new form-based templates.
* PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Magnus: Prepare agenda for April 25 meeting.
* ~~Emil: Update invite for April 11->25 meeting.~~


### March 27, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, not present
* Others
    * Fatih Degirmenci, not present
    * Fredrik Fristedt, present for TC elections item

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* TC Elections update
    * The list of eligible candidates was announced a bit too late, but we found that it didn't warrant any particular action.
    * No exception requests have been filed so the announced candidate list is final.
    * We had a discussion about archived projects and that maintainers of such shouldn't be eligible. Draft issue to update GOVERNANCE.md has been created.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Future Eiffel Community meetings
    * Magnus, the planned moderator of the _Public key distribution for event signing using meta.security_ community meeting planned for April 11, can't make it that day. Push it to the May meeting? Or move April community meeting to 25th?
    * Yes, postpone April 11 meeting until April 25. May meeting still stands but we may end up canceling it if we don't find a topic.
    * Action Magnus: Prepare agenda for April 11 meeting.
    * Action Emil: Update invite for April 11 meeting.
* Follow-up the OTel discussion. Are there any further actions we can take at this point?
    * No immediate actions to take, but we look forward to the CI/CD WG within OTel.
    * Axis is doing some work in this area and may be able to provide input to the ongoing OTel efforts related to context and baggage propagation in the CI/CD context.
* Should we have a possibility to identify a testcase from an issue? E.g. if a test fail and we write a ticket on it should we in the ID event link to the Testcase?
    * This is a valid use case and the target of such a link could not only be a TCT but also e.g. an SCS. Would a link type for this be better than simply having a CAUSE link to the failing TCF?
    * Draft issue created.
* Should we document whether to send events from separate services or from within the services where things actually happen (CDEvents-translator case)?
* Follow up outcome of meeting about [github.com/eiffel-community/eiffel-intelligence#534](https://github.com/eiffel-community/eiffel-intelligence/issues/534).
* PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Magnus: Prepare agenda for April 11 meeting.
* Emil: Update invite for April 11 meeting.

### March 7, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Future Eiffel Community meetings
    * _Public key distribution for event signing using meta.security_ is a good candidate. Is it too late to talk about this on March 14?
    * Yes, cancel the March 14 community meeting and aim to talk about public keys on April 11 instead.
    * We can probably have a talk about Volvo Cars' event protocol on May 16 (or possibly May 2).
* Eiffel summit
    * We had a meeting with Volvo Group on March 5 and they have agreed to host a summit in Gothenburg in late September or early October. We'll start working on the agenda in about a month. Magnus and Emil will be the main drivers from the TC.
* How do we note compliance against protocol versions and API (for example minimal ER API) amongst the community repos?
    * From prior meeting: Yes, this would be a good thing. However, the implementation is unclear. The information is probably too rich to fit in a single badge in the readme files. Perhaps a table that describes which events from which editions are consumed and produced?
    * Let's start with badges for the ER version. The ER spec has the wrong version and the eiffel-event-repository git hasn't been tagged. Draft issue for this created, and another one for getting the badges in place.
* https://github.com/eiffel-community/eiffel/issues/374 - should this say an machine readable YAML file?
    * From prior meeting: The information already is machine readable, albeit in the original YAML files and therefore not super convenient to access.
    * Let's generate a machine readable file. Issue has been updated accordingly.
* Out of time, postponed: Should we have a possibility to identify a testcase from an issue? E.g. if a test fail and we write a ticket on it should we in the ID event link to the Testcase?
* Out of time, postponed: Should we document whether to send events from separate services or from within the services where things actually happen (CDEvents-translator case)?
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.

### February 22, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, not present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Eiffel Community meeting 14th of March
    * _Public key distribution for event signing using meta.security_ is a good candidate. Let's follow up next week and decide.
* How should we handle issues like this https://github.com/eiffel-community/eiffel-intelligence/issues/534 when we can't reproduce it?
    * Totally fine to close an issue if the problem can't be reproduced. Use good judgment.
* How do we note compliance against protocol versions and API (for example minimal ER API) amongst the community repos?
    * Yes, this would be a good thing. However, the implementation is unclear. The information is probably too rich to fit in a single badge in the readme files. Perhaps a table that describes which events from which editions are consumed and produced?
* https://github.com/eiffel-community/eiffel/issues/374 - should this say an machine readable YAML file?
    * The information already is machine readable, albeit in the original YAML files and therefore not super convenient to access.
* Should we have a possibility to identify a testcase from an issue? E.g. if a test fail and we write a ticket on it should we in the ID event link to the Testcase?
    * Discussion held, no conclusions. Follow up when Emil is back.
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Mattias: Draft text of email to maintainers re archival.~~
    * ~~**Update:** Proposal~~
    >Hi maintainers!
    >
    >We would like to make you aware we have created a ticket in your repository https://github.com/eiffel-community/eiffel-store/issues/10 on archiving it. Please use this ticket for further communication on this topic.
    >
    >Best Regards,  
    >Eiffel Technical Committee
    * ~~Update 2024-02-22: This email text looks fine.~~
* ~~Mattias: Update the eiffel-easy2use configuration to require approvals from outside contributions and update these minutes to state exactly what setting was changed.~~
    * ~~**Update**: Under `Actions->General->Fork pull request workflows from outside collaborators` set it to *Require approval for all outside collaborators*~~

### February 8, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Fredrik Fristedt, present (up to and including _Self-hosted GitHub runners_ agenda item)

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* [TC elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Proposed timeline was approved.
* Self-hosted GitHub runners
    * https://www.securityweek.com/major-it-crypto-firms-exposed-to-supply-chain-compromise-via-new-class-of-ci-cd-attack/ 
    > To mitigate this class of vulnerability, organizations are advised to change the default repository settings so that all outside contributions require approval.
    * Decision: All repos should be configured to require approval of all outside contributions before workflows are run.
    * Action Magnus: Update [github.com/eiffel-community/community#151](https://github.com/eiffel-community/community/issues/151) with the requirement that outside contributions require approval before any workflows are run.
    * Action Mattias: Update the eiffel-easy2use configuration and update these minutes to state what was changed.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Coming Absence in TC
    * Emil is off w8 (Feb 22)
    * Mattias is off w9? (Feb 29)
    * Meetings will be held with reduced presence.
* Updates from CDEvents, Emil
    * "[CDEvents Translator](https://github.com/cdevents/community/pull/42)" proposed. Mainly for transforming SCM 'events' to CDEvents.
* Eiffel Summit 2024: Where and when?
    * Volvo wants to host a summit this year. Planning meeting to be scheduled by Volvo.
* Open source tool for inserting events to MongoDB?
    * Magnus will look into open sourcing Axis's MongoDB inserter.
* PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Magnus: Write an agenda for the OTel meeting.~~
* Mattias: Draft text of email to maintainers re archival.
    * **Update:** Proposal
    >Hi maintainers!
    >
    >We would like to make you aware we have created a ticket in your repository https://github.com/eiffel-community/eiffel-store/issues/10 on archiving it. Please use this ticket for further communication on this topic.
    >
    >Best Regards,  
    >Eiffel Technical Committee
* ~~Magnus: Update [github.com/eiffel-community/community#151](https://github.com/eiffel-community/community/issues/151) with the requirement that outside contributions require approval before any workflows are run.~~
* Mattias: Update the eiffel-easy2use configuration to require approvals from outside contributions and update these minutes to state exactly what setting was changed.
    * **Update**: Under `Actions->General->Fork pull request workflows from outside collaborators` set it to *Require approval for all outside collaborators*

### February 1, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
    * Ticket events are being discussed; creation, closure, and updates of tickets. See [github.com/cdevents/spec#180](https://github.com/cdevents/spec/pull/180).
* Should we propose to add event triggered updates to Renovate?
    * Note: Renovate has support for Gerrit now: https://github.com/renovatebot/renovate/releases/tag/37.112.0
    * Similar issue in CDEvents: https://github.com/cdevents/spec/issues/39
    * No action for now.
* Archiving stale repositories
    * We'll create an issue in each repository that we think should be archived and ask the ostensible maintainers to complain if they want the repository to remain in an active state. See [github.com/eiffel-community/eiffel-store#10](https://github.com/eiffel-community/eiffel-store/issues/10) for an example.
    * Candidates for archival:
        * eiffel-gerrit-lib
        * eiffel-gerrit-herald
        * eiffel-jenkins-plugin
        * eiffelactory
        * eiffel-persistence-technology-evaluation
        * ml-jmespath-generator
        * eiffel-vici
        * eiffel-jira-plugin
    * Decision: TC will take over eiffel-playground and turn it into a community repo.
* Out of time, postponed: Self-hosted GitHub runners
    * https://www.securityweek.com/major-it-crypto-firms-exposed-to-supply-chain-compromise-via-new-class-of-ci-cd-attack/  
    > To mitigate this class of vulnerability, organizations are advised to change the default repository settings so that all outside contributions require approval.
* Out of time, postponed: Open source tool for inserting events to MongoDB?
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Emil: Send existing Volvo contacts an email and ask about a summit.~~
* Magnus: Write an agenda for the OTel meeting.
* Mattias: Draft text of email to maintainers re archival.

### January 25, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
* Eiffel Summit 2024: Where and when?
    * There are two windows of opportunity: late April or early May or during the fall, e.g. early September.
    * Let's ask Volvo Trucks if they're interested in hosting a one or two day summit.
    * Action Emil: Send existing Volvo contacts an email and ask about a summit.
* Community meeting Feb 15
    * Decision: OpenTelemetry and Eiffel, hosted by Magnus.
    * Action Magnus: Write an agenda for the OTel meeting.
* Should we archive all repos that don't have active maintainers?
    * Yes. Suggestion to send email to maintainers and check if they still consider themselves maintainers.
    * Action Mattias: Draft text of email to maintainers re archival
* Out of time, postponed: Should we propose to add event triggered updates to Renovate?
    * Note: Renovate has support for Gerrit now: https://github.com/renovatebot/renovate/releases/tag/37.112.0
    * Similar issue in CDEvents: https://github.com/cdevents/spec/issues/39
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* ~~Emil: Send the appointed election officers an email to announce the appointment and request that they present the election timeline at the Feb 8 TC meeting. Also add them to the meeting invite.~~
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Emil: Send existing Volvo contacts an email and ask about a summit.
* Magnus: Write an agenda for the OTel meeting.
* Mattias: Draft text of email to maintainers re archival.

### January 18, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
* Initiate TC elections by appointing Election Officers for 2024
    * https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#election-officers
    * Decision: Fatih Degirmenci and Fredrik Fristedt are appointed election officers until Jan 31, 2025.
    * Action Magnus: Update [GOVERNANCE.md](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md) accordingly. Draft issue created.
    * Action Emil: Send the appointees an email to announce the appointment and request that they present the election timeline at the Feb 8 TC meeting. Also add them to the meeting invite.
* When we answer someone who sends a mail via the Community Mailing list they need to be a member to see the response.
    * Action Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Scope of [Santiago edition](https://github.com/eiffel-community/eiffel/milestone/9)
    * One issue added to the edition and the due date was updated to 2024-03-15.
* Can we add a source tag event ([github.com/eiffel-community/eiffel#219](https://github.com/eiffel-community/eiffel/issues/219)) before we're reasonably done with the new source change events?
    * Action Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* ~~Emil: Talk to Panos about Vici's Dependabot PRs.~~
    * ~~We'll merge the Dependabot PRs now.~~
    * ~~Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.~~
    * ~~Update 2024-01-18: Draft issue for archiving the repository has been created.~~
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* ~~Emil/Magnus: Ask Fatih/Daniel/Kristofer and Fredrik if they're willing to be election officers for the next year.~~
* Emil: Send the appointed election officers an email to announce the appointment and request that they present the election timeline at the Feb 8 TC meeting. Also add them to the meeting invite.
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.

### January 11, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
    * Nothing in particular.
* Initiate TC elections by appointing Election Officers for 2024
    * https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#election-officers
    * Action: Ask Fatih/Daniel/Kristofer and Fredrik if they're willing to be election officers for the next year.
* Jan 18 community meeting
    * A possible topic for the community meeting on Jan 18 is OTel and how it might integrate with Eiffel (and vice versa). If we're not ready for that discussion by Jan 11 we'll cancel.
    * Decision: Cancel the meeting.
* We have multiple ongoing protocol PRs by multiple people. How can we work efficiently to avoid stepping on each other's toes and rebasing too much?
* Out of time, postponed: Scope of [Santiago edition](https://github.com/eiffel-community/eiffel/milestone/9)
* Out of time, postponed: Can we add a source tag event ([github.com/eiffel-community/eiffel#219](https://github.com/eiffel-community/eiffel/issues/219)) before we're reasonably done with the new source change events?
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
    * We'll merge the Dependabot PRs now.
    * Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Emil/Magnus: Ask Fatih/Daniel/Kristofer and Fredrik if they're willing to be election officers for the next year.
