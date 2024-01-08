###### tags: `Technical Committee`

# Technical Committee Meetings 2024

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2024-01-11 Meeting](#January-11-2024)

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
    * When/if decided: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.
* Should we propose to add event triggered updates to Renovate?
    * Note: Renovate has support for Gerrit now: https://github.com/renovatebot/renovate/releases/tag/37.112.0
    * Similar issue in CDEvents: https://github.com/cdevents/spec/issues/39

### January 11, 2024

#### Participants

* TC Attendees
    * Emil Bäckmark, present / not present
    * Magnus Bäck, present / not present
    * Mattias Linnér, present / not present

#### Agenda and Notes
* Rollcall, All
* Agenda Bashing, All
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDEvents, Emil
* Initiate TC elections by electing Election Officers for 2024
    * https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#election-officers
* Jan 18 community meeting
    * A possible topic for the community meeting on Jan 18 is OTel and how it might integrate with Eiffel (and vice versa). If we're not ready for that discussion by Jan 11 we'll cancel.
* We have multiple ongoing protocol PRs by multiple people. How can we work efficiently to avoid stepping on each other's toes and rebasing too much?
* Scope of [Santiago edition](https://github.com/eiffel-community/eiffel/milestone/9)
* Can we add a source tag event ([github.com/eiffel-community/eiffel#219](https://github.com/eiffel-community/eiffel/issues/219)) before we're reasonably done with the new source change events?
* PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
    * We'll merge the Dependabot PRs now.
    * Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
