###### tags: `Technical Committee`

# Technical Committee Meetings 2023

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2023-12-14 Meeting](#December-14-2023)
    * [2023-11-29 Meeting](#November-29-2023)
    * [2023-11-16 Meeting](#November-16-2023)
    * [2023-11-01 Meeting](#November-1-2023)
    * [2023-10-12 Meeting](#October-12-2023)
    * [2023-10-05 Meeting](#October-5-2023)
    * [2023-09-21 Meeting](#September-21-2023)
    * [2023-09-07 Meeting](#September-7-2023)
    * [2023-08-24 Meeting](#August-24-2023)
    * [2023-08-17 Meeting](#August-17-2023)
    * [2023-08-09 Meeting](#August-9-2023)
    * [2023-06-29 Meeting](#June-29-2023)
    * [2023-06-01 Meeting](#June-1-2023)
    * [2023-05-25 Meeting](#May-25-2023)
    * [2023-05-17 Meeting](#May-17-2023)
    * [2023-05-04 Meeting](#May-4-2023)
    * [2023-04-27 Meeting](#April-27-2023)
    * [2023-03-30 Meeting](#March-30-2023)
    * [2023-03-23 Meeting](#March-23-2023)
    * [2023-03-08 Meeting](#March-8-2023)
    * [2023-02-22 Meeting](#February-22-2023)
    * [2023-02-09 Meeting](#February-09-2023)
    * [2023-02-02 Meeting](#February-02-2023)
    * [2023-01-25 Meeting](#January-25-2023)
    * [2023-01-11 Meeting](#January-11-2023)

## Logistics

* **When:** 13:00–14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_OTc1NDIzNTUtYzJiMy00OThiLTkwZDUtYTdkODVhOGNjYzI3%40thread.v2/0?context=%7b%22Tid%22%3a%2292e84ceb-fbfd-47ab-be52-080c6b87953f%22%2c%22Oid%22%3a%2249725723-aa8c-4dcf-b9d0-b974e8a25702%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/03BGtiW8Qyeqq5Q52BvrMw) in order to prevent notes getting out of sync.

### December 14, 2023

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
    * CDEvents governing board election will most likely be pushed to January.
* Updates from OTel CI/CD semantic conventions kick-off meeting
    * The [github.com/open-telemetry/community#1822](https://github.com/open-telemetry/community/pull/1822) PR is the basis for the formation of the working group. See the [minutes](https://docs.google.com/document/d/1zlBtUs8Kk15MJP3LFvJ6mi59nNF2UOPxuA4w2t0N23k/edit) from the first meeting for details.
* Meetings during and after the holidays
    * Canceling meetings Dec 21 and 28.
    * Keeping the extra TC meeting Jan 4 in the calendar for now.
    * A possible topic for the community meeting on Jan 18 is OTel and how it might integrate with Eiffel (and vice versa). If we're not ready for that discussion by Jan 11 we'll cancel.
* [Key distribution when signing events](https://groups.google.com/g/eiffel-community/c/Yu-yDytXjnQ/m/FuF3FqqWAQAJ)
    * Magnus will look into FRSCA, Sigstore, and related pieces of the new supply chain ecosystem to see if any of them fit in.
* PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
    * We'll merge the Dependabot PRs now.
    * Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* ~~Magnus: Send email to eiffel-community group to solicit participants in the new OTel working group.~~

### November 29, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * Election to the CDEvents governing board will probably be held in December.
    * Event linking PR still ongoing.
    * SBOM reference to be added to artifact.packaged event.
* Join OTel discussions about observability in CI/CD?
    * Meeting to be held on Dec 7 (?). See [this comment](https://github.com/open-telemetry/oteps/pull/223#issuecomment-1829753863) for more information.
    * Action: Magnus send email to eiffel-community group to solicit participants in the new working group.
    * Magnus will likely join the working group himself.
* Should Sepia graduate?
    * Yes. It fulfills the graduation requirements. Draft issue for updating the README file and the landscape picture created.
    * Also, should the commnity repos that de facto are outside the normal project lifecycle be marked as such in the landscape picture? Draft issue created.
* Info: Event signing updates
    * Event signing implementation for the Go SDK is ongoing ([github.com/eiffel-community/eiffelevents-sdk-go#9](https://github.com/eiffel-community/eiffelevents-sdk-go/issues/9)). Will be followed by a Java implementation in the eiffel-broadcaster plugin for Jenkins.
* Info: Eiffel Collector status
    * Increased Ericsson-internal priority. Official development will start and will hopefully be approved for open sourcing.
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
    * We'll merge the Dependabot PRs now.
    * Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ?: Read up on static code analysis (see item in Next) and bring info to TC
* ~~Magnus: Send email to eiffel-community group to solicit participants in the new working group.~~

### November 16, 2023

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* Rollcall, All
    * Quorum reached
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project board](https://github.com/orgs/eiffel-community/projects/3/views/4)
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDF sig-events, Emil & Mattias
    * Link discussion ongoing.
* Should we keep the not-yet-introduced dormant state?
    * No, we don't need it. Let's stick with the archived state. We can always open up a repository again if needed.
    * Close [github.com/eiffel-community/community#156](https://github.com/eiffel-community/community/issues/156) with an explanation of why we don't need the state.
    * Update [github.com/eiffel-community/community#148](https://github.com/eiffel-community/community/issues/148) to mention that we should inform on mailing list & Slack some time before archiving. The Jenkins community's process for taking over an abandoned plugin can be used as an inspiration.
* JSON Schema deprecation support - https://json-schema.org/draft/2020-12/draft-bhutton-json-schema-validation-00#rfc.section.9.3. Do we want to use it?
    * Yes, possibly. We need to upgrade the JSON Schema version before we can use the deprecation attribute. We currently don't have any fields that need to be deprecated so there's no rush.
* Should the ER lookup spec ([PR](https://github.com/eiffel-community/eiffel-event-repository/pull/12)) include references to link types?
    * No, allow any UPPERCASE_WITH_UNDERSCORES strings, including the magic "ALL" value. The help text can still contain a list of all link types. By doing this we allow custom events to be used and the API spec won't be as dependent on the events.
    * We'll write an issue in the protocol repo to add an autogenerated documentation page containing all link types.
* Out of time, postponed: Should Sepia graduate?
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
    * We'll merge the Dependabot PRs now.
    * Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.
* All: Evaluate key repositories according to the OpenSSF criteria.
* ~~Emil: Update agenda of Nov 9 extra TC meeting to cover CDEvents and linking.~~
* ~~Emil: Update the meeting invite for Nov 23 community meeting.~~

### November 1, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * Nothing in particular.
* Extra TC meeting Nov 9
    * Introduction to and discussion about how to connect events in CDEvents.
    * Action Emil: Update agenda to cover this topic.
* Meetup/summit
    * Next community meeting Nov 23
    * Summit
    * Meetup or community meeting about source change events during autumn?
        * What are the source change events used for? To trigger CI pipelines, or to show a correct/current view of objects referenced? Observability and/or interoperability
        * How are stacked changes handled in GitHub (stacked PRs)?
        * What about triggering pipelines on "Approved" and/or "Submittable" states?
        * Yes, action for Emil to update the meeting invite.
* Out of time, postponed: Should we keep the not-yet-introduced dormant state?
* Out of time, postponed: JSON Schema deprecation support - https://json-schema.org/draft/2020-12/draft-bhutton-json-schema-validation-00#rfc.section.9.3. Do we want to use it?
* Out of time, postponed: PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
    * We'll merge the Dependabot PRs now.
    * Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.
* ~~Magnus: Check with Tobias what the point of the dormant state actually is.~~
* ~~Emil: Send cancellation for Oct 26 community meeting.~~
* All: Evaluate key repositories according to the OpenSSF criteria.
* Emil: Update agenda of Nov 9 extra TC meeting to cover CDEvents and linking.
* Emil: Update the meeting invite for Nov 23 community meeting.

### October 12, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * Nothing in particular.
* Next community meeting October 26
    * No topic so we'll cancel.
    * Action Emil: Send cancellation.
* Meetup about source change events during autumn?
    * Depends on proposal from Emil & Mattias
    * Since it'll be a light-weight meetup we can start planning it when Emil & Mattias have something that's at least half-ready.
    * Nothing that's ready to share yet.
* Add OpenSSF Security Scorecard to our projects?
    * https://github.com/ossf/scorecard
    * Currently (Sep 2023) scans 1M projects nightly
    * [Instructions](https://securityscorecards.dev/)
    * Decision: We'll evaluate the three key TC repos to see what score we'd get and decide further actions based on that. Magnus will look at the eiffel repo, Emil the community repo, and Mattias the eiffel-sepia repo.
* Add OpenSSF Best Practices badge?
    * Currently (Sep 2023) 6k projects participating, 1k passing
    * https://www.bestpractices.dev/en
    * Decision: Same thing as the OpenSSF scorecard, above.
* PRs and issues

#### Action Items
* Emil: Look into proposal made in the maintainer role presentation from the 2021 summit.
* ~~Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.~~
    * ~~It's not clear exactly what this action was about. Almost two years have passed anyway. Closing.~~
* ~~Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.~~
    * ~~Effectively done.~~
* ~~Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.~~
    * ~~Replaced by [github.com/eiffel-community/community#182](https://github.com/eiffel-community/community/issues/182).~~
* Magnus: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.
* Magnus: Ask the security officers to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
    * We'll merge the Dependabot PRs now.
    * Depending on whether or not we'll introduce a dormant state we'll transition the repo to either dormant or just archive it.
* Magnus: Check with Tobias what the point of the dormant state actually is.
* Emil: Send cancellation for Oct 26 community meeting.
* All: Evaluate key repositories according to the OpenSSF criteria.

### October 5, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * Connected events continue to be discussed.
    * Ticket events, i.e. equivalent to EiffelIssueDefinedEvent, have also been discussed.
* Next community meeting October 26
    * See mail from Nasdaq
    * No obvious topic and we'll probably cancel, but keeping the meeting for now.
* Meetup about source change events during autumn?
    * Depends on proposal from Emil & Mattias
    * Since it'll be a light-weight meetup we can start planning it when Emil & Mattias have something that's at least half-ready.
* Why did we want a dormant state https://github.com/eiffel-community/community/issues/15? To keep it lightweight maybe we should only have archived (as the Community can bring back archived projects)
    * Action: Magnus: Check with Tobias what the point of the dormant state actually is.
* In https://github.com/eiffel-community/eiffel/tree/master/eiffel-syntax-and-usage we have both PNG and SVG files, but in https://github.com/eiffel-community/eiffel/tree/master/usage-examples we only have SVG. 
    * Have we agreed and documented (where?) to have both PNG and SVG?
    * Should we document howto/tips and tricks for InkScape (to ease for new people trying to update/create a event graph)
    * See also https://github.com/eiffel-community/community/blob/master/howtos/how-to-handle-graphical-images.md
* Do we want to introduce checks for grammar within our pipelines or as a tox target? We have for example
    * https://github.com/marketplace/actions/vale-linter
    * https://github.com/marketplace/actions/github-spellcheck-action
    * https://github.com/reviewdog/action-languagetool
* Out of time, postponed: Add OpenSSF Security Scorecard to our projects?
    * https://github.com/ossf/scorecard
    * Currently (Sept 2023) scans 1M projects nightly
    * [Instructions](https://securityscorecards.dev/)
* Out of time, postponed: Add OpenSSF Best Practices badge?
    * Currently (Sept 2023) 6k projects participating, 1k passing
    * https://www.bestpractices.dev/en
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* ~~Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.~~
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* Magnus: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.
* ~~Emil: Contact Volvo AB and Nasdaq to check if they have any topics for the next community meeting.~~
* Action security officers: Ask them to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.
* Magnus: Check with Tobias what the point of the dormant state actually is.

### September 21, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * Presentation of how to integrate OpenTelemetry and CDEvents ([pull request and more info](https://hackmd.io/2FRGlw9fTMmKN1OQUVvguA#Sep-19-2023)).
* Next community meeting September 28
    * No topic, cancelling meeting.
* Current status on Nordix work
    * https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ?view#September-8-2023
* Should we close https://github.com/orgs/eiffel-community/projects/4 as all tasks are now done?
    * Yes, project closed.
* Vici has several [Dependabot PRs](https://github.com/eiffel-community/eiffel-vici/pulls) should we just merge them for security reasons even if they could render Vici unusable because of breaking changes in the dependent API?
    * Or should Vici be set to dormant?https://github.com/eiffel-community/community/issues/156
    * No, not yet anyway.
    * Action Emil: Talk to Panos about this. TC recommends merging as many PRs as possible.
* Out of time, postponed: In https://github.com/eiffel-community/eiffel/tree/master/eiffel-syntax-and-usage we have both PNG and SVG files, but in https://github.com/eiffel-community/eiffel/tree/master/usage-examples we only have SVG. 
    * Have we agreed and documented(where?) to have both PNG and SVG?
    * Should we document howto/tips and tricks for InkScape (to ease for new people trying to update/create a event graph)
    * See also https://github.com/eiffel-community/community/blob/master/howtos/how-to-handle-graphical-images.md
* Out of time, postponed: Do we want to introduce checks for grammar within our pipelines or as a tox target? We have for example
    * https://github.com/marketplace/actions/vale-linter
    * https://github.com/marketplace/actions/github-spellcheck-action
    * https://github.com/reviewdog/action-languagetool
* Out of time, postponed: Add OpenSSF Security Scorecard to our projects?
    * https://github.com/ossf/scorecard
    * Currently (Sept 2023) scans 1M projects nightly
    * [Instructions](https://securityscorecards.dev/)
* Out of time, postponed: Add OpenSSF Best Practices badge?
    * Currently (Sept 2023) 6k projects participating, 1k passing
    * https://www.bestpractices.dev/en
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* Magnus: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.
* Emil: Contact Volvo AB and Nasdaq to check if they have any topics for the next community meeting.
* Action security officers: Ask them to try out the private vulnerability reporting feature.
* Emil: Talk to Panos about Vici's Dependabot PRs.

### September 7, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * The CDEvents PR concerned with links ([github.com/cdevents/spec#139](https://github.com/cdevents/spec/pull/139)) doesn't include links in the protocol but rather have the relations stored by a separate service.
    * CDEvents will participate in Hacktoberfest.
* Post-summit survey
    * Interesting parts of the responses collected in https://hackmd.io/6v4hYbmMRPSk2OHz3dIT-g.
* Next community meeting September 28
    * Action Emil: Contact Volvo AB and Nasdaq to check if they have any topics for the next community meeting.
* Physical/virtual meetup during the autumn?
    * Possibly physical meetup to discuss source change events during Q4, depending on if Emil will complete the counterproposal for new source change events.
* Do we use Travis CI anymore or should we remove it from https://github.com/organizations/eiffel-community/settings/oauth_application_policy? We might have tokens left.
    * Let's get rid of it. Draft issue created.
* Do we feel we capture all initiatives or should we use something like https://allcontributors.org/docs/en/overview?
    * No, not at this moment.
* Info: https://github.com/k8up-io/k8up/security/advisories/new uses issues to send security advisories. Maybe there is some update that allows this to be bettered handled now.
    * Action security officers: Ask them to try out the private vulnerability reporting feature.
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* ~~Emil: Check if Jonathan would be interested in being a TC member. Doesn't seem like a valid Action anymore~~
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* ~~Magnus: Create post-summit survey and send for internal review. Use [previous survey](https://docs.google.com/forms/d/1jGZyMAyHVYNedHAcY98YV_nMB6qECpYsptL0w_3Z-gI/edit) for inspiration.~~
* Magnus: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.
* Emil: Contact Volvo AB and Nasdaq to check if they have any topics for the next community meeting.
* Action security officers: Ask them to try out the private vulnerability reporting feature.

### August 24, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * Connected events discussion still ongoing. Mostly causality links in scope right now.
    * Ericsson is a member in CDF End user council. There is a high interest in that group to have event-driven CI/CD.
* Post-summit survey
    * Approved the current survey with a few updates. Magnus will send the survey to the attendants.
* Could we close?
    - https://github.com/eiffel-community/community/issues/44
        - Emil will close issue.
    - https://github.com/eiffel-community/community/issues/4
        - Emil will close issue.
    - https://github.com/eiffel-community/community/issues/10
        - Mattias will close issue.
    - https://github.com/eiffel-community/community/issues/47
        - Magnus will look into the issue and see if it's okay to close.
    - https://github.com/orgs/eiffel-community/projects/3/views/4?pane=issue&itemId=9276722 isn't it there in https://github.com/eiffel-community/community/blob/master/howtos/update-tc-members.md
        - That draft issue was archived during the meeting
* Could we merge?
    - https://github.com/eiffel-community/eiffel-jira-plugin/pull/33
        - Emil: Yes, merge PR.
    - https://github.com/eiffel-community/ml-jmespath-generator/pull/1
        - Emil: Yes, merge PR and close referenced issue.
* Enforce GitHub Codescanning, secret scanning, dependabot PRs, Dependabot Alerts (https://github.com/organizations/eiffel-community/settings/security_analysis)
    * Solvable with [github.com/eiffel-community/community#151](https://github.com/eiffel-community/community/issues/151)?
    * Action Magnus: Enable everything globally from the organization and send email to the mailing list about this change.
* We have a board to follow-up on the protocol issues. How do we follow up on community issues e.g. the newly created https://github.com/eiffel-community/community/issues/175 (that was closed as it was a duplication, but it serves as an example)?
    * Could we set up a GH action to add new issues to a project board? Yes, [github.com/eiffel-community/community#182](https://github.com/eiffel-community/community/issues/182) created. Should cover both community repos and the protocol repo.
    * Additionally, existing issues should be added to the TC or protocol boards. Magnus already has a tracked action for this.
* How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
    * Use next extra TC meeting for prioritizing the protocol issues, including documentation issues. Emil will update the invite to include the other protocol maintainers.
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* Magnus: Create post-summit survey and send for internal review. Use [previous survey](https://docs.google.com/forms/d/1jGZyMAyHVYNedHAcY98YV_nMB6qECpYsptL0w_3Z-gI/edit) for inspiration.
* Magnus: Enable all code scanning, Dependabot, secret scanning etc globally from the organization and send email to the mailing list about this change.

### August 17, 2023

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present

#### Agenda and Notes
* When should we step versions of our events. As per https://github.com/eiffel-community/eiffel/pull/366#pullrequestreview-1573957182
    - We decided to try to be ultra strict - any change in a yaml file will result in the version stepped on the event, regardless of if it is just a spelling error or other.
* Community meeting in two weeks
    * Topic decided. See community meeting HackMd Doc.
* How should we handle email adresses? Should we display them as in https://github.com/eiffel-community/community/pull/179 or should we link to the GitHub profile instead so that the persons can decide it themselves?
    - Should we also update the list of TC members ([TC](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#technical-committee-members))? (And maybe require a TC to have a public email in its profile)
    - Decided to move the maintainers rows in the Google group table to the issue about removing Google groups
    - Decided to replace all individual mail links with links to their Github profiles
* Out of time, postponed: How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
* Out of time, postponed: Enforce GitHub Codescanning, secret scanning, dependabot PRs, Dependabot Alerts (https://github.com/organizations/eiffel-community/settings/security_analysis)
    * Solvable with [github.com/eiffel-community/community#151](https://github.com/eiffel-community/community/issues/151)?
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* Magnus: Create post-summit survey and send for internal review. Use [previous survey](https://docs.google.com/forms/d/1jGZyMAyHVYNedHAcY98YV_nMB6qECpYsptL0w_3Z-gI/edit) for inspiration.

### August 9, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * Connected events discussions continue.
    * Also source change events. [Issues](https://github.com/cdevents/spec/issues) have been created.
* Post-summit survey
    * Still not done. Magnus will make a proposal and post on Slack.
* Physical/virtual meetup during the autumn
    * Possibly a virtual meetup during the autumn, but we'll punt on it and talk about it later. We'll probably have a summit in April or May.
* Is this interesting? https://killercoda.com/about
    * Interesting, but not something we have time for right now.
* Given the comments in https://github.com/eiffel-community/eiffel/pull/367 should we have a dependabot best practice for the community?
    * Yes, we shoud have a best practices document where e.g. this is documented. Draft issue created.
* Converting draft issues to real issues, with template. Try this workaround: https://github.com/orgs/community/discussions/14010#discussioncomment-6123115
    - Yes it works!
* How to relate to OpenTelemetry? A community meeting about it to start with? See https://github.com/open-telemetry/oteps/pull/223#discussion_r1196347548
    * We need to learn more about traces before we can talk about this topic. Perhaps we could invite an external party? Or just wait until one of us has used it?
* Out of time, postponed: How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
* Out of time, postponed: Enforce GitHub Codescanning, secret scanning, dependabot PRs, Dependabot Alerts (https://github.com/organizations/eiffel-community/settings/security_analysis)
    * Solvable with [github.com/eiffel-community/community#151](https://github.com/eiffel-community/community/issues/151)?
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* Magnus: Create post-summit survey and send for internal review. Use [previous survey](https://docs.google.com/forms/d/1jGZyMAyHVYNedHAcY98YV_nMB6qECpYsptL0w_3Z-gI/edit) for inspiration.


### June 29, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * There will be a discussion tomorrow about a proposal for event correlation/linking.
    * JFrog seems to be interested in supporting CDEvents.
* Discuss [github.com/eiffel-community/eiffel#354](https://github.com/eiffel-community/eiffel/pull/354)
    * PR approved.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * Action Magnus: Create post-summit survey and send for internal review. Use [previous survey](https://docs.google.com/forms/d/1jGZyMAyHVYNedHAcY98YV_nMB6qECpYsptL0w_3Z-gI/edit) for inspiration.
* [Orizaba edition](https://github.com/eiffel-community/eiffel/milestone/8)
* Out of time, postponed: Physical/virtual meetup during the autumn
* Out of time, postponed: Is this interesting? https://killercoda.com/about
* Out of time, postponed: How to relate to OpenTelemetry? A community meeting about it to start with? See https://github.com/open-telemetry/oteps/pull/223#discussion_r1196347548
* Out of time, postponed: How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
* Out of time, postponed: Enforce GitHub Codescanning, secret scanning, dependabot PRs, Dependabot Alerts (https://github.com/organizations/eiffel-community/settings/security_analysis)
    * Solvable with [github.com/eiffel-community/community#151](https://github.com/eiffel-community/community/issues/151)?
* PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* ~~Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.~~
    * ~~Agreed to not shut down the cluster~~
    * ~~No action on Eiffel TC, but EST/Nordix will try to find time/resources to deploy on the cluster.~~
    * ~~Information to be updated on https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ~~
    * ~~Emil & Mattias to follow up with Nordix next time we meet them~~
    * ~~Panos will make an attempt to deploy Easy2Use on Nordix. Aims to be presented on Eiffel summit.~~
    * ~~Presented on summit. Next step is to continue setting up stuff towards Eiffel 4 Eiffel on Nordix. This is handled in one of the GitHub project boards.~~
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* ~~Emil: Cancel the meetings during the vacations.~~
* ~~Emil: Cancel community meeting and book summit instead in its place.~~
* ~~Emil: Close the registration form since we're more or less out of seats.~~
* ~~Emil: Send email to everyone who's registered.~~
* Magnus: Create post-summit survey and send for internal review. Use [previous survey](https://docs.google.com/forms/d/1jGZyMAyHVYNedHAcY98YV_nMB6qECpYsptL0w_3Z-gI/edit) for inspiration.

### June 1, 2023

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
* Updates from CDF sig-events, Emil & Mattias
    * There was a meeting with JFrog about possibly adding CDEvents support to Artifactory.
    * There's a [draft PR](https://github.com/cdevents/spec/pull/139) for adding link support to CDEvents.
* Issues for all PRs?
    * Draft issue created.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * Action Emil: Close the registration form since we're more or less out of seats.
    * Action Emil: Send email to everyone who's registered.
* [Orizaba edition](https://github.com/eiffel-community/eiffel/milestone/8)
* Removing links to GitHub pages (https://github.com/eiffel-community/eiffel-remrem-publish/pull/264 for example). Should we also remove the gh-pages branch?
    * We should clear out the contents of deprecated gh-pages branches but keep the branches themselves so that the data stays accessible. Draft issue created.
* Out of time, postponed: How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
* Out of time, postponed: Enforce GitHub Codescanning, secret scanning, dependabot PRs, Dependabot Alerts (https://github.com/organizations/eiffel-community/settings/security_analysis)
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.
    * Agreed to not shut down the cluster
    * No action on Eiffel TC, but EST/Nordix will try to find time/resources to deploy on the cluster.
    * Information to be updated on https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ
    * Emil & Mattias to follow up with Nordix next time we meet them
    * Panos will make an attempt to deploy Easy2Use on Nordix. Aims to be presented on Eiffel summit.
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* ~~Emil: Cancel the meetings during the vacations.~~
* ~~Emil: Cancel community meeting and book summit instead in its place.~~
* ~~Emil: Close the registration form since we're more or less out of seats.~~
* ~~Emil: Send email to everyone who's registered.~~

### May 25, 2023

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
* Updates from CDF sig-events, Emil & Mattias
* Elect [security officers](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#security-officers)
    * The term of the current officers, Kristofer H and Fredrik F, ends on May 31st. Both have accepted to continue for another year.
    * Decision: Kristofer Hallén and Fredrik Fristedt are appointed to a new term as security officers. Their new term ends 2024-05-31.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * Magnus will try to have meeting with Erik on May 26.
    * Emil and Magnus (and maybe Mattias) will meet next week.
* [Orizaba edition](https://github.com/eiffel-community/eiffel/milestone/8)
* Vacation plans for TC members
    * Emil: w27–31
    * Magnus: w28–31
    * Mattias: w25
    * Last TC meeting before summer hiatus will be June 29. Next TC meeting w 32, August 10.
    * Action Emil: Cancel the meetings during the vacations.
* June 8 community meeting
    * Cancelled. Will be replaced with a summit preparation meeting together with Erik.
    * Action Emil: Cancel community meeting and book summit instead in its place.
* Should we have rules for what Java package paths to use in Eiffel Community repos?
    * See for example the new repos eiffel-demo-cdevents and eiffel-translator-cdevents
    * The original contributor chooses the Java package name, typically based on the contributing organization's domain name. Draft issue to document this has been created.
* [OWASP Top 10 CI/CD Security risks](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
    * Interesting compilation but nobody has time to document Eiffel's applicability for addressing the risks.
* Out of time, postponed: Removing links to GitHub pages (https://github.com/eiffel-community/eiffel-remrem-publish/pull/264 for example). Should we also remove the gh-pages branch?
* Out of time, postponed: How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
* Out of time, postponed: Enforce GitHub Codescanning, secret scanning, dependabot PRs, Dependabot Alerts (https://github.com/organizations/eiffel-community/settings/security_analysis)
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.
    * Agreed to not shut down the cluster
    * No action on Eiffel TC, but EST/Nordix will try to find time/resources to deploy on the cluster.
    * Information to be updated on https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ
    * Emil & Mattias to follow up with Nordix next time we meet them
    * Panos will make an attempt to deploy Easy2Use on Nordix. Aims to be presented on Eiffel summit.
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* Emil: Cancel the meetings during the vacations.
* Emil: Cancel community meeting and book summit instead in its place.

### May 17, 2023

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
* Updates from CDF sig-events, Emil & Mattias
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
* Recap of [May 11 community meeting about source change events](https://hackmd.io/fYFr6BIgTE-o2_49T7RDUQ)
    * Home work for both Axis and Ericsson to prepare arguments and counter arguments.
* [Orizaba edition](https://github.com/eiffel-community/eiffel/milestone/8)
* Out of time, postponed: Should we have rules for what Java package paths to use in Eiffel Community repos?
    * See for example the new repos eiffel-demo-cdevents and eiffel-translator-cdevents
* Out of time, postponed: [OWASP Top 10 CI/CD Security risks](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
* Out of time, postponed: Removing links to GitHub pages (https://github.com/eiffel-community/eiffel-remrem-publish/pull/264 for example). Should we also remove the gh-pages branch?
* Out of time, postponed: How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
* Postponed: Elect [security officers](https://github.com/eiffel-community/community/blob/master/GOVERNANCE.md#security-officers)
    * The term of the current officers, Kristofer H and Fredrik F, ends on May 31st.
    * During the meeting it wasn't clear whether both would like to continue so this will be added to the agenda of the next meeting.
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.
    * Agreed to not shut down the cluster
    * No action on Eiffel TC, but EST/Nordix will try to find time/resources to deploy on the cluster.
    * Information to be updated on https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ
    * Emil & Mattias to follow up with Nordix next time we meet them
    * *NEW* Panos will make an attempt to deploy Easy2Use on Nordix. Aims to be presented on Eiffel summit.
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* ~~Emil: Go through the [TC member checklist](https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md) to remove Tobias.~~
* ~~Emil: Announce the co-chair appointment to the mailing list.~~

### May 4, 2023

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
        * Action Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
    * Follow up [the Eiffel protocol project board](https://github.com/orgs/eiffel-community/projects/6)
* Updates from CDF sig-events, Emil & Mattias
    * 0.3 release this week, probably. Will include a revamp of test events and a new "artifact signed" event.
* New TC, including co-chair election
    * Action Emil: Go through the [TC member checklist](https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md) to remove Tobias.
    * Emil and Magnus appointed as co-chairs.
    * Action Emil: Announce the co-chair appointment to the mailing list.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
* Can we complete the [Orizaba edition](https://github.com/eiffel-community/eiffel/milestone/8) before the summit?
    * We populated the milestone with a number of issues that would be realistic to include in the Orizaba edition. Let's aim to have them ready by June 1.
* How can we get some progress with all the [open documentation issues in the protocol repo](https://github.com/eiffel-community/eiffel/issues)?
    * Discussed but no conclusion.
* Out of time, postponed: Should we have rules for what Java package paths to use in Eiffel Community repos?
    * See for example the new repos eiffel-demo-cdevents and eiffel-translator-cdevents
* Out of time, postponed: [OWASP Top 10 CI/CD Security risks](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
* Out of time, postponed: Removing links to GitHub pages (https://github.com/eiffel-community/eiffel-remrem-publish/pull/264 for example). Should we also remove the gh-pages branch?
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.
    * Agreed to not shut down the cluster
    * No action on Eiffel TC, but EST/Nordix will try to find time/resources to deploy on the cluster.
    * Information to be updated on https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ
    * New action: Emil & Mattias to follow up with Nordix next time we meet them
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* ~~Magnus: Update the summit page with more details on the themes and a link to the registration form.~~
* ~~Magnus: Send When2Meet to Emil and Erik S to talk about topics and the agenda.~~
* ~~Emil: Send an email to Software Center and the community mailing list when the summit page has been updated with themes and a link to the sign-up form.~~
* Magnus: Go through repos under TC's purview and make sure all issues are added to the TC board.
* Emil: Go through the [TC member checklist](https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md) to remove Tobias.
* Emil: Announce the co-chair appointment to the mailing list.

### April 27, 2023

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
    * Follow up [the TC GitHub project](https://github.com/orgs/eiffel-community/projects/3/views/4)
* Updates from CDF sig-events, Emil & Mattias
    * A [Jenkins plugin for CDEvents](https://github.com/jenkinsci/cdevents-plugin) is now available.
* Highlights from KubeCon
    * Seemingly more buzz over OpenTelemetry than CloudEvents.
* [TC Elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * New TC to assume seats on May 4.
    * We thank Tobias for his two years of service in the TC.
* [Community meeting follow-up](https://hackmd.io/dpQQOkEeQoC5yV7IpFUYOg)
* Next community meeting May 11
    * Decided to talk about Source change events and tags.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * Update summit page with form
        * Existing action for Magnus
    * Interact with Software Center?
        * Action Emil to send an email to SC and the community mailing list when the summit page has been updated with themes and a link to the sign-up form.
    * From community meeting April 13th - bring the topic of CLM for HW&SW to the Eiffel Summit. See the discussion here: https://hackmd.io/dpQQOkEeQoC5yV7IpFUYOg
    * Action Magnus: Send When2Meet to Emil and Erik S to talk about topics and the agenda.
* Remove [github.com/eiffel-community/appium](https://github.com/eiffel-community/appium)?
    * Yes. The fork was created on 2023-02-02, clearly be mistake.
* Common [branching strategy](https://github.com/eiffel-community/community/issues/150)?
    * Yes, but only as a suggested strategy (i.e. not mandated). Draft issue created.
* GitHub projects can now define [roadmaps](https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/) - do we want to use such?
    * No, not now anyway.
* Out of time, postponed: Should we have rules for what Java package paths to use in Eiffel Community repos?
    * See for example the new repos eiffel-demo-cdevents and eiffel-translator-cdevents
* Out of time, postponed: [OWASP Top 10 CI/CD Security risks](https://owasp.org/www-project-top-10-ci-cd-security-risks/)
* Out of time, postponed: Removing links to GitHub pages (https://github.com/eiffel-community/eiffel-remrem-publish/pull/264 for example) . Should we also remove the gh-pages branch?
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.
    * Agreed to not shut down the cluster
    * No action on Eiffel TC, but EST/Nordix will try to find time/resources to deploy on the cluster.
    * Information to be updated on https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ
    * New action: Emil & Mattias to follow up with Nordix next time we meet them
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* ~~Magnus: Check with Johan if he's willing to present the problem at the April 13 community.~~
* Magnus: Update the summit page with more details on the themes and a link to the registration form.
* ~~Emil: Update the summit invite.~~
* Magnus: Send When2Meet to Emil and Erik S to talk about topics and the agenda.
* Emil: Send an email to Software Center and the community mailing list when the summit page has been updated with themes and a link to the sign-up form.

### March 30, 2023

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
    * Follow up [the TC GitHub project](https://github.com/orgs/eiffel-community/projects/3/views/4)
* [TC Elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
* Updates from CDF sig-events, Emil & Mattias
    * Value Stream Management Consortium has visited the CDF TOC. SIG events got an action to stay in touch with VSM.
* April 13 community meeting
    * Last week we decided that source change events would be the topic, but both Magnus and Sven (who proposed the new source change events) won't be able to make it that day. Should we talk about CLMs for combinations of software/hardware instead?
    * Yes.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
* Dependabot Alerts for the whole organization
    * https://github.blog/changelog/2022-02-08-view-dependabot-alerts-across-an-organization/
    * Could we do something like looping over `curl https://github.com/eiffel-community/<reponame>/security/dependabot`?
    * Since there's no way to get an organization-wide overview of open vulnerabilities TC will simply delegate this tracking to the maintainers. This is already tracked in https://github.com/eiffel-community/community/issues/153.
* Out of time, postponed: Common [branching strategy](https://github.com/eiffel-community/community/issues/150)?
* Out of time, postponed: GitHub projects can now define [roadmaps](https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/) - do we want to use such?
* Out of time, postponed: Should we have rules for what Java package paths to use in Eiffel Community repos?
    * See for example the new repos eiffel-demo-cdevents and eiffel-translator-cdevents
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.
    * Agreed to not shut down the cluster
    * No action on Eiffel TC, but EST/Nordix will try to find time/resources to deploy on the cluster.
    * Information to be updated on https://hackmd.io/X3Nrxe4MRdSJI_lsTkSwiQ
    * New action: Emil & Mattias to follow up with Nordix next time we meet them
* Emil: Check if Jonathan would be interested in being a TC member.
* Emil: Ask Nasdaq is they have any topic they would like to discuss at a community meeting.
* ~~Magnus: Check with Johan if he's willing to present the problem at the April 13 community.~~
* Magnus: Update the summit page with more details on the themes and a link to the registration form.
* Emil: Update the summit invite.

### March 23, 2023

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
    * Follow up [the TC GitHub project](https://github.com/orgs/eiffel-community/projects/3/views/4)
* [TC Elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Decide on exceptions to the list of eligible people.
* Updates from CDF sig-events, Emil & Mattias
    * Version 0.2 released on March 21. Includes incident events.
    * Work ongoing to update Java, Python, and Go SDKs.
    * Proposal to add optional objects for links and global context id.
* Mattias is away April 6 and 20. Emil is away April 20th. Should the extra meetings on March 30 and/or April 27 be turned into ordinary TC meetings so they don't fall too far apart?
    * April 20th to be canceled?
    * Yes, cancel meeting on April 6 and 20.
    * Replace with ordinary meetings on March 30 and April 27.
* Decide topic for April 13 community meeting? Suggestions:
    * How to express confidence in an artifact/hardware combination?
    * Source change events and tags.
    * Decision: Source change events and tags on April 13, confidence in combinations remains a viable candidate for May 11.
* Take some action on deploying Eiffel services on Nordix?
    * Action Emil/Mattias: Talk to the Nordix folks.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * How should we continue developing the agenda?
* Out of time, postponed: Common [branching strategy](https://github.com/eiffel-community/community/issues/150)?
* Out of time, postponed: GitHub projects can now define [roadmaps](https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/) - do we want to use such?
* Out of time, postponed: Dependabot Alerts for the whole organization
    * https://github.blog/changelog/2022-02-08-view-dependabot-alerts-across-an-organization/
    * Could we do something like looping over `curl https://github.com/eiffel-community/<reponame>/security/dependabot`?
* Out of time, postponed: Should we have rules for what Java package paths to use in Eiffel Community repos?
    * See for example the new repos eiffel-demo-cdevents and eiffel-translator-cdevents
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* ~~Magnus: Announce podcast episode on LinkedIn.~~
* ~~Magnus: Initiate discussion with election officers.~~
* ~~Emil: Set up meeting with Erik about Summit planning~~
* ~~Magnus: Create the script and send the list to Election Officers on Monday.~~
* Emil/Mattias: Talk to the Nordix folks about the future of the k8s cluster.

### March 8, 2023

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
    * Follow up [the TC GitHub project](https://github.com/orgs/eiffel-community/projects/3/views/4)
* Updates from CDF sig-events, Emil & Mattias
    * Incident events about to be merged into CDevents. Release planned for coming Monday.
* [TC Elections](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Candidates to be listed on Friday (March 10th)
        * List members of all teams that are called "*-maintainers"
    * List to be published on Monday (March 13th)
    * Who performs these tasks?
        * Action Magnus: Create the script and send the list to Election Officers on Monday.
* Next week's community meeting
    * No obvious agenda so we'll cancel.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * How to involve doWhile?
        * Have an early check-in with Erik to see to what extent he wants to be involved and to sort out some practicality questions right away. Emil to set up a meeting with Erik and TC to discuss the way forward.
    * How should we continue developing the agenda?
        * Let's see after meeting with Erik.
    * How to communicate with Software Center?
        * Let's talk to the respective company representatives (Ericsson's and Axis's) in Software Center.
* At the summit we talked about describing relationships between artifacts. Was there an issue filed for this? Should there be one?
    * We'll drop this topic for now as we don't see a sufficiently large need to solve the problem.
* Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
    * Draft issue created.
* Out of time, postponed: Common [branching strategy](https://github.com/eiffel-community/community/issues/150)?
* Out of time, postponed: GitHub projects can now define [roadmaps](https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/) - do we want to use such?
* Out of time, postponed: Dependabot Alerts for the whole organization
    * https://github.blog/changelog/2022-02-08-view-dependabot-alerts-across-an-organization/
    * Could we do something like looping over `curl https://github.com/eiffel-community/<reponame>/security/dependabot`?
* Out of time, postponed: Should we have rules for what Java package paths to use in Eiffel Community repos?
    * See for example the new repos eiffel-demo-cdevents and eiffel-translator-cdevents
* Out of time, postponed: PRs and issues

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* ~~Magnus: Announce podcast episode on LinkedIn.~~
* ~~Magnus: Initiate discussion with election officers.~~
* ~~Emil: Set up meeting with Erik about Summit planning~~
* ~~Magnus: Create the script and send the list to Election Officers on Monday.~~

### February 22, 2023

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, partially present

#### Agenda and Notes

* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
    * Follow up [the TC GitHub project](https://github.com/orgs/eiffel-community/projects/3/views/4)
* TC elections
    * [Elections document](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * We noticed a discrepancy between GOVERNANCE.md and the elections document regarding eligibility. We decided to follow what the former says but to get this decision confirmed with the election officers before proceeding to update the elections document.
    * Action Magnus: Initiate discussion with election officers.
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * Let's nail the dates, location and the high-level focus
    * Send out invites
    * Decided on June 13–14 in Gothenburg.
    * Extra extra TC meeting on Feb 23 to discuss summit topics and agenda. Emil to send invite to TC.
* Updates from CDF sig-events, Emil & Mattias
    * There's a proposal from an Apple engineer to use a hybrid solution for links with both something that resembles Eiffel but also support for global IDs.
    * [CDEvents in tools](https://github.com/orgs/cdevents/projects/4/views/1)
* Eiffel vision/mission - related to [community issue 190](https://github.com/eiffel-community/eiffel/issues/190)
    * How to continue from the earlier extra TC meeting?
    * Emil and Mattias will look at it as time permits.
* Follow up from last weeks' community meeting
    * https://hackmd.io/nAfMMmKZRdyzJthWTwtXlg
* Out of time, postponed: At the summit we talked about describing relationships between artifacts. Was there an issue filed for this? Should there be one?
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: Common [branching strategy](https://github.com/eiffel-community/community/issues/150)?
* Out of time, postponed: GitHub projects can now define [roadmaps](https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/) - do we want to use such?
* Out of time, postponed: Dependabot Alerts for the whole organization
    * https://github.blog/changelog/2022-02-08-view-dependabot-alerts-across-an-organization/
    * Could we do something like looping over `curl https://github.com/eiffel-community/<reponame>/security/dependabot`?
* Out of time, postponed: PRs and issues 

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* ~~Emil: Send invite for separate meeting to discuss event linking vs. CDevents.~~
    * ~~Discussion held as part of a community meeting on Feb 16th~~
* ~~Emil: Ask Frank at EST to get an updated list of contributors from EST's Bitergia tool.~~
    * ~~Information received and documented through the election process on https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw#Eligible-Community-Members~~
* Magnus: Initiate discussion with election officers.

### February 9, 2023

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, not present

* Others
    * Fatih Degirmenci, Election Officer, present
    * Fredrik Fristedt, Election Officer, present

#### Agenda and Notes

* Rollcall, All
    * We have quorum.
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* TC elections, Fatih & Fredrik
    * [Elections document](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw)
    * Action Emil: Ask Frank at EST to get an updated list of contributors from EST's Bitergia tool.
    * Created draft issue to update GOVERNANCE.md to clearly state how to make exceptions to the election eligibility.
    * Election timeline approved.
* Action Item Review, All
    * Follow up [the TC GitHub project](https://github.com/orgs/eiffel-community/projects/3/views/4)
* [Eiffel Summit 2023](https://hackmd.io/_uJkbcSWR0aSaYDE0TRPqg)
    * What step to take next and when?
    * Co-location with Software Center reporting workshop still a possibility.
    * Action Emil: Check with Kristian Sandahl about whether a co-location could be interesting to the Software Center folks.
    * Action Emil: Check with Erik Sternersson if doWhile can host.
    * Action Emil: Check with Bo Palmblad if he can help out with hosting at Ericsson Lindholmen.
    * If Gothenburg doesn't work out let's try to do something in Linköping or Lund instead, in the same timeframe.
* Updates from CDF sig-events, Emil & Mattias
    * Incident events will probably be part of the next release (0.2).
    * Linking being discussed under the "connected events" moniker.
    * Decision: Next week's community meeting will focus on event linking and CDevents.
* Out of time, postponed: Eiffel vision/mission - related to [community issue 190](https://github.com/eiffel-community/eiffel/issues/190)
    * How to continue from last weeks extra TC meeting?
* Out of time, postponed: At the summit we talked about describing relationships between artifacts. Was there an issue filed for this? Should there be one?
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: Common [branching strategy](https://github.com/eiffel-community/community/issues/150)?
* Out of time, postponed: GitHub projects can now define [roadmaps](https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/) - do we want to use such?
* Out of time, postponed: PRs and issues 

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* ~~TC: Investigate if we can obtain legal assistance from Software Center.~~
    * ~~Update 2023-02-06: Emil and Mattias might know something more about this now.~~
    * ~~Update 2023-02-09: We won't pursue this further. Software Center won't be able to offer legal support.~~
* Emil: Send invite for separate meeting to discuss event linking vs. CDevents.
* Emil: Ask Frank at EST to get an updated list of contributors from EST's Bitergia tool.

### February 2, 2023

(Extra TC meeting)

#### Participants

* TC Attendees
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, not present

#### Agenda and Notes
* Rollcall, All
    * We have quorum.
* Appoint election officers
    - Fatih Degirmenci and Fredrik Fristedt have accepted to be Election Officers for a one-year term ending 2024-02-02.
    - https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw#Eiffel-Technical-Committee-Elections-2023
    - Emil: Reach out to them to start by setting the timeline and come back to TC to present it when done
* https://github.com/eiffel-community/eiffel/pull/343 - Did we say step major version for experimental link types
    * Mattias will approve it now.
    * Magnus will consider it one more night before submitting it.
* Discuss issue Eiffel vision/mission - https://github.com/eiffel-community/eiffel/issues/190
    * Compare to distributed tracing. Where do we draw the line? Should there be a spanId attribute in one of the activity events? Should we express an opinion on how deep down in the stack Eiffel should be used (build-as-a-service example)?
    * How far towards the ops space (incidents etc)?
    * Resource monitoring was used an example of what not to cover, but why not? A possible rule that _might_ work is that events that are _only_ useful outside the pipeline but never within the pipeline shouldn't be part of Eiffel. That at least applies to the resource monitoring example. However, Eiffel can include references to where consumers can find resource usage data.
    * Eiffel should be used for events/occurences, not "current status/state".
* Postponed to next weeks TC meeting: Info project now have roadmaps - https://github.blog/changelog/2023-01-31-roadmap-in-projects-public-beta/


### January 25, 2023

#### Participants

* TC Attendees
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
    * The TC GitHub project: https://github.com/orgs/eiffel-community/projects/3/views/4
* Updates from CDF sig-events, Emil & Mattias
    * There was a meeting between CDEvents and folks from an interoperabiltiy subgroup of [Value Stream Management Consortium](https://www.vsmconsortium.org/) community. The VSM group will run a meeting series on this topic.
    * Incident events are being discussed and will probably be included in the next release. This would enable DORA metrics.
* TC elections
    * [Elections document](https://hackmd.io/6x1Ef5Y_RWqaOmytMeYVKw) (synced to GitHub)
    * Election Officers: Emil will ask Fatih. Magnus will ask Fredrik or others at Axis. Next week's extra meeting will appoint the person's we've found.
    * What should the timeline be?
        * The newly appointed election officers will be asked to revise the time plan and present it at the Feb 9 TC meeting.
* What happened with [github.com/eiffel-community/eiffel#190](https://github.com/eiffel-community/eiffel/issues/190)?
    * Ties in with the mission/vision. Will be discussed at next week's extra TC meeting.
* Eiffel repo naming regarding 
[github.com/eiffel-community/community#162](https://github.com/eiffel-community/community/issues/162) and [github.com/eiffel-community/community#161](https://github.com/eiffel-community/community/issues/161)
    * Relates to the names of SDK repos as well - eiffelevents-sdk-
    * Currently proposed names (eiffel-demo-cdevents and eiffel-translator-cdevents) were approved.
    * Emil to create PR to finish the project creation through community repo documents
* Do we all know about eventcatalog? E.g the part on events https://www.eventcatalog.dev/docs/events/introduction
    * Might be usable when publishing Eiffel event documentation on github.io.
* Out of time, postponed: At the summit we talked about describing relationships between artifacts. Was there an issue filed for this? Should there be one?
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: [Common branching strategy?](https://github.com/eiffel-community/community/issues/150)
* Out of time, postponed: PRs and issues 

#### Action Items
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* TC: Investigate if we can obtain legal assistance from Software Center.
* Emil: Send invite for separate meeting to discuss event linking vs. CDevents.
    * Update 2022-12-12: https://www.when2meet.com/?17987352-Gk4R3

### January 11, 2023

#### Participants

* TC Attendees
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
    * The TC GitHub project: https://github.com/orgs/eiffel-community/projects/3/views/4
* Updates from CDF sig-events, Emil & Mattias
    * 0.2 still slated for mid-February.
    * Mattias and Emil will attend KubeCon in Amsterdam in April.
* Plan [next week's community meeting](https://hackmd.io/fdXgYppfTYa5ObGuGd0ghw)
* Out of time, postponed: Reasoning about events as being in the traceability dimension or the activity dimension; should we document this and how?
* Out of time, postponed: [Common branching strategy?](https://github.com/eiffel-community/community/issues/150)
* Out of time, postponed: PRs and issues

#### Action Items
* ~~Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation~~
    * ~~[Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.~~
    * ~~Update 2021-08-12: Question sent to Fatih but no reply yet.~~
    * ~~Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.~~
    * ~~Update 2021-10-07: Cluster running, access control situation unclear.~~
    * ~~Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.~~
    * ~~Update 2022-01-27: Probably simple to fix, Tobias to ping Robert at Nordix.~~
    * ~~Update 2022-02-17: Tobias has pinged Robert. Waiting for response.~~
    * ~~Update 2022-09-29: Robert has promised to fix the problem this month.~~
    * ~~Update 2022-11-03: Emil and Mattias will talk to Nordix.~~
    * ~~Update 2022-11-17: New Nordix contact established.~~
    * ~~Update 2022-12-01: We now have access to a k8s cluster via a jumphost. No inbound access from the internet though.~~
    * ~~This is followed up as an issue - https://github.com/eiffel-community/community/issues/75~~
* ~~TC: Add all TC members to all existing Eiffel Google groups~~
    * ~~Update 2022-12-12: With what role? See also https://github.com/eiffel-community/community/pull/155~~
    * ~~It was decided on 2022-12-12 TC meeting to deprecate mailing lists.~~
    * ~~Draft issue for deprecation created.~~
* TC: Look into proposal made in the maintainer role presentation from the 2021 summit.
* Magnus: Collect feedback from the Python Podcast.\_\_init\_\_ interview to see if there are concrete steps we can take to improve how things are presented or explained.
* Magnus: Go through current action list and suggest which should be migrated to issues in the community repo.
* Magnus: Announce podcast episode on LinkedIn.
* TC: Investigate if we can obtain legal assistance from Software Center.
* Emil: Send invite for separate meeting to discuss event linking vs. CDevents.
    * Update 2022-12-12: https://www.when2meet.com/?17987352-Gk4R3
* ~~Emil: Update Jan 19 community meeting invite to state the topic. On the Jan 12 TC meeting we'll decide which issues to actually talk about.~~
* ~~Magnus: Follow [checklist](https://github.com/eiffel-community/community/blob/master/howtos/introduction-of-a-new-tc-member.md) to revert authorities for Azeem.~~
* ~~Emil: Create a project board for the protocol to handle priorities for the protocol issues. Readable by all in the community and writeable by protocol maintainers.~~
    * ~~**Update 2023-01-10:** https://github.com/orgs/eiffel-community/projects/6~~
