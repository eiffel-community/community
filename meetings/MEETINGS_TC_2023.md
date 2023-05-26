###### tags: `Technical Committee`

# Technical Committee Meetings 2023

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
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

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/sL9z7MGwSCOGSCXeY27mFg) in order to prevent notes getting out of sync.

### Next

...

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
