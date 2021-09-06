# Technical Committee Meetings 2021

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2021-08-26 Meeting](#August-26-2021)
    * [2021-08-12 Meeting](#August-12-2021)
    * [2021-07-01 Meeting](#July-1-2021)
    * [2021-06-17 Meeting](#June-17-2021)
    * [2021-06-03 Meeting](#June-3-2021)
    * [2021-05-20 Meeting](#May-20-2021)
    * [2021-05-06 Meeting](#May-6-2021)

## Logistics

* **When:** 13:00 - 14:00 CET, every even week on Thursdays
* **Where:** [Microsoft Teams Meeting](https://teams.microsoft.com/l/meetup-join/19%3ameeting_MDljZGI1ZDEtOGRhYS00NzlmLTlkZTgtNTM4OGMwNmU3ZTVh%40thread.v2/0?context=%7b%22Tid%22%3a%22d2585e63-66b9-44b6-a76e-4f4b217d97fd%22%2c%22Oid%22%3a%22b5142d0f-6dad-4704-99f5-29b74621c34a%22%7d)
* **Meeting Agenda and Minutes:** https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ
* **Community Repo:** https://github.com/eiffel-community/community

## Agenda and Notes

Please do not update the meeting agenda and notes directly on GitHub and instead use the document on [HackMD.io](https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ) in order to prevent notes getting out of sync.

### August 26, 2021

#### Participants

**TC Attendees**

* David Westberg, present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linnér, present
* Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
* Approval of Previous Minutes, All
    * Approved
* Agenda Bashing, All
    * Approved
* Action Item Review, All
* Update from the interview with The New Stack
    * Magnus Bäck was interviewed by Joab Jackson on Aug 3. Waiting for article to be published.
* Updates from CDF sig-events
    * There have been discussions about whether the new protocol should be a standard or a project. Cloud Events is a project.
    * How should subscriptions work in a global context? A message broker works within a company but not across the whole internet. Webhooks?
* Summit preparations status
    * Emil: Send follow-up meeting next Thursday at 13:00 CET
    * Mattias's PR that adds the agenda to https://eiffel-community.github.io/summit.html looks generally good and will be published shortly.
* How do we handle images? Should we upload originals or just the svg?
    * Moving this topic to next meeting
* PRs and issues
    * Landscape PR

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
* Magnus: Present Go package when it's available.
* Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* Magnus: Check if it is possible to restrict accesses to repos in eiffel community from organization owners. Today we can merge PRs in any repo even if we are not maintainers explicitly.
* Mattias: Ask the community about ways to handle our graphics (in e.g. Sepia and protocol repos)

### August 12, 2021

#### Participants

**TC Attendees**

* David Westberg, present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linnér, present
* Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
* Approval of Previous Minutes, All
* Agenda Bashing, All
* Action Item Review, All
* Updates from CDF sig-events
    * A PoC exists with event communication between Keptn and Tekton
    * Naming discussion ongoing for the new protocol
* Preparing for the [Lyon edition](https://github.com/eiffel-community/eiffel/milestone/6)
    * Intention is to present both Paris and Lyon on the upcoming Eiffel Summit
* Maintainer role
    * This is a carry-over item form the July 1 meeting. It's not entirely clear what we intended to discuss at this meeting :-/
    * Proposed to be discussed further on the summit
    * Action created to check possibility to restrict access for TC board members to some repos
* The [Proposed routing key schema](https://github.com/eiffel-community/eiffel-sepia/issues/8) issue has a concrete suggestion on how to move forward.
    * We seem to be aligned with Magnus last comment. The PR will be updated. Family will be a free text field.
* How do we handle images? Should we upload originals or just the svg?
    * We should ask if anyone in the community has any input to this. Which format to use/save, and should we inline svg data in html files or not? Action: Mattias
* PRs and issues

#### Action Items
* ~~Mattias to publish API for ER~~
    * ~~[Eiffel event repository #12](https://github.com/eiffel-community/eiffel-event-repository/pull/12) (to see it rendered checkout the preview link in the PR) - Done~~
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
* Magnus: Present Go package when it's available.
* ~~Magnus: Add discussion item about the maintainership role in the agenda for an upcoming TC meeting.~~
* ~~Magnus: Check max length of routing key for RabbitMQ queue bindings and max number of bindings for a queue. Add findings to the [Proposed routing key schema](https://github.com/eiffel-community/eiffel-sepia/issues/8) issue.~~
* Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* Magnus: Check if it is possible to restrict accesses to repos in eiffel community from organization owners. Today we can merge PRs in any repo even if we are not maintainers explicitly.
* Mattias: Ask the community about ways to handle our graphics (in e.g. Sepia and protocol repos)

### July 1, 2021

#### Participants

**TC Attendees**

* David Westberg, present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linnér, not present
* Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum
* Approval of Previous Minutes, All
    * Approved
* Agenda Bashing, All
    * Approved
* Action Item Review, All
* Updates from CDF sig-events and cdCon
    * 4000 had signed up for cdCon.
    * PoC of new event protocol not available as a demo. Should be available later.
    * Some recordings available but so far basically just keynotes.
    * Recommended: https://www.youtube.com/watch?v=U9H--2G-yNM
* Which repositories should be handled in the TC meetings? To which extent should maintainership of repos be coupled to the TC members?
    * Candidates:
        * eiffel-sepia
        * community
        * .github
        * eiffel-community.github.io
    * We should be maintainers of all community-tagged repos under github.com/eiffel-community.
    * In addition to the community repos we should keep a close eye on the key repos eiffel and eiffel-sepia.
    * Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* PRs and issues
    * [Proposed routing key schema](https://github.com/eiffel-community/eiffel-sepia/issues/8) was discussed but without conclusion. 
        * Magnus: Look into what limitations RabbitMQ has on the length of a routing key and the number of bindings for a queue.
* Contents of Eiffel Summit 2021.1
    * Add wanted topics to https://hackmd.io/1rcrNty5RFWVhoeV2isdXA.
* Gather list of suitable summer tasks when we have partially overlapping vacations
    * [SPDX](https://spdx.dev/) has Eiffel-adjacent features and it would useful to look into it to see if we can interoperate with them.
    * Otherwise no particular tasks were identified.

#### Action Items
* Mattias to publish API for ER
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
* Magnus: Present Go package when it's available.
* ~~Emil/Mattias: Send invite to August 19 summit planning.~~
* Magnus: Add discussion item about the maintainership role in the agenda for an upcoming TC meeting.
* Magnus: Check max length of routing key for RabbitMQ queue bindings and max number of bindings for a queue. Add findings to the [Proposed routing key schema](https://github.com/eiffel-community/eiffel-sepia/issues/8) issue.

### June 17, 2021

#### Participants

**TC Attendees**

* David Westberg, present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linnér, present
* Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
    * All present, we have quorum
* Approval of Previous Minutes, All
    * Approved
* Agenda Bashing, All
    * Approved
* Action Item Review, All
* TC meetings during the summer
    * Last TC meeting before vacations on July 1.
    * Reconvene on August 12.
* [Restructuring of meeting minutes PR](https://github.com/eiffel-community/community/pull/100)
    * Approved, will be merged shortly.
* Updates from CDF sig-events
    * New protocol being designed within the SIG.
    * Aims to produce PoC prior to cdCon so that Keptn and Tekton can communicate.
    * Emil speaks at cdCon on June 23. There's also a BoF session that he co-chairs. There are few other sessions directly related to events.
* Contents of Eiffel Summit 2021.1
    * We should have a session to describe the Eiffel landscape, possibly based on Sepia or the [CDF landscape](https://landscape.cd.foundation/images/landscape.png).
* [Proposed routing key schema](https://github.com/eiffel-community/eiffel-sepia/issues/8)
    * No conclusion. Continue discussion on GitHub and on next TC meeting.
* Monthly Eiffel meetings
    * Follow-up of last meeting's discussion about having a monthly meeting for presentations, discussions, or workshops.
    * First meeting will be August 19, focusing on setting the agenda of the summit.
    * Emil/Mattias to send invite to mailing list.
* Community [PRs](https://github.com/eiffel-community/community/pulls) and [Issues](https://github.com/eiffel-community/community/issues)
    * New repos proposed in [github.com/eiffel-community/community#99](https://github.com/eiffel-community/community/issues/99) and [github.com/eiffel-community/community#102](https://github.com/eiffel-community/community/issues/102). Both have been announced on the mailing list and are ready for review.
    * The proposed new issue template for lifecycle changes ([github.com/eiffel-community/community#101](https://github.com/eiffel-community/community/issues/101)) will require duplicatation of the template in the .github repo. A PR has been sent to migrate said repo to support multiple templates ([github.com/eiffel-community/.github#8](https://github.com/eiffel-community/.github/issues/8)).

#### Action Items
* Mattias to publish API for ER
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
* Magnus: Present Go package when it's available.
* ~~Emil/Mattias: Send PR for updating eiffel-community.github.io with information about the September summit.~~
    * ~~https://github.com/eiffel-community/eiffel-community.github.io/pull/20~~
* ~~Magnus: Update next meeting's agenda with item about discussing the content of the summit.~~
* Emil/Mattias: Send invite to August 19 summit planning.

### June 3, 2021

#### Participants

**TC Attendees**

* David Westberg, not present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linnér, present
* Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
    * We have quorum
* Approval of Previous Minutes, All
    * Approved
* Agenda Bashing, All
    * Approved
* Action Item Review, All
* Eiffel summit autumn 2021
    * Proposed days for all-remote summit: September 29–30
        * Not weekend-adjacent to decrease risk of people being on vacation.
        * Near the end of the month to give prep time after the summer vacations.
        * Hopefully sufficiently late after the start of school semesters to minimize risk of illness among attendees or their children.
    * Proposed dates collide with DevOps World. How about September 22–23 instead?
        * Yes, suggest to community.
        * Action: Emil to send invite.
        * Action: Emil/Mattias to send PR for updating eiffel-community.github.io.
        * Action: Magnus to update next meeting's agenda with item about discussing the content of the summit.
* Presentations on coming TC meetings, or outside TC meetings?
    * Decision: Monthly meeting the same time as the TC meeting. Can be used for e.g. presentations or workshops. Bring up at next meeting to finalize.
* Are there any examples of using Eiffel to actually orchestrate a pipeline execution rather than just observing the results? (Magnus)
    * Yes, Ericsson does this with a Jenkins plugin that can trigger builds based on events.
* We don't have comprehensive Eiffel event data type libraries in any language, i.e. data types that not only make it easy to produce correct events (we have those for at least Python and Java) but also allows deserialization of events received on the bus. Should we work out recommendations for the interfaces of such libraries? For example, how should we handle deserializing different major versions of events? (Magnus)
    * Action: Magnus to present Go package when it's available and we'll see if there are ideas that can be applied to libraries for other languages.
* Eiffel protocol workshop outcome (Magnus)
    * The workshop was appreciated and should be repeated when necessary.
* Community [PRs](https://github.com/eiffel-community/community/pulls) and [Issues](https://github.com/eiffel-community/community/issues)
    * [github.com/eiffel-community/community#101](https://github.com/eiffel-community/community/issues/101) was met with general approval. Unclear how the introduction of a new-style template in the community repo will interact with the legacy templates in the .github repo.
    * Reviews of [github.com/eiffel-community/community#99](https://github.com/eiffel-community/community/issues/99) and [github.com/eiffel-community/community#102](https://github.com/eiffel-community/community/issues/102) are encouraged.
* New [project-lifecycle label](https://github.com/eiffel-community/community/issues?q=label%3Aproject-lifecycle) in the [community repository](https://github.com/eiffel-community/community) (Magnus)
    * The new label met general approval.

#### Action Items
* ~~Mattias to help David to be part of the HackMD team~~
    * ~~https://hackmd.io/team/eiffel-community/manage#members~~
* Mattias to publish API for ER
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
* ~~TC Chairs: PR on GOVERNANCE.md to state the new chairs of the TC~~
* ~~Update community owners list https://github.com/orgs/eiffel-community/people?query=role%3Aowner as decided~~
    * ~~Decision: Add TC members. Keep current members as owners except for inactive owners who has not been active lately.~~
* ~~Chair: Prepare suggestion on how to restructure meetings documents~~
    * ~~PR exists: https://github.com/eiffel-community/community/pull/100~~
* ~~Magnus: Prepare proposal for Eiffel summit autumn 2021~~
    * ~~Done, included in this meeting's agenda.~~
* Magnus: Present Go package when it's available.
* Emil/Mattias: Send PR for updating eiffel-community.github.io with information about the September summit.
* Magnus: Update next meeting's agenda with item about discussing the content of the summit.

### May 20, 2021

#### Participants

**TC Attendees**

* David Westberg, present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linner, present
* Tobias Persson, present

**Community Attendees**
* \<add me\>

#### Agenda and Notes
* Rollcall, All
    * We have Quorum
* Approval of Previous Minutes, All
    * Minutes are approved
    * Restructure meetings documents
        * Create community/docs for meeting docs and link them from top level MEETINGS.md?
        * We didn't conclude the next step for this
        * TC Chair: Make a suggestion to next TC meeting
* Agenda Bashing, All
* Action Item Review, All
* Who are we in the TC, and how do we use Eiffel today? All
    * Add a few sentences to some public document describing each one of us?
        * Decision: We don't write any such document yet. We have more important things to document.
* https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ is writable for everyone even non signed in persons. Should we at least update the note so that you have to be signed in to edit it?
    * Emil: I already made this update. Ok that all signed in users can edit?
    * Done
* The TC currently has filled 5 of the 7 seats. Do we want to try to get more people on the TC?
    * No action: We don't see the possibility to find people from more companies for the moment.
* Eiffel summit autumn 2021?
    * Yes, we want to setup a summit. Preferrably physical, but we might not be able to make that.
    * For the future we see that we would like to have 2 summits per year - one physical and one digital
    * And recurring meetings to discuss top topics (Issues/PRs, etc)
    * Suggested setup for 2021 autumn summit:
        * Virtual
        * 2 days?
        * 1st day for all interested in Eiffel, with high level presentations
        * 2nd day for current users, with in-depth discussions/presentations on Eiffel topics
        * September?
        * Magnus: Start planning for this before next TC meeting
    * Plan for a physical summit early 2022?
* Presentations on coming TC meetings, or outside TC meetings?
    * Not discussed, postponed to next meeting
* Are there any examples of using Eiffel to actually orchestrate a pipeline execution rather than just observing the results? (Magnus)
    * Not discussed, postponed to next meeting
* We don't have comprehensive Eiffel event data type libraries in any language, i.e. data types that not only make it easy to produce correct events (we have those for at least Python and Java) but also allows deserialization of events received on the bus. Should we work out recommendations for the interfaces of such libraries? For example, how should we handle deserializing different major versions of events? (Magnus)
    * Not discussed, postponed to next meeting
* Community [PRs](https://github.com/eiffel-community/community/pulls) and [Issues](https://github.com/eiffel-community/community/issues)
    * Not discussed, postponed to next meeting
* \<add item\>

#### Action Items
* ~~Mattias to update GOVERNANCE.md to state that a majority of maintainers for the community repo needs to approve any PR in that repo.~~
    * ~~[Mattias] - https://github.com/eiffel-community/community/pull/96~~
* Mattias to help David to be part of the HackMD team
    * https://hackmd.io/team/eiffel-community/manage#members
* Mattias to publish API for ER
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
* ~~Mattias: Update Governance document to state that two equal chairs are heading the TC. Make this PR separate from the other one MattiasMattias: Update Governance document to state that two equal chairs are heading the TC. Make this PR separate from the other one Mattias~~
    * ~~[Mattias] - https://github.com/eiffel-community/community/pull/97~~
* ~~TC Chairs: Mail the outcome of this TC meeting to the community~~
* TC Chairs: PR on GOVERNANCE.md to state the new chairs of the TC
* ~~Emil: Send meeting invite to TC meetings~~
* Update community owners list https://github.com/orgs/eiffel-community/people?query=role%3Aowner as decided
    * Decision: Add TC members. Keep current members as owners except for inactive owners who has not been active lately.
* Chair: Prepare suggestion on how to restructure meetings documents
* Magnus: Prepare proposal for Eiffel summit autumn 2021


### May 6, 2021

#### Participants

**TC Attendees**

* David Westberg, present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linner, present
* Tobias Persson, present

**Community Attendees**
* Fatih Degirmenci

#### Agenda and Notes
* Rollcall, All
    * We have Quorum
* Approval of Previous Minutes, All
    * Minutes are approved
* Agenda Bashing, All
* Action Item Review, All
    * New Eiffel TC to decide who should be owners of Eiffel Community on GitHub - https://github.com/orgs/eiffel-community/people?query=role%3Aowner
        * Proposal: All in Eiffel Community TC should be the owners
        * Decision: Add TC members. Keep current members as owners except for inactive owners who has not been active lately.
* 2021 TC Chair Election, All
    * Agree: The topic to determine the TC Chair for elected TC will be discussed during the next Eiffel TC Meeting - TBD by new TC
    * Two equal chairs is wanted. Update to Governance document is needed.
    * Decision: Magnus Bäck and Emil Bäckmark are the TC chairs.
* Next meeting time
    * Frequency
        * Decision: TC meetings are held every two weeks
    * Date/time for next meeting
        * Decision: Keep every second Thursday at 13.00 CE(S)T. Next meeting on May 20th.
* Are these meetings open to all? If so how do we spread the word? - Mattias
    * Yes, they are open to all community member
    * Informed through mail from TC chairs a few days in advance of each TC meeting
* Are issues always needed for PRs in Eiffel repos?
    * To be discussed next meeting
* Eiffel protocol workshop to be held
    * May 27th. A mail has been sent out to the community about it.

#### Action Items
* ~~New Eiffel TC to decide who should be owners of Eiffel Community on GitHub~~ - ~~https://github.com/orgs/eiffel-community/people?query=role%3Aowner~~
    * ~~Moved to today's agenda~~~~
* ~~Emil to update the governance document and list the elected TC members~~
    * ~~DONE: Update is done as part of https://github.com/eiffel-community/community/pull/95 as suggested on https://github.com/eiffel-community/community/issues/90#issuecomment-824774647~~
    * ~~PR exists~~
* ~~Henning to update eiffel-community maintainers list on Eiffel Community organization on April 23rd and add elected TC Members.~~ ~~Edit by Henning 2021-04-23: Done!~~
* Mattias to update GOVERNANCE.md to state that a majority of maintainers for the community repo needs to approve any PR in that repo.
    * [Mattias] - https://github.com/eiffel-community/community/pull/96
* ~~Fatih to remove bootstrap process - https://github.com/eiffel-community/community/issues/90 on April 23rd~~
    * ~~DONE: PR opened: https://github.com/eiffel-community/community/pull/95~~
* ~~Fatih to send mail to Eiffel Maillist, announcing the new TC with the date the TC assume their seats~~
    * ~~DONE: Mail sent: https://groups.google.com/g/eiffel-community/c/G6uDgkwurdE/m/wnQfGDzHAQAJ~~
* ~~Fatih to close election process on GitHub - https://github.com/eiffel-community/community/issues/87~~
    * ~~DONE: Issue closed: https://github.com/eiffel-community/community/issues/87~~
* Fatih to add the elected TC to Eiffel HackMD team
    * DONE: https://hackmd.io/team/eiffel-community/manage#members
    * David is not yet a member
* ~~Emil to send invitation for the next Eiffel TC Meeting if a better time is determined.~~
* ~~Henning and Fatih to work on clarifying how the eligibility is determined in governance document, CODEOWNERS vs mainateiners groups. Edit by Henning 2021-04-23: PR submitted for review (https://github.com/eiffel-community/community/pull/94)~~
* ~~TC to discuss whether to adapt co-chair setup after the new TC is seated. Part of the agenda for today~~
* Mattias to publish API for ER
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
* Mattias: Update Governance document to state that two equal chairs are heading the TC. Make this PR separate from the other one Mattias
    * [Mattias] - https://github.com/eiffel-community/community/pull/97
* TC Chairs: Mail the outcome of this TC meeting to the community
* TC Chairs: PR on GOVERNANCE.md to state the new chairs of the TC
* Emil: Send meeting invite to TC meetings
* Update community owners list https://github.com/orgs/eiffel-community/people?query=role%3Aowner as decided
