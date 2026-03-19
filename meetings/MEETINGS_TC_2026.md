###### tags: `Technical Committee`

# Technical Committee Meetings 2026

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2026-03-19 Meeting](#March-19-2026)
    * [2026-03-05 Meeting](#March-5-2026)
    * [2026-02-12 Meeting](#February-12-2026)
    * [2026-01-22 Meeting](#January-22-2026)
    * [2026-01-08 Meeting](#January-8-2026)

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

### March 19, 2026

#### Participants

* TC Attendees
    * Magnus Bäck
    * Mattias Linnér

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
    * Approved.
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
* [TC Elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * The election officer pulled the eligibles on March 18, and we need a new TC meeting to deal with any exception requests. Let's use the TC meeting on April 2 for that. The nomination period can still be on the original dates.
* Should we have a Infrastructure focused community meetup?
    * Yes, let's use the April 23 meeting for that and extend it to one hour.
* Eiffel Summit 2026
    * Nothing planned so far. A smaller workshop-style summit could be an option that's easier to host.
* Should we expand on the recipe concept more? For example have a recipes for test and activities?
    * Yes, that would be useful. An ArtC can link to other artifacts (via ENVIRONMENT → EnvironmentDefined → RUNTIME_ENVIRONMENT) that describe e.g. the CI job definition, but perhaps we can do something more generalized.
    * Should SBOMs and VEX files be first-class citizens in the ecosystem? Both may be refined after the fact and can't necessarily be included in the original ArtC.
* What does the Eiffel Community have for guidelines on when project do incompatible changes and miss incrementing the API in the right way?
    * Changes in public APIs that aren't backwards incompatible but are labeled as such (e.g. by not bumping the major version) should be treated as bugs and be corrected.
* Have we reported any CVEs from the Community or are we bugfree?
    * The [eiffel-broadcaster plugin for Jenkins](https://www.cvedetails.com/vulnerability-list/vendor_id-15865/product_id-176435/Jenkins-Eiffel-Broadcaster-Plugin.html) has a CVE since early last year.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Magnus: Create Google calendar for important events.
* Magnus: Ask Tobias about the ETOS workflow on GitHub. Anything to demo?
* ~~Mattias: Check with Daniel Ståhl if there was a particular reason behind the ActF -> ActT linking (since it also differs from the Ericsson-internal version of the protocol).~~
     * ~~**Done:** No clear answer but more pointing to that TCT holds the semantic importance~~

### March 5, 2026

#### Participants

* TC Attendees
    * Magnus Bäck
    * Mattias Linnér

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * No updates.
* [TC Elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Anything else about the timeline
    * No, things look good.
* Community Meeting February 26
    * Technical issues prevented the meeting from starting. Two external participants tried to connected but was unable to. Magnus will try to understand what happened.
* Is there anything to demo of GitHub app (ETOS workflow)?
    * Action Magnus: Ask Tobias about this.
* For a beginner it might be confusing why e.g. TCF links to TCT and not TCS. Should we have a written explanation and reasoning around it?
    * One reason could be that it's more consistent if TCS, TCF, and TCC all link to the TCT.
    * Action Mattias: Check with Daniel Ståhl if there was a particular reason behind this (since it also differs from the Ericsson-internal version of the protocol).
* Regarding the discussion on general about Requirements
    * Do we need to document more clearly where Eiffel ends and not?
    * Any more comments to add to the dicussion?
    * Do we need to move anything to GitHub as we only have 3 months of history?
    * There is probably a plot hole in the test events. Even if we don't split test events into test case definitions and test case executions, there's currently no good way to link to the test case source code, nor a good way to link to the requirement that prompted the test case.
* Broadcom changes licenses for VMWare. Should we need to worry about RabbitMQ?
    * Probably not. Broadcom could attempt a rug pull, but that'll only affect new versions, and would probably result in a fork.
* Eiffel Eye demo.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Magnus: Create Google calendar for important events.
* Magnus: Ask Tobias about the ETOS workflow on GitHub. Anything to demo?
* Mattias: Check with Daniel Ståhl if there was a particular reason behind the ActF -> ActT linking (since it also differs from the Ericsson-internal version of the protocol).


### February 12, 2026

#### Participants

* TC Attendees
    * Magnus Bäck
    * Mattias Linnér

#### Agenda and Notes
* Rollcall (All)
    * We have quorum.
* Agenda Bashing (All)
* [TC Elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Fredrik wasn't able to come, but he's updated the election document.
    * Some dates were shifted, but overall okay. Magnus will talk to Fredrik about the changes made.
* Action Item Review (All)
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from OpenTelemetry CI/CD WG (Magnus)
    * No updates.
* Community Meeting February 26
    * Mattias on Vacation that week
    * We'll have the meeting anyway.
* Some people from the summit was not on the community list. Should we have some other additional means to find out about our the meetup?
    * Unclear. Let's follow up later.
* How do we block spam from the mail list like  [Feedback for Air Ducts and Vents Cleaning/Chimney Cleaning](https://groups.google.com/g/eiffel-community/c/_4x6XfKCCEM/m/8ax0ATRvAQAJ?utm_medium=email&utm_source=footer) - reporting it as spam does not help.
* Info - Slack content will be removed
    >This is a notice that starting March 28th, 2026, messages and files older than one year will be deleted from your workspace if you remain on the free Slack plan. 
* Info - [Petter Johansson's post about event driven software delivery](https://www.linkedin.com/pulse/event-driven-software-delivery-petter-johansson-os0wf?[…]ource=share&utm_medium=member_android&utm_campaign=share_via)
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* ~~Mattias: Update post-election checklist to cover this task.~~
    * https://github.com/eiffel-community/community/pull/225 - Merged
* Magnus: Create Google calendar for important events.


### January 22, 2026

#### Participants

* TC Attendees
    * Magnus Bäck
    * Mattias Linnér

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
* TC Elections
    * Fredrik Fristedt was appointed for another term as election officer, starting 2026-02-01 and ending 2027-01-31.
    * We'll ask him to prepare an election timeline and present it at the next TC meeting.
* Who has the responsiblility to sync HackMD documents to GitHub?
    * Have we any need to document the process of linking and pushing or is the HackMD documentation enough?
    * Technical Commitee notes
        * Whoever takes the notes will push to HackMD upon
          completion.
    * Election process
        * Pushed to GitHub after the annual elections.
        * Action Mattias: Update post-election checklist
          to cover this task.
* Do we need a calendar for the task to be done over the year or is that overthinking?
    * New technical meetings notes
    * Getting election officers
    * Starting summit discussions
    * Elections
    * Follow the post election checklist
    * Security officers
    * Action Magnus: Create Google calendar for important events
* Eiffel summit 2026
    * Too early to tell.
* Where to put a new API for publishing events?
    * In a new, aptly named, repository.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* ~~Mattias: Send directed email to people who during the summit expressed interest in the new kind of community meetings.~~
    * ~~Sent: 2026-01-08~~
* Mattias: Update post-election checklist to cover this task.
    * https://github.com/eiffel-community/community/pull/225
* Magnus: Create Google calendar for important events.

### January 8, 2026

#### Participants

* TC Attendees
    * Magnus Bäck
    * Mattias Linnér

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
* Remind people about next community meeting on Jan 29.
    * Action Mattias: Send directed email to people who during the summit expressed interest in the new kind of community meetings.
* Eiffel summit 2026
    * Hosting
    * Any new approaches? E.g. invite external speakers.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* Mattias: Send directed email to people who during the summit expressed interest in the new kind of community meetings.

### January 8, 2026

#### Participants

* TC Attendees
    * Magnus Bäck
    * Mattias Linnér

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
* Remind people about next community meeting on Jan 29.
    * Action Mattias: Send directed email to people who during the summit expressed interest in the new kind of community meetings.
* Eiffel summit 2026
    * Hosting
    * Any new approaches? E.g. invite external speakers.
* PRs and issues

#### Action Items
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* Magnus: Look into why "Reply All" on Google Groups doesn't actually reply all.
* Magnus: Check the proposed name of the source code tag event against the proposed new source change events to see if they're reasonably well aligned. If so we can move on with the tag event without waiting for the source change events.
* Mattias: Create issue(s) for security vulnerabilities.
* Mattias: Send directed email to people who during the summit expressed interest in the new kind of community meetings.