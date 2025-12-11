###### tags: `Technical Committee`

# Technical Committee Meetings 2025

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2025-12-11 Meeting](#December-11-2025)
    * [2025-11-13 Meeting](#November-13-2025)
    * [2025-10-15 Meeting](#October-15-2025)
    * [2025-09-18 Meeting](#September-18-2025)
    * [2025-09-11 Meeting](#September-11-2025)
    * [2025-08-21 Meeting](#August-21-2025)
    * [2025-07-03 Meeting](#July-3-2025)
    * [2025-06-12 Meeting](#June-12-2025)
    * [2025-06-05 Meeting](#June-5-2025)
    * [2025-05-08 Meeting](#May-8-2025)
    * [2025-04-23 Meeting](#April-23-2025)
    * [2025-04-10 Meeting](#April-10-2025)
    * [2025-03-19 Meeting](#March-19-2025)
    * [2025-03-06 Meeting](#March-6-2025)
    * [2025-02-06 Meeting](#February-6-2025)
    * [2025-01-23 Meeting](#January-23-2025)
    * [2025-01-09 Meeting](#January-9-2025)

## Logistics

* **When:** 13:00–14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_NGJhNDNjMTktYmE2NC00MDYwLWE5NzgtMjNhYTM0YzgwODM0%40thread.v2/0?context=%7b%22Tid%22%3a%2278703d3c-b907-432f-b066-88f7af9ca3af%22%2c%22Oid%22%3a%22535d914b-36ac-466b-af0a-b637f03eed42%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg) in order to prevent notes getting out of sync.

### Next

* Should we evaluate Eiffel against the [OpenSSF Security Scorecard](https://github.com/ossf/scorecard) and/or the [OpenSSF Best Practices](https://www.bestpractices.dev/en)?
* Should we enable Code scanning for all repos. See https://github.com/eiffel-community/eiffel-remrem-publish/security/code-scanning for an example.
    * Set via https://github.com/eiffel-community/eiffel-remrem-publish/settings/security_analysis
    * Workflow example: https://github.com/eiffel-community/eiffel-remrem-publish/blob/master/.github/workflows/codeql.yml
    * We need to understand how code scanning works before we enable it globally. Do we need a workflow similar to the codeql.yml above for things to work or is it enough to just click Enable in the repo (or global) settings?
        * (2024-02-21): You can set it up globaly - https://docs.github.com/en/code-security/code-scanning/enabling-code-scanning/configuring-default-setup-for-code-scanning-at-scale#eligible-repositories-for-codeql-default-setup
    * When/if decided: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.
* [OpenPubkey](https://www.bastionzero.com/openpubkey) for public key distribution
* How do we document the process for adding external repos to the community?
    * What responsiblities does the Community /TC have for external repos?
    * Should the TC enforce maintainer rules on external repos?
* Should we take another look at [eventcatalog](https://www.eventcatalog.dev/), see also [example](https://app.eventcatalog.dev/visualiser/?type=all&name=AllEventsAndServices)
    * Was previously raised on [TC 2023-01-26](https://github.com/eiffel-community/community/blob/master/meetings/MEETINGS_TC_2023.md#agenda-and-notes-24)
* Gap analysis - CDEvents vs Eiffel. To help CDEvents reach 1.0 we should provide our input on the gap
* [JSON schema to validate PURLs](https://github.com/package-url/purl-spec/pull/514)
* Remind people about next community meeting on Jan 29.

### December 11, 2025

#### Participants

* TC Attendees
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * No updates.
* Eiffel summit
    * Anything left?
        * Link to the last presentation slides missing from github.io page. Magnus will send PR.
    * Feedback
        * Responses from 10 participants. Short summary in https://hackmd.io/kb4fvw4MS_qRaLRTJBR-Ew. Will revisit when we look at a summit next year.
* [Santiago Edition](https://github.com/eiffel-community/eiffel/milestone/9)
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.

### November 13, 2025

#### Participants

* TC Attendees
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
    * No updates.
* Eiffel summit
    * Presentations
        * Still waiting for a few.
        * Action Magnus: Remind them.
    * Anything else left?
        * Action Magnus: Remind people about the feedback survey.
* Monthly community meetings
* [Santiago Edition](https://github.com/eiffel-community/eiffel/milestone/9)
    * Let's aim for a new edition before EOY.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* ~~Magnus: Draft mailing list email and LinkedIn and Slack posts to announce the new format for the meetings. Obviously also update the invites.~~
* ~~Magnus: Remind those who haven't shared their summit presentations.~~
* ~~Magnus: Remind people about the feedback survey.~~

### October 15, 2025

#### Participants

* TC Attendees
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
    * No updates.
* Eiffel summit
    * Videos
        * Mattias: Consolidate the three protocol news videos and publish them on Friday.
        * Magnus: Add chapters to videos, where appropriate.
        * Magnus: Prepare a PR with the summit.html to link to the videos.
    * Feedback form
        * Let's send the feedback form to the participants before the weekend.
    * Presentation uploads
        * Action Mattias: Send with PR his and Helena's slides. We'll remind the others next week if needed.
    * Reflections
        * Nice to see so many active participants.
        * Let's talk next year about the feasibility of another summit.
        * Proposal for new concept for the community meetings was perhaps the most important takeaway.
* Monthly community meetings
    * Convert existing community meetings to the new check-in concept and reduce the duration to 30 minutes.
        * Action Magnus: Draft mailing list email to announce the new format for the meetings. Obviously also update the invites.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Draft mailing list email to announce the new format for the meetings. Obviously also update the invites.
* ~~Mattias: Consolidate the three protocol news videos and publish them on Friday.~~
* ~~Mattias: Send with PR his and Helena's slides. We'll remind the others next week if needed.~~
* ~~Magnus: Add chapters to videos, where appropriate.~~
* ~~Magnus: Prepare a PR with the summit.html to link to the videos.~~

### September 18, 2025

#### Participants

* TC Attendees
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
    * No updates because of lack of time.
* Eiffel summit
    * See notes [Summit 2025 Planning](https://hackmd.io/RtTg-aRASzaoqk_CfJEvag?both#Summit-planning)
    * Everything correct https://eiffel-community.github.io/summit.html ?
        * Submission API abstract missing
            * Magnus will send PR.
    * Should we prepare some Q&A questions?
        * Yes. Put them in a new section in the Summit document.
    * Do the additional registrations warrant a change in schedule?
        * No.
    * Discussion about:
        * Source change verdirct
        * Community Discussion
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.

### September 11, 2025

#### Participants

* TC Attendees
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
    * [Interesting discussion about long-running spans](https://github.com/open-telemetry/opentelemetry-specification/discussions/4646)
* Eiffel summit
    * See notes [Summit 2025 Planning](https://hackmd.io/RtTg-aRASzaoqk_CfJEvag?both#Summit-planning)
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* ~~Magnus: Send invites to the fall's community meetings.~~

### August 21, 2025

#### Participants

* TC Attendees
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
* September community meeting
    * Too close in time and too close to the summit. Send invites starting with the November meeting.
* Eiffel summit
    * See notes [Summit 2025 Planning](https://hackmd.io/RtTg-aRASzaoqk_CfJEvag?both#Summit-planning)
    * Response from Volvo
    * Re check the proposed agenda to see if we have missed anything
* How are we doing with Santiago?
    * Let's try to get Santiago ready for the summit, at least the majority of the remaining issues.
* [Go SDK to get usable example programs for signing](https://github.com/eiffel-community/eiffelevents-sdk-go/issues/112)
* [JSON schema to validate PURLs](https://github.com/package-url/purl-spec/pull/514)
    * Let's more about it and talk in depth in the next meeting.
* Open telemetry and events - https://opentelemetry.io/docs/concepts/signals/traces/#span-events
* PRs and issues
    * [Add example of working with Git submodules](https://github.com/eiffel-community/eiffel/pull/404)
    * [Add EiffelSourceChangeApprovedEvent #236](https://github.com/eiffel-community/eiffel/issues/236) - do we need to enable reject on approval?

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* ~~Magnus: Review [GOVERNANCE.md](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md) to see if there are any plot holes when the number of people willing to be in the TC is very small.~~
    * ~~Update 2025-08-21: No plot holes or other conflicts found.~~
* Magnus: Send invites to the fall's community meetings.
* ~~Magnus: Announce registration form on mailing list some time in the second half of August.~~
    * ~~Mattias reminded people that they need to register instead of accepting the meeting call - Wed 2025-08-13 15:43.~~

### July 3, 2025

#### Participants

* TC Attendees
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
    * No updates.
* Community meeting on August 14?
    * No. Send invites for the September meeting and onwards.
* We get some new feature in Slack [New security features in Slack](https://slack.com/help/articles/39264531104275-Updates-to-feature-availability-and-pricing-for-Slack-plans#h_01JWSAEQ21DGPQSXAD44Z622KD). Anything we need to think of?
    * No, nothing of particular interest.
* [Proposal: Enable CI/CD Interoperability Through SDLC Workflow Segments](https://github.com/cdevents/spec/issues/253)
    * Interesting, but nothing to take action on right now. Let's track the issue.
* Standard API for event submission
* PRs and issues
    * [Add example of working with Git submodules](https://github.com/eiffel-community/eiffel/pull/404)

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review [GOVERNANCE.md](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md) to see if there are any plot holes when the number of people willing to be in the TC is very small.
* ~~Magnus: Execute TC election checklist.~~
* ~~Magnus: Check with current security officers if they're willing to remain for another term.~~
    * ~~Update 2025-06-11: They accepted another term.~~
* ~~Magnus: Prepare the invitation form until next Wednesday.~~
* Magnus: Send invites to the fall's community meetings.
* ~~Mattias: Update save-the-date calendar invite.~~
* ~~Mattias: Update summit.html with the link to the registration form.~~
* Magnus: Announce registration form on mailing list some time in the second half of August.
* ~~Magnus: Announce registration form on LinkedIn.~~
* ~~Magnus: Update GOVERNANCE.md with the new security officers.~~
    * ~~Update 2025-06-30: https://github.com/eiffel-community/community/pull/220~~

### June 12, 2025

#### Participants

* TC Attendees
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
    * No updates.
* Summit
    * Status of the invite
        * Action Mattias: Update save-the-date calendar invite.
        * Action Magnus: Announce registration form on mailing list.
        * Action Magnus: Announce registration form on LinkedIn.
    * Add the invite to the summit page
        * Action Mattias: Update summit.html with the link to the registration form.
* Eiffel TC
    * Appointment of security officers.
        * Fredrik Fristedt and Kristofer Hallén have accepted to continue for another term and were duly appointed for a term that ends May 31, 2026.
        * Action Magnus: Update GOVERNANCE.md.
    * Meetings during the summer
        * All meetings during Magnus's vacation canceled.
* Can we use AI in some why to help us do tickets and fixes? E.g. 
    * https://github.com/features/copilot
    * https://github.com/abuzarmahmood/blech_github_bot
    * Feel free to use them yourself, but no central work will be done.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review [GOVERNANCE.md](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md) to see if there are any plot holes when the number of people willing to be in the TC is very small.
* Magnus: Execute TC election checklist.
* ~~Magnus: Check with current security officers if they're willing to remain for another term.~~
    * ~~Update 2025-06-11: They accepted another term.~~
* Magnus: Prepare the invitation form until next Wednesday.
* Magnus: Send invites to the fall's community meetings.
* Mattias: Update save-the-date calendar invite.
* Mattias: Update summit.html with the link to the registration form.
* Magnus: Announce registration form on mailing list.
* Magnus: Announce registration form on LinkedIn.
* Magnus: Update GOVERNANCE.md with the new security officers.

### June 5, 2025

#### Participants

* TC Attendees
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
* Summit
    * Volvo's participation: Ask them for a status update and maybe a talk on their Neo4j usage?
        * Yes, it seems they've been active since the summit and should have things to say about the journey.
    * Any feedback we should think of:
        * https://hackmd.io/IOIGKpdcRh2FZVCn3AMO8A
        * https://docs.google.com/forms/d/1aJ5nWkvEx5RYmewSYdxOT9N0um4ux0F0fRt41hXEiD4/edit#responses
    * Action Magnus: Prepare the invitation form for next Wednesday.
* Eiffel TC
    * Appointment of security officers.
        * The previous ones haven't been asked yet. Postponing until the next meeting.
    * Invites for the fall's community meetings.
        * Action Magnus: Send invites.
* How to follow-up on https://nexergroup.com/events/ci-cd-gothenburg/ 
* Add us to the [CNCF landscape](https://landscape.cncf.io/guide#introduction--what-is-the-cloud-native-landscape)?
    * We should look into it. It seems we don't fulfill all the listed criteria but it might be accepted anyway.
* [Proposal: Enable CI/CD Interoperability Through SDLC Workflow Segments](https://github.com/cdevents/spec/issues/253) (Should we post this sort of things in the General Slack channel?)
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review [GOVERNANCE.md](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md) to see if there are any plot holes when the number of people willing to be in the TC is very small.
* Magnus: Execute TC election checklist.
* Magnus: Check with current security officers if they're willing to remain for another term.
* ~~Magnus: Send invites for TC meeting on even weeks, with the exception of the May 29 which is moved to May 28 to avoid the ascension public holiday. Don't forget to update the Teams link in the HackMD document.~~
* Magnus: Prepare the invitation form until next Wednesday.
* Magnus: Send invites to the fall's community meetings.

### May 8, 2025

#### Participants

* TC Attendees
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
    * No particular updates.
* [Post Technical Committee Election Checklist](https://github.com/eiffel-community/community/blob/master/howtos/post-tc-election-checklist.md)
* Meeting logistics for TC
    * Meeting time and dates
        * Action Magnus: Send invites for TC meeting on even weeks, with the exception of the May 29 which is moved to May 28 to avoid the ascension public holiday. Don't forget to update the Teams link in the HackMD document.
    * Invites for the Community Meeting
        * Recordings?
        * Send new invites for the fall meetings. There will be a meeting on May 22, but the June meeting conflicts with vacations, as does the July meeting.
* Summit
    * Reach out to companies regarding Eiffel Summit: Volvo Group, Nasdaq, VCC, DoWhile
    * Send the "save the date" mail
* [CDEvents Namespacing Proposal (WSDL-Inspired)](https://github.com/cdevents/spec/issues/250)
    * Interesting but nothing we have time to act on now.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review [GOVERNANCE.md](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md) to see if there are any plot holes when the number of people willing to be in the TC is very small.
* ~~Magnus: Try sending a Teams invite to Mattias to verify that everything works.~~
* Magnus: Execute TC election checklist.
* ~~Magnus: Execute TC member update checklist in reverse for Emil.~~
* ~~Magnus: Make sure update of [RESOURCES.md](https://github.com/eiffel-community/community/blob/master/RESOURCES.md) is covered by the checklist.~~
    * ~~Created issue [github.com/eiffel-community/community#217](https://github.com/eiffel-community/community/issues/217) to track this.~~
* ~~Magnus: Update current election officer in [GOVERNANCE.md](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md).~~
    * ~~[github.com/eiffel-community/community#219](https://github.com/eiffel-community/community/pull/219)~~
* Magnus: Check with current security officers if they're willing to remain for another term.
* ~~Mattias: Send "save the date" email once the date has been decided.~~
* Magnus: Send invites for TC meeting on even weeks, with the exception of the May 29 which is moved to May 28 to avoid the ascension public holiday. Don't forget to update the Teams link in the HackMD document.

### April 23, 2025

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
* Elections
    * Mattias and Magnus were reappointed for another TC term. Emil is leaving the TC.
    * Action: Execute TC election checklist in reverse for Emil.
    * Action: Execute TC member update checklist in reverse for Emil.
    * Action: Make sure update of RESOURCES.md is covered by the checklist.
* Someone needs to take over the invites from Emil.
    * Emil will cancel his invites.
    * Action Magnus: Attempt to take over the Teams invites.
* https://github.com/eiffel-community/community/blob/master/RESOURCES.md
* Coming TC meetings
    * Magnus has sent an invite to the next meeting on May 8. At that meeting we'll sort out the upcoming meeting occasions.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* ~~Mattias: Check in with Erik Sternersson.~~
    * ~~2025-01-09: Waiting for a response from Sabina.~~
    * ~~2025-03-18: No response from Sabina but checked via Erik.~~
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review GOVERNANCE.md to see if there are any plot holes when the number of people willing to be in the TC is very small.
* Magnus: Try sending a Teams invite to Mattias to verify that everything works.
* Execute TC election checklist in reverse for Emil.
* Execute TC member update checklist in reverse for Emil.
* Make sure update of RESOURCES.md is covered by the checklist.

### April 10, 2025

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
    * Some movement for semconv for pipeline execution parts.
* Updates from Kubecon (Emil & Mattias)
    * Interesting and well-visited talk by Adriel and Dotan.
* Codacy
    * This GitHub app has been enabled for a couple of repositories.
* Next community meeting on April 24
    * No topics are ready, canceling.
* Summit
    * One company may offer to host the summit. They will make a decision during the spring.
* Elections
    * Nomination period open, closing April 14.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.
    * 2025-01-09: Waiting for a response from Sabina.
    * 2025-03-18: No response from Sabina but checked via Erik.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review GOVERNANCE.md to see if there are any plot holes when the number of people willing to be in the TC is very small.

### March 19, 2025

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
* Next community meeting on March 27
* Summit
* Event-triggered Renovate
* Elections
    * https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw
        * The list of people eligible people was presented.
        * Nobody had requested an exception, so there was nothing to approve.
    * Did we publish the list on LinkedIn?
        * No.
* PRs and issues
    * https://github.com/eiffel-community/eiffel/pull/410

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.
    * 2025-01-09: Waiting for a response from Sabina.
    * 2025-03-18: No response from Sabina but checked via Erik. **(NEW)** 
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review GOVERNANCE.md to see if there are any plot holes when the number of people willing to be in the TC is very small.
* ~~Magnus: Attempt to locate any previous script for extracting maintainers from GitHub and, if located, send to Fredrik.~~

### March 6, 2025

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
    * Nothing in particular to report. One thing we could bring up in Slack and/or a working group meeting is integrating events from different such ecosystems with OTel entities, similar to what we talked about a community meeting last spring.
* Elections
    * Fredrik Fristedt will prepare a list of eligible candidates by early next week.
* Next community meeting the 27 of March
    * Will likely be canceled, but we can punt that decision until later.
* CDEvents have gone for AsyncAPI - https://github.com/cdevents/implementation-wg/issues/5
* UUID7 is out. Any benefit for switching?
    * No dramatic benefits. Will ignore for now.
* Summit
    * Mattias has talked to TietoEvry about co-hosting a summit, and they might be willing to help out.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.
    * 2025-01-09: Waiting for a response from Sabina.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review GOVERNANCE.md to see if there are any plot holes when the number of people willing to be in the TC is very small.
* Magnus: Attempt to locate any previous script for extracting maintainers from GitHub and, if located, send to Fredrik.

### February 6, 2025

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
* Other Attendees
    * Fredrik Fristedt

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
* Elections
    * Fredrik's [election plan](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw) was reviewed.
    * Action Magnus: Attempt to locate any previous script for extracting maintainers from GitHub and, if located, send to Fredrik.
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * PR for adding CI/CD metrics the semantic conventions merged: https://github.com/open-telemetry/semantic-conventions/pull/1681
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.
    * 2025-01-09: Waiting for a response from Sabina.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review GOVERNANCE.md to see if there are any plot holes when the number of people willing to be in the TC is very small.
* Magnus: Attempt to locate any previous script for extracting maintainers from GitHub and, if located, send to Fredrik.

### January 23, 2025

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
* Election officer appointment
    * Fredrik Fristedt was appointed as election officer for a term starting February 1, 2025, and ending January 31, 2026.
    * Invite Fredrik to the next TC meeting (February 6) and ask him to prepare a schedule for the election process.
* For https://github.com/eiffel-community/eiffel/community (Community Standards) - should we enable "Repository admins accept content reports"?
    * Yes, enabled for the protocol repo and community repo. See the [documentation](https://docs.github.com/en/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam) for what it means.
* GitHub package access
    * For some reason the organization had disallowed making GitHub packages public. This has been opened up via the [organization settings](https://github.com/organizations/eiffel-community/settings/packages). It's unclear when that setting was introduced or changed. At some point it was possible to pull Docker images without authentication.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.
    * 2025-01-09: Waiting for a response from Sabina.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review GOVERNANCE.md to see if there are any plot holes when the number of people willing to be in the TC is very small.
* ~~Mattias: Ask the Volvo folks if any of them are willing to sit in the TC.~~
* ~~Mattias: Ask Fatih about election officer appointment.~~
* ~~Magnus: Ask Fredrik about election officer appointment.~~

### January 9, 2025

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
* Election officer appointment
    * We ask Fatih and Fredrik if they'd like to be appointed for another term.
* Security officer question regarding vulnerabilities
    * Matter resolved in mid-December email thread.
* Community meeting Jan 30
    * Mattias will check with Johan at Volvo if he's willing to share their use of Neo4j. As a backup we can talk about SBOMs and build attestations, or follow up any of the topics from the December meeting.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.
    * 2025-01-09: Waiting for a response from Sabina.
* Mattias: Create issue(s) for security vulnerabilities.
* Magnus: Review GOVERNANCE.md to see if there are any plot holes when the number of people willing to be in the TC is very small.
* Mattias: Ask the Volvo folks if any of them are willing to sit in the TC.
* ~~Mattias: Ask Fatih about election officer appointment.~~
* ~~Magnus: Ask Fredrik about election officer appointment.~~
