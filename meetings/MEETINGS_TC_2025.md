###### tags: `Technical Committee`

# Technical Committee Meetings 2025

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
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
* January 2025: Election officer appointment
* January 2025: Follow up email
* For https://github.com/eiffel-community/eiffel/community (Community Standards) - should we enable "Repository admins accept content reports" 

### January 9, 2025

#### Participants

* TC Attendees
    * Emil Bäckmark, present / not present
    * Magnus Bäck, present / not present
    * Mattias Linnér, present / not present

#### Agenda and Notes
* Rollcall (All)
* Agenda Bashing (All)
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Check in with Erik Sternersson.
