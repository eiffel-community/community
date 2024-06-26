###### tags: `Technical Committee`

# Technical Committee Meetings 2021

[![HackMD documents](https://hackmd.io/badge.svg)](https://hackmd.io/SCImga0nS1qSh3QvsEOAVQ)

## Quick links

* [Logistics](#logistics)
* [Agenda and Notes](#agenda-and-notes)
    * [2021-12-16 Meeting](#December-16-2021)
    * [2021-12-02 Meeting](#December-02-2021)
    * [2021-11-18 Meeting](#November-18-2021)
    * [2021-11-04 Meeting](#November-4-2021)
    * [2021-10-21 Meeting](#October-21-2021)
    * [2021-10-07 Meeting](#October-7-2021)
    * [2021-09-09 Meeting](#September-9-2021)
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

### Next meeting
- Set agenda for community meeting on source change events

### December 16, 2021

#### Participants

* TC Attendees
    * David Westberg, not present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, not present

#### Agenda and Notes
* Rollcall, All
    * Ok
* Approval of Previous Minutes, All
    * Approved
* Agenda Bashing, All
    * Approved
* Action Item Review, All
* Updates from CDF sig-events
* Python podcast follow-up
    * To be scheduled in January
* Log4j vulnerability
    * We don't see that any Eiffel Community repo is directly affected. Updates to later log4j is introduced anyway in some repo.
* Summit planning
    * We don't plan for a physical summit yet, due to the situation with the pandemic
    * We don't yet plan for a virtual summit during the spring, due to lack of prepared items to discuss/present
    * A smaller physical community meetup / focused workshop might be held late spring 2022, but we don't plan for it yet
        * Source change events?
    * We should revisit this in February
* Community meetings
    * Outcome of SDK workshop
        * No further actions
    * Topic of next meeting (Feb 3)
        * Protocol workshop (source change events)
* When is next TC meeting?
    * Next ordinary TC meeting Jan 13th
* Eiffel Intelligence uses Travis-ci.com to run tests. They now only give open source projects 10000 credits (which you can request more of by mail). Do we have a recommendation on this? Should we announce it to all the community?
    * Should GitHub actions be used instead of Travis CI? See [summit recording](https://www.youtube.com/watch?v=x1P8Cydv_qA) and [mail from Fatih](https://groups.google.com/g/eiffel-community/c/a304uJu8BiY).
        * Yes, we should use GitHub actions default in all repos
    * Nordix?
        * Could maybe be relevant for more complicated or more resource demanding flows
        * We should publish images to Nordix even if we don't use it to execute CI pipelines
* --- No time to come further ---
* Deal with [summary/outcome](https://hackmd.io/QEwWwRlNQ8mYKXAQKOg16A#Session-recap) from the summit
* Go through https://github.com/orgs/eiffel-community/projects/3/views/1
* Show what Ericsson is prioritizing for developement https://github.com/orgs/eiffel-community/projects/2/views/1
* Should we add a readme for the organization for introduction. Would go into the .github repo. See https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile for more info and https://github.com/keptn-sandbox as an example.
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
* ~~Mattias: Define a GitHub "beta project" for TC and add all TC members to it.~~
    * ~~https://github.com/orgs/eiffel-community/projects/3/views/1~~
* Emil: Go through the discussions in the summit presentations and see if there are things we should create issues from or have monthly community meetings about.
* Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.
* Emil: Check how CDF's Google Calendar works.
* Magnus: Propose new policy of how to deal with the issue requirement for new development.
* Magnus: Continue examining consequences for JSON validation code when meta is extracted to a separate file.
* Magnus: Write script for creating single-file schema files from multi-file schemas.
* Magnus: Process for how to lift event versions when meta object is updated needs to be added to the protocol meta PR. Ask Sven to do it?
    * https://github.com/eiffel-community/eiffel/issues/279
* ~~Emil: Update SDKs community meeting invite after Magnus has written the agenda~~
* Emil: Check admin access to YouTube channel. Could all TC members be admins? Or should we all have access to a (new?) admin Google account?
* Mattias/Emil/David: Set up 2FA for your account on the GitHub organization, https://github.com/orgs/eiffel-community/people?query=role%3Aowner
* TC: Write issue about archiving projects and do archive eiffel-remrem-shared
    * remrem-shared: https://github.com/eiffel-community/eiffel-remrem-shared/issues/30
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Amend the repo creation checklist in the eiffel-repository-template repo to state that TC members should be added as owners to any created Google Groups.
* TC: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* ~~Magnus: Contact Daniel Ståhl about Python podcast.~~
* TC: Add recommendation to not use force pushes to code review guidelines.
* Emil/Magnus: Revisit summit planning first half of February.

### December 02, 2021

#### Participants

* TC Attendees
    * David Westberg, not present
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
* Updates from CDF sig-events
    * CD Events is now accepted as a CDF Incubating project
    * Some people of today's SIG Events will be the bootstrap TC for CD Events, preparing for elections of a formal TC
* All set for next weeks monthly meeting?
    * Promote on Slack
    * Emil to send updated invite
* How do we deal with dead repos, to be deleted or archived
    * Example: [github.com/eiffel-community/eiffel-remrem-shared#30](https://github.com/eiffel-community/eiffel-remrem-shared/issues/30)
    * We should archive any dormant repository. After a number of months we can then delete them
    * Action on archive:
        * Update projects.md with status archive
        * Change badge in README and state that project is archived in READMEd text
        * Close ALL open PRs and issues
        * Update repo settings since they cannot be changed afterwards. Set them to...? (Find out what by archiving eiffel-remrem-shared)
        * Archive project
    * Update instruction in Lifecycle with previous tasks
* Mail groups
    * Should TC members be part owners of all the Google groups mailing lists?
        * Yes. TC members should be individual owners of each Eiffel connected Google group.
        * Add this to repo checklist https://github.com/eiffel-community/eiffel-repository-template/blob/master/repo-checklist.md
        * Add all TC members to all existing Eiffel Google groups
        * Add TC members mail addresses to the GOVERNANCE document (in the table of TC members)
    * If not how do we see to it that we don't just have one owner who disappears?
    * Action created and end-of-discussion.
* The Community Monthly Meeting in January falls on Epiphany (public holiday)
    * We'll cancel this meeting. Emil will cancel it.
* Participate in the Python-podcast?
    * Magnus will participate. Magnus will contact Daniel and Tobias (Python) on that.
* PR updates and use of force push. Harder to review but easier to merge. What is our take on it?
    * The larger the PR the more important it is to not use force push (for the sake of the reviewer)
    * As soon as reviewers are invited to a PR no more force pushes should be done
    * We should document this as a recommendation on https://github.com/eiffel-community/.github/blob/master/CONTRIBUTING.md
* Eiffel Intelligence uses Travis-ci.com to run tests. They now only give open source projects 10000 credits (which you can request more of by mail). Do we have a recommendation on this? Should we announce it to all the community?
    * Should GitHub actions be used instead of Travis CI? See [summit recording](https://www.youtube.com/watch?v=x1P8Cydv_qA) and [mail from Fatih](https://groups.google.com/g/eiffel-community/c/a304uJu8BiY).
* Deal with [summary/outcome](https://hackmd.io/QEwWwRlNQ8mYKXAQKOg16A#Session-recap) from the summit
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
* ~~Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?~~
* Mattias: Define a GitHub "beta project" for TC and add all TC members to it.
    * https://github.com/orgs/eiffel-community/projects/3/views/1
* Emil: Go through the discussions in the summit presentations and see if there are things we should create issues from or have monthly community meetings about.
* Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.
* ~~Emil/Magnus: Add summit planning to future TC meeting agenda.~~
* Emil: Check how CDF's Google Calendar works.
* Magnus: Propose new policy of how to deal with the issue requirement for new development.
* Magnus: Continue examining consequences for JSON validation code when meta is extracted to a separate file.
* Magnus: Write script for creating single-file schema files from multi-file schemas.
* Magnus: Process for how to lift event versions when meta object is updated needs to be added to the protocol meta PR. Ask Sven to do it?
* ~~Magnus: Prepare the Hackmd document including agenda for the community meeting on SDKs~~
* Emil: Update SDKs community meeting invite after Magnus has written the agenda
* ~~All? Promote the next community meeting on Slack.~~
* ~~Mattias: Prepare a PR for the updated PR review requirements, considering differences for graduated/non-graduated projects and more, as discussed on Nov 18th.~~
    * ~~https://github.com/eiffel-community/.github/pull/12~~
* Emil: Check admin access to YouTube channel. Could all TC members be admins? Or should we all have access to a (new?) admin Google account?
* Mattias/Emil/David: Set up 2FA for your account on the GitHub organization, https://github.com/orgs/eiffel-community/people?query=role%3Aowner
* TC: Write about archiving projects and do archive eiffel-remrem-shared
* TC: Add all TC members to all existing Eiffel Google groups
* TC: Amend the repo creation checklist in the eiffel-repository-template repo to state that TC members should be added as owners to any created Google Groups.
* TC: Add TC members' email addresses to the GOVERNANCE document (in the table of TC members).
* Magnus: Contact Daniel Ståhl about Python podcast.
* TC: Add recommendation to not use force pushes to code review guidelines.

### November 18, 2021

#### Participants

* TC Attendees
    * David Westberg, not present
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
    * CD Events might become a CDF flagship project. Probably launched around Jan/Feb 2022.
    * Referencing between events is being discussed and will probably be needed in one form or another before the CD Events project launch.
    * Use Cases for events in CI/CD systems is also being discussed and will help in promoting CD Events as a project
* Outcome from previous monthly community meeting
    * Linking ActT to SCC for retriggering put on hold until general activity linking using PRECURSOR is decided.
    * Meta discussion
        * Magnus: Process for how to lift event versions when meta object is updated needs to be added to the PR. Ask Sven to do it?
        * Magnus will check the validity of the proposal using various JSON validators
* Set and promote topic for next monthly meeting
    * SDKs!
    * Magnus: Prepare the Hackmd document including agenda for the meeting
    * Emil: Update invite after Magnus has written the agenda
    * Promote the meeting on Slack. After next TC meeting?
* How many reviewers should be needed per PR? Including author?
    * https://github.com/eiffel-community/.github/blob/master/CONTRIBUTING.md#reviewing-and-merging-pull-requests
        * Two maintainers (or org admin) need to approve a pull request. The author cannot approve it themselves.
        * Each repo needs at least 3 maintainers to fulfill this
        * Proposal: Change to something like "1. A Pull Request is recommended to be approved by at least two maintainers (including the one doing the merging). For this to function well, the above point on participation is critical. For graduated projects all PRs shall be approved be at least two maintainers from two different organizations."
            * Mattias: Prepare a PR for this.
* Should we add the TC mail as the billing mail in https://github.com/organizations/eiffel-community/settings/profile
    * Tobias: Yes, try setting the TC mail address (eiffel-tc@googlegroups.com) there, and also on https://github.com/organizations/eiffel-community/settings/billing
    * Admin access to YouTube channel.
        * Emil: To check what we can do there. Could all TC members be admins?
    * 2FA for all owners in the organization?
        * All TC members: Set this up for yourselves (https://github.com/orgs/eiffel-community/people?query=role%3Aowner)
* How do we deal with dead repos, to be deleted or archived
    * Example: [github.com/eiffel-community/eiffel-remrem-shared#30](https://github.com/eiffel-community/eiffel-remrem-shared/issues/30)
* Mail groups
    * Should TC members be part owners of all the Google groups mailing lists?
    * If not how do we see to it that we don't just have one owner who disappears?
* PR updates and use of force push. Harder to review but easier to merge. What is our take on it?
* Eiffel Intelligence uses Travis-ci.com to run tests. They now only give open source projects 10000 credits (which you can request more of by mail). Do we have a recommendation on this? Should we announce it to all the community?
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
* Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* ~~Mattias: Create checklists for new or removed TC members (e.g. granting/revoking access).~~
    * ~~https://github.com/eiffel-community/community/pull/119~~
* Emil: Go through the discussions in the summit presentations and see if there are things we should create issues from or have monthly community meetings about.
* Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.
* Emil/Magnus: Add summit planning to future TC meeting agenda.
* ~~Tobias: Add link to mailing list thread for monthly community meeting invite.~~
* ~~Magnus: Prepare introductory slides to give background on the meta breakout.~~
* Emil: Check how CDF's Google Calendar works.
* Magnus: Propose new policy of how to deal with the issue requirement for new development.
* ~~Emil: Ask JSON schema knowledgable person to review the meta extraction PR.~~
* Magnus: Continue examining consequences for JSON validation code when meta is extracted to a separate file.
* Magnus: Write script for creating single-file schema files from multi-file schemas.
* ~~Mattias: Add comment to [github.com/eiffel-community/eiffel#246](https://github.com/eiffel-community/eiffel/issues/246) about potential new TRIGGERED_BY link type.~~
* Magnus: Process for how to lift event versions when meta object is updated needs to be added to the protocol meta PR. Ask Sven to do it?
* Magnus: Prepare the Hackmd document including agenda for the community meeting on SDKs
* Emil: Update SDKs community meeting invite after Magnus has written the agenda
* All? Promote the next community meeting on Slack.
* Mattias: Prepare a PR for the updated PR review requirements, considering differences for graduated/non-graduated projects and more, as discussed on Nov 18th.
    * https://github.com/eiffel-community/.github/pull/12
* Emil: Check admin access to YouTube channel. Could all TC members be admins? Or should we all have access to a (new?) admin Google account?
* All: Set up 2FA for your account on the GitHub organization, https://github.com/orgs/eiffel-community/people?query=role%3Aowner


### November 4, 2021

#### Participants

* TC Attendees
    * David Westberg, not present
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
* Updates from CDF sig-events
    * Recent meeting had discussions about hierarchical activity events.
    * Artifact and composition events were also discussed.
* Next week's monthly community meeting
    * Feedback on [github.com/eiffel-community#287](https://github.com/eiffel-community/eiffel/pull/287)
    * Substructure breakout
    * Replace [github.com/eiffel-community#287](https://github.com/eiffel-community/eiffel/pull/287) discussion with general issue walkthrough.
* How do we handle images? Should we upload originals or just the svg?
    * Example from CDF - https://github.com/cdfoundation/artwork
    * Logos and event graphs and similar block diagrams should be treated separately.
    * Mattias to continue investigation.
* How do we deal with the requirement to reference issues in PRs for from-scratch development in a new repository?
    * We might need to be more pragmatic at times. E.g. when setting up a new repo and when fixing spelling errors.
    * General agreement that we should loosen the current policy but it wasn't immediately clear what the policy should be.
    * Magnus: Propose new policy.
* How many reviewers should be needed per PR? Including author?
    * Out of time, postponed.
* Should we add the TC mail as the billing mail in https://github.com/organizations/eiffel-community/settings/profile
    * Admin access to YouTube channel.
    * Out of time, postponed.
* How do we deal with dead repos, to be deleted or archived
    * Example: [github.com/eiffel-community/eiffel-remrem-shared#30](https://github.com/eiffel-community/eiffel-remrem-shared/issues/30)
    * Out of time, postponed.
* PRs and issues

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * ~~Action Emil: Ask Fatih to set up meeting to discuss k8s on Nordix infra.~~
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
* Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* ~~Mattias: Ask the community about ways to handle our graphics (in e.g. Sepia and protocol repos)~~
* Mattias: Create checklists for new or removed TC members (e.g. granting/revoking access).
    * https://github.com/eiffel-community/community/pull/119
* Emil: Go through the discussions in the summit presentations and see if there are things we should create issues from or have monthly community meetings about.
* Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.
* ~~Emil: Add HackMD document for monthly meetings (proposed topics and links to minutes for each meeting where available) and link to that document from https://github.com/eiffel-community/community/blob/master/meetings/README.md.~~
* Emil/Magnus: Add summit planning to future TC meeting agenda.
* ~~Emil: Upload the PPT from the 2021-10-14 community meeting to the community repo (https://github.com/eiffel-community/community/tree/master/presentations).~~
* ~~Emil: Write draft PR for the PRECURSOR addition so that we have a solid base for the discussion so that we can finalize the discussion at the next community meeting.~~
* Tobias: Add link to mailing list thread for monthly community meeting invite.
* Magnus: Prepare introductory slides to give background on the meta breakout.
* Emil: Check how CDF's Google Calendar works.
* Magnus: Propose new policy of how to deal with the issue requirement for new development.

### October 21, 2021

#### Participants

* TC Attendees
    * David Westberg, not present
    * Emil Bäckmark, present
    * Magnus Bäck, present
    * Mattias Linnér, present
    * Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
* Approval of Previous Minutes, All
    * Approved
* Agenda Bashing, All
    * Approved after adding "Should we have more frequent TC meetings?" item
* Action Item Review, All
* Should we have more frequent TC meetings?
    * Currently we have TC meetings every two weeks but we often don't have time to cover everything, particularly not issues and PRs.
    * Decision to use the monthly Thursday 13:00-14:00 slot that remains when regular TC meetings and the monthly community meeting have claimed their time. These meetings can be used to process issues or PRs or discuss other matters. First occasion is next week, Oct 28.
* Updates from CDF sig-events
* Summit reflections
    * [Takeaways](https://hackmd.io/QEwWwRlNQ8mYKXAQKOg16A)
    * Poll answers (Mattias) - https://hackmd.io/6EK7rwLdQpyxLKqBiU74Yw
    * Should decide date and form (digital or in person) before the end of the year. Follow up at TC meeting around the end of November.
* Takeaways from last monthly meeting (Oct 14)
    * MoM created: https://hackmd.io/jEiLclrrTaG5tPIBvrtRfg?both
    * How to proceed the discussion on CONTEXT/CAUSE/PRECURSOR?
* Choice of topic for Eiffel monthly meeting on Nov 11
    * Finalize CONTEXT/CAUSE/PRECURSOR discussion first hour, meta breakout second hour with coffee break in between.
    * SDK on Dec 9th, source change events on whatever monthly meeting that follows.
* Promote the monthly community meeting
    * Should we announce the monthly community meetings in more ways then just the mail list?
        * Announce on mailing list, Slack and LinkedIn three weeks ahead.
        * Post reminder on Slack and see if there's a good way of bumping the LinkedIn post for attention.
    * Should we document it on https://github.com/eiffel-community/community/tree/master/meetings - Yes
* How do we handle images? Should we upload originals or just the svg?
    * Example from CDF - https://github.com/cdfoundation/artwork
    * Out of time, postponed.
* How do we deal with the requirement to reference issues in PRs for from-scratch development in a new repository?
    * We might need to be more pragmatic at times. E.g. when setting up a new repo and when fixing spelling errors.
    * Out of time, postponed.
* How many reviewers should be needed per PR? Including author?
    * Out of time, postponed.
* Should we add the TC mail as the billing mail in https://github.com/organizations/eiffel-community/settings/profile
    * Admin access to YouTube channel.
    * Out of time, postponed.
* How do we deal with dead repos, to be deleted or archived
    * Example: [github.com/eiffel-community/eiffel-remrem-shared#30](https://github.com/eiffel-community/eiffel-remrem-shared/issues/30)
    * Out of time, postponed.
* PRs and issues
    * Out of time, postponed.

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * ~~Action Emil: Ask Fatih to set up meeting to discuss k8s on Nordix infra.~~
    * Update 2021-10-07: Cluster running, access control situation unclear.
    * Update 2021-10-21: Tobias and Mattias have SSH access to one of the hosts but we don't appear to have k8s access.
* Magnus: Present Go package when it's available.
    * PR with the most important functionality has been uploaded. Will present this at a future SDK monthly meeting so this AI will be closed.
* Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* Mattias: Ask the community about ways to handle our graphics (in e.g. Sepia and protocol repos)
* Mattias: Create checklists for new or removed TC members (e.g. granting/revoking access).
* Emil: Go through the discussions in the summit presentations and see if there are things we should create issues from or have monthly community meetings about.
* Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.
* Emil: Call for new TC monthly meeting.
* Emil: Add HackMD document for monthly meetings (proposed topics and links to minutes for each meeting where available) and link to that document from https://github.com/eiffel-community/community/blob/master/meetings/README.md.
* Emil/Magnus: Add summit planning to future TC meeting agenda.
* Emil: Upload the PPT from the 2021-10-14 community meeting to the community repo (https://github.com/eiffel-community/community/tree/master/presentations).
* Emil: Write draft PR for the PRECURSOR addition so that we have a solid base for the discussion so that we can finalize the discussion at the next community meeting.
* Magnus: Prepare introductory slides to give background on the meta breakout.
* Emil: Check how CDF's Google Calendar works.

### October 7, 2021

#### Participants

* TC Attendees
    * David Westberg, not present
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
* Updates from CDF sig-events
    * The new protocol has a name - "CD Events"
    * GitHub organization has been allocated and domain name discussions are ongoing.
    * The vocabulary discussions have e.g. concerned whether generic activity events or specific pipeline/build/step events should be used.
* Summit reflections
    * [Takeaways](https://hackmd.io/QEwWwRlNQ8mYKXAQKOg16A)
    * Poll answers (Mattias)
* Choice of topic for Eiffel monthly meeting on Oct 14
    * Protocol workshop focusing on [github.com/eiffel-community/eiffel#227](https://github.com/eiffel-community/eiffel/issues/227), i.e. how to express activity relationships, particularly hierarchical ones.
* PRs and issues
    * [github.com/eiffel-community/eiffel#277](https://github.com/eiffel-community/eiffel/pull/277) is the last PR up for review to complete the Lyon release.
* Landscape picture feedback, Mattias
    * Where in Sepia should this be placed? Any surrounding text needed?
    * Add landscape image to https://eiffel-community.github.io/community.html instead of the Sepia subpage (hosted in the Sepia repository).
* How do we deal with the requirement to reference issues in PRs for from-scratch development in a new repository?
    * We might need to be more pragmatic at times. E.g. when setting up a new repo and when fixing spelling errors.
    * Not enough time; postponed to next meeting.
* Anybody know about https://github.com/ItJustWorksTM/EiffelVis
    * Student project aiming to produce a blazingly fast Eiffel visualizer. Tobias and Ola Söder know more.
* Should we add the TC mail as the billing mail in https://github.com/organizations/eiffel-community/settings/profile
    * Not enough time; postponed to next meeting.
* How do we deal with dead repos, to be deleted or archived
    * Example: [github.com/eiffel-community/eiffel-remrem-shared#30](https://github.com/eiffel-community/eiffel-remrem-shared/issues/30)
    * Not enough time; postponed to next meeting.

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * ~~Action Emil: Ask Fatih to set up meeting to discuss k8s on Nordix infra.~~
    * Update 2021-10-07: Cluster running, access control situation unclear.
* Magnus: Present Go package when it's available.
* Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* Mattias: Ask the community about ways to handle our graphics (in e.g. Sepia and protocol repos)
* ~~Magnus: Do animations work when sharing the PPT?~~
* ~~Mattias/Emil: Prepare informational chat message that will be pasted at the start of every session at the summit.~~
* Emil: Update meeting invite for the 2021-09-16 monthy meeting to include the chosen topic.
* ~~Mattias: Announce the summit in the CDF slack.~~
* ~~Emil: Make sure all TC members can contribute videos.~~
* Mattias: Create checklists for new or removed TC members (e.g. granting/revoking access).
* Emil: Go through the discussions in the summit presentations and see if there are things we should create issues from or have monthly community meetings about.
* Magnus: Prepare examples, event diagrams etc for the proposed source change events together with Sven Selberg and Tobias. That material can form the basis of source change discussions in an upcoming monthly community meeting.

### September 9, 2021

#### Participants

**TC Attendees**

* David Westberg, not present
* Emil Bäckmark, present
* Magnus Bäck, present
* Mattias Linnér, present
* Tobias Persson, present

#### Agenda and Notes
* Rollcall, All
* Approval of Previous Minutes, All
    * Approved.
* Agenda Bashing, All
    * Approved.
* Action Item Review, All
* Updates from CDF sig-events
    * Naming discussions about to conclude.
    * Still unclear where in the Cloud Event fields should be placed (top-level or under the `data` key).
* Summit preparations status
    * A #summit Slack channel was set up.
    * Action Magnus: Do animations work when sharing the PPT?
    * Action Tobias: Add Slack channel link to summit page.
    * Try to save the meeting chat history if there's something we might want to publish elsewhere afterwards.
    * Action Mattias/Emil: Prepare informational chat message that will be pasted at the start of every session.
* How do we handle images? Should we upload originals or just the svg?
    * Moving to next meeting.
* Choice of topic for Eiffel monthly meeting on Sep 16
    * Open protocol PRs and issues, similar to the protocol workshop in May.
    * Action Emil: Update meeting invite to include this topic.
* Promoting Eiffel Summit in CDF slack?
    * Action Mattias: Announce the summit in the CDF slack.
* Does the TC own the Youtube channel?
    * Action Emil: Make sure all TC members can contribute videos.
    * Action Mattias: Create checklists for new or removed TC members (e.g. granting/revoking access).
* Landscape picture feedback, Mattias
* PRs and issues
    * [github.com/eiffel-community/eiffel#269](https://github.com/eiffel-community/eiffel/pull/269) is the last PR up for review to complete the Lyon release.

#### Action Items
* Magnus to file another PR to Eiffel Protocol repo to move from examples to best practices.
     * Issue already exists that could contain this improvement: https://github.com/eiffel-community/eiffel/issues/226, but no PR yet
* Tobias: Fatih to get Tobias and Mattias in touch with Nordix for Kubernetes cluster installation
    * [Fatih] Still pending unfortunately. Will come back to this as soon as I get some time.
    * Update 2021-08-12: Question sent to Fatih but no reply yet.
    * Update 2021-09-09: Future communication to be done directly with Nordix via their mailing list.
    * Action Emil: Ask Fatih to set up meeting to discuss k8s on Nordix infra.
* Magnus: Present Go package when it's available.
* Emil: See if there's a way to create something dashboard-like to more easily track PRs and issues in sets of projects. Maybe use the [project feature](https://github.com/orgs/eiffel-community/projects/1)?
* ~~Magnus: Check if it is possible to restrict accesses to repos in eiffel community from organization owners. Today we can merge PRs in any repo even if we are not maintainers explicitly.~~
    * ~~Right now there doesn't appear to be a better way than having multiple GitHub accounts; one owner account and one that's used for everything else.~~
* Mattias: Ask the community about ways to handle our graphics (in e.g. Sepia and protocol repos)
* Magnus: Do animations work when sharing the PPT?
* Mattias/Emil: Prepare informational chat message that will be pasted at the start of every session at the summit.
* Emil: Update meeting invite for the 2021-09-16 monthy meeting to include th chosen topic.
* Mattias: Announce the summit in the CDF slack.
* Emil: Make sure all TC members can contribute videos.
* Mattias: Create checklists for new or removed TC members (e.g. granting/revoking access).


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
