###### tags: `Technical Committee`

# Technical Committee Meetings 2025

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2025-04-23 Meeting](#April-23-2025)
    * [2025-04-10 Meeting](#April-10-2025)
    * [2025-03-19 Meeting](#March-19-2025)
    * [2025-03-06 Meeting](#March-6-2025)
    * [2025-02-06 Meeting](#February-6-2025)
    * [2025-01-23 Meeting](#January-23-2025)
    * [2025-01-09 Meeting](#January-9-2025)

## Logistics

* **When:** 13:00–14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_OTc1NDIzNTUtYzJiMy00OThiLTkwZDUtYTdkODVhOGNjYzI3%40thread.v2/0?context=%7b%22Tid%22%3a%2292e84ceb-fbfd-47ab-be52-080c6b87953f%22%2c%22Oid%22%3a%2249725723-aa8c-4dcf-b9d0-b974e8a25702%22%7d)
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
