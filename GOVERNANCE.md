# Eiffel Community Governance

## Quick Links

* [Introduction](#introduction)
* [Projects](#projects)
* [Project Roles](#project-Roles)
* [Community Roles](#community-roles)
* [Technical Committee](#technical-committee)

## Introduction

Eiffel is a protocol for technology agnostic machine-to-machine communication in continuous integration and delivery pipelines, aimed at securing scalability, flexibility and traceability.
Eiffel is based on the concept of decentralized real time messaging, both to drive the continuous integration and delivery system and to document it.

Governance of the Eiffel Community is structured according to this document.
This structure is intended to provide a healthy, sustainable and attractive community for Eiffel development and collaboration.

The Eiffel community proactively adopts and follows best practices employed by successful open source communities while maintaining a governance agreeable to its members.

Governance of the Eiffel Community is the responsibility of Eiffel Technical Committee.

## Projects

The projects that take part in Eiffel Community develop solutions in order to contribute to Eiffel vision of technology agnostic machine-to-machine communication in CI/CD pipelines.
The work done within the projects can focus on specific areas such as security, visualization, and ease of use or contribute to and drive the high level architecture or the protocol itself which impacts the entire community.

The projects that constitute Eiffel Community are self governing, meaning that project related work is done and decisions are taken within the projects.


## Project Roles

The projects that take part in Eiffel Community currently have two roles relevant to their governance: contributors and maintainers.

### Contributors

A contributor is anyone who made contributions to any of the projects within Eiffel Community.

There are different means and ways to contribute to Eiffel Community in order to be a contributor, such as issuing and reviewing pull requests, creating issues in project backlog, or taking part in technical discussions.
Determination of the complete criteria for contributors is the responsibility of the Eiffel Technical Committee with the input from Eiffel Community at large.

Contributors are eligible to vote on Technical Committee elections. Contributors do not have the rights to accept pull requests.

### Maintainers

Maintainers are active contributors and participants in the projects they are maintainers of. Maintainers have the rights to accept pull requests.

In order for a contributor to become a maintainer for a certain project, the individual must be nominated by one of the existing maintainers of that project with a reference to the individual's history of contributions to the same project. The nomination is discussed and voted on amongst the maintainers. Unless unanimous approval within the maintainers group can be reached, the Technical Committee can be consulted for advice. If approved, the nominated contributor must be added to the GitHub team for the maintainers of this project.

Maintainers have a responsibility towards the code and content of the projects and repositories they maintain. This means the maintainer is expected to enforce the following:
* Inclusive and non-offensive content
* Adequate overall code quality
* Reasonable test coverage
* Reasonable security and vulnerability scanning

A good default for security and vulnerability scanning is to have [Dependabot Alerts](https://docs.github.com/en/code-security/dependabot/dependabot-alerts/about-dependabot-alerts), [Dependabot Security Updates](https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/about-dependabot-security-updates) and [Secret Scanning](https://docs.github.com/en/enterprise-cloud@latest/code-security/secret-scanning/about-secret-scanning) enabled. All these settings can be found under _Settings -> Code and Security Analysis_

Maintainers are eligible to vote on Technical Committee elections. They can be nominated as members to the Technical Committee during Technical Committee elections.

Individuals can be maintainers to multiple Eiffel Community Open Source Projects.

For guidelines on how to contribute, please see [our contribution guidelines](https://github.com/eiffel-community/.github/blob/master/CONTRIBUTING.md).

## Community Roles

Eiffel Community currently has two roles relevant to community governance and support.

### Election Officers

Eiffel Community Election Officers are the community members who are appointed by Eiffel Technical Committee to conduct community elections.

The term for Election Officers is **one year**.

Responsibilities of Election Officers are

* Determine the list of community members who are eligible to vote and run in community elections.
* Conduct the elections based on the process documented in [Election Process](#Election-Process).
* Ensure the elections are done in a transparent way.
* Guide the Technical Committee and Eiffel Community at large in election matters.

Eiffel Community is served by **2** election officers.

Eiffel Community Election Officers are the individuals listed below, appointed for a term ending January 31, 2026:

* Fredrik Fristedt, Axis Communications

### Security Officers

Eiffel Community Security Officers are the community members who are appointed by Eiffel Technical Committee to oversee [Eiffel Community Vulnerability and Security Reporting and Response process](https://github.com/eiffel-community/.github/blob/master/SECURITY.md).

The term for Security Officers is **one year**.

Responsibilities of Security Officers are

* Be the main contact with regards to community vulnerability and security issues including for the issues reported by users or discovered by the community members. The security officers do not take responsibility for security issues in individual repositories.
* Be a member of private community mail list eiffel-community-security@googlegroups.com and monitor it actively.
* Monitor the community [security advisories](https://github.com/eiffel-community/community/security/advisories). 
* Inform repository owners of reported issues. Acknowledging, analysing, fixing, and releasing is a responsibility for repository maintainers.
* Ensure the public disclosure of the issue and required fixes are done in a timely manner
* Ensure community vulnerability and security reporting and response process is followed by the community. 

Eiffel Community is served by **2** Security Officers.

Eiffel Community Security Officers are the individuals listed below, appointed for a term ending May 31, 2026:

* Fredrik Fristedt, Axis Communications
* Kristofer Hallén, Ericsson

## Technical Committee

The Technical Committee is responsible for the oversight of the Eiffel Community Open Source Projects. Technical Committee is comprised of **7** voting members.

No single company may be represented by more than **2** seats in the Technical Committee at any one time. If the results of an election result in greater than **2** representatives within the Technical Committee, the lowest vote getters from any particular company will be removed in order to keep company representation cap.

The term for Technical Committee is **one year**.

The responsibilities of the Technical Committee are

* coordination of the technical direction of the project(s)
* discussions, seeking consensus, and where necessary, voting on technical matters that affect multiple Eiffel Community Open Source Projects
* serving as point of contact with regards to licensing matters
* determination and amendment of the size, makeup, and the procedure for Technical Committee
* establishment of the project creation and archival processes, approving and archiving Eiffel Community Open Source Projects
* creation and amendment of community governance, election, contribution, and code of conduct guidelines
* enforcement and reminding of code of conduct processes
* creation and amendment of the criteria for maintainer promotion and removal
* creation or elimination of project and community roles
* appointing community members to interact with other open source communities
* coordinating event participation and communications regarding the Eiffel Community Open Source Projects

Eiffel Community aims to operate as a consensus based community, if any decision requires a vote to move the Eiffel Community Open Source Projects forward, the members of the Technical Committee will vote on a one vote per member basis.
Simple majority is required for any decision to be approved. When voting in a meeting, it is a simple majority of the voting members present.  When voting through email or other forms of asynchronous communication, it is a simple majority of all Technical Committee voting members. For PRs in the community repository the same rule applies, simple majority of all Technical Committee voting members.

The Technical Committee meets regularly and the meetings are intended to be open to the public and can be conducted electronically, via teleconference, or in person.
Quorum for Technical Committee meetings requires at least a majority of all voting members of the Technical Committee to be present.
The Technical Committee  may continue to meet if quorum is not met, but will be prevented from making any decisions at the meeting.

Eiffel Committee was served by Bootstrap Technical Committee between September 2020 and April 2021 based on the process documented [here](https://github.com/eiffel-community/community/blob/0c880e483723c75024ce4d477f32a9f1691e9170/GOVERNANCE.md#community-bootstrap-process).

### Technical Committee Elections and Voting

Representatives to Eiffel Community Technical Committee are elected by their peers in the Eiffel Community on the basis of merit.

Information related to conducted and ongoing elections are kept in [ELECTIONS.md](./ELECTIONS.md) document.

#### Election Rules

1. Anyone who is a maintainer of one or more non-archived projects hosted in the [Eiffel Community GitHub organization](https://github.com/eiffel-community) is eligible to run for a seat in the Eiffel Technical Committee or nominate another maintainer as a candidate. The list of eligible candidates will be sent for review to the Eiffel Community prior to the start of the nomination phase. Anyone in the Eiffel Community can request an exemption to add/remove a candidate in that list by replying to the review.
1. Anyone who is a member of the [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community) is eligible to vote in Technical Committee Elections.
1. Community elections are overseen by [Election Officers](#Election-Officers).
1. The members of Technical Committee are elected using [Ranked Voting](https://en.wikipedia.org/wiki/Ranked_voting).
If there is a tie resulting in more candidates to be elected than stated in the charter, it is responsibility of the presiding Technical Committee to determine the tie-breaking rules.

#### Election Process

The election process consists of 3 phases

* **Preparation Phase**:
  * Election Officers prepare the timeline for the elections and get it approved by the Technical Committee.
  * Election Officers determine the list of community members who are eligible to **run** in the Technical Committee elections and announce this on [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community).
  * The list of eligible members is open for review for one to two weeks. Any changes to this list are managed by the Election Officers who inform the Technical Committee before the nomination phase starts.
* **Nomination Phase**:
  * Once the eligible community members are determined, Election Officers start nomination period for Technical Committee elections by sending an email to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community). The nomination period should be between one and two weeks.
  * After the commencement of the nomination phase, eligible candidates who wish to run for a seat in Technical Committee announce their nomination by sending an email to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community). (self-nomination) If community members want to nominate someone else to Technical Committee, they can do so by sending nomination mail to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community) but this must then be accepted by the nominated community member by responding to their nomination mail in order for their candidacy to be valid. Only maintainers may nominate candidates.
  * Upon the completion of the nomination phase, Election Officers collate the nominations and announce final list of candidates on [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community).
  * Announcement of candidates ends the nomination phase.
* **Election Phase**:
  * The election medium is selected by Eiffel Community Election Officers.
  * Election Officers prepare the election poll on selected medium and enter candidates to ballot.
  * Election Officers start the election by sending poll link to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community).
  * Election period should be one to two weeks.
  * Upon the completion of the election phase, Election Officers announce the result of the election on [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community).

Elected members of the Technical Committee assume their seat during the first Technical Committee Meeting following the completion of the election phase.

#### Exceptions

There could be cases where Election Officers may need to follow different processes to ensure the election process can be completed.

One such case is the number of candidates who run for the Technical Committee elections.
If the number of candidates is less than the number of seats in Technical Committee, Election Officers are authorized to extend the nomination period for one more week. If the number of candidates is still less than the number of seats in Technical Committee, Election Officers are authorized to end the nomination and election process so all the candidates assume their seats without election. The remaining seats are left vacant. The new Technical Committee is responsible to determine if, when, and how to fill the vacant seats.
If the number of candidates is equal to the number of seats in Technical Committee, Election Officers are authorized to end the nomination and election process so all the candidates assume their seats without election.

In addition to handling exceptions that may occur during community elections, Election Officers are responsible to guide the Technical Committee and Eiffel Community at large in case someone resigns from the Technical Committee or is impeached. Technical Committee is responsible of determining how to fill vacant seat and special elections can be held if the Technical Committee deems it necessary. Otherwise, the seat can be left vacant or a community member can be appointed by the Technical Committee.

### Technical Committee Chair Elections and Voting

Chair of the Eiffel Community Technical Committee is elected from within the members of Eiffel Technical Committee.

Information related to conducted and current elections are kept in the [ELECTIONS.md](./ELECTIONS.md) document.

#### Election Rules

Anyone who is a member of the Eiffel Technical Committee is eligible to run for Eiffel Technical Committee Chair, and eligible to vote in the Eiffel Technical Committee Chair elections.

Chair elections are overseen by [Election Officers](#Election-Officers).

The Chair of Technical Committee is elected using [Ranked Voting](https://en.wikipedia.org/wiki/Ranked_voting).
If there is a tie, it is responsibility of the incoming Technical Committee to determine the tie-breaking rules.

#### Election Process

The election process consists of 2 phases

* **Nomination Phase**:
  * Election Officers start nomination period for Technical Committee Chair elections by sending an email to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community) Nomination period is limited to **one week**.
  * After the commencement of the nomination phase, eligible candidates who wish to run for Technical Committee Chair announce their nomination by sending an email to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community). (self-nomination) If community members want to nominate someone else as Technical Committee Chair, they can do so by sending nomination mail to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community) but this must then be accepted by the nominated community member by responding to their nomination mail in order for their candidacy to be valid. Only Technical Committee members may nominate candidates.
  * Upon the completion of the nomination phase, Election Officers collate the nominations and announce final list of candidates on [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community).
  * Announcement of candidates ends the nomination phase.
* **Election Phase**:
  * The election medium is selected by Eiffel Community Election Officers.
  * Election Officers prepare the election poll on selected medium and enter candidates to ballot.
  * Election Officers start the election by sending poll link to [Eiffel Community Maillist](https://groups.google.com/g/eiffel-community).
  * Election period is limited to **one week**.

#### Exceptions

Technical Committee is ultimately responsible for if, when, and how the chair will be elected.

Technical Committee may decide to run the election as documented in this chapter or the committee may well decide to use a lightweight process such as electing the chair from within itself during the very first meeting the new members of the committee assume their seat.
However, all members of the Technical Committee must be present in this meeting in order for this process to be valid.
Otherwise, Technical Committee may decide to run chair elections or postpone application of the lightweight process to elect chair to the next meeting.

If Technical Committee decides to hold elections for Technical Committee Chair, there could still be cases where Election Officers may need to follow different processes to ensure the election process can be completed.
One such case is the number of candidates who run for the Technical Committee Chair election.

If there is no candidate for Technical Committee Chair election, Election Officers are authorized to extend the nomination period for one more week. If there is still no candidate, Election Officers are authorized to end the nomination and election process and this matter is discussed within Technical Committee during the very first Technical Committee Meeting following the end of the nomination period. The Technical Committee is responsible to determine if, when, and how to fill the chair seat.

If the number of candidates is one and their candidacy is unchallenged, Election Officers are responsible to bring this topic to the very first Technical Committee Meeting in order to determine if an extension for the nomination period is required or the unchallenged candidate assumes their seat. Simple majority within Technical Committee is required for candidate to assume their seat.

### Technical Committee Members

Members of the Technical Committee are appointed via community elections. Project maintainers are eligible to run as candidates for the Technical Committee in elections.
Maintainers and contributors are eligible to vote in elections.

Members of the Technical Committee are the individuals listed below. You can reach all current members with the [eiffel-tc@googlegroups.com](mailto:eiffel-tc@googlegroups.com) mailing list.

Full Name         | Company              | GitHub                                                        | Elected On | Until
------------------|:--------------------:|---------------------------------------------------------------|------------|-----------
Magnus Bäck       | Axis Communications  | [magnusbaeck](https://github.com/magnusbaeck)                 | May 2025   | May 2026
Mattias Linnér    | Ericsson             | [m-linner-ericsson](https://github.com/m-linner-ericsson)     | May 2025   | May 2026

The technical committee members will strive to

* represent a cross-section of interests
* balance technical, architectural, and governance expertise in order to increase community participation
* be inclusive in decision-making process
* hold staggered terms, sufficient to ensure an orderly transition of power via elections as designed and implemented by the committee
* provide designated alternates in cases where quorum is required but not attainable with the current set of members

Members of the Technical Committee will be granted access to the repositories listed [here](https://github.com/search?q=topic%3Acommunity+org%3Aeiffel-community+fork%3Atrue).

### Technical Committee Chair

The committee elects two Technical Committee Chairs from within members, who will preside over meetings of the committee and will serve until their resignation or replacement by the committee.

The goal of this position is servant leadership for the Eiffel Community, projects that take part in Eiffel Community, committee and stakeholders.

As the Technical Committee currently only has two members, no chairs have been elected.

The chairs MUST ensure that

* the community processes are being adhered to
* the committee meetings are scheduled and minutes are kept
* all committee meetings are inclusive
* community and committee communication channels such as maillists are available

### Vacancies in Technical Committee

In the event of a resignation or other loss of an elected Technical Committee member, the candidate with the next most votes from the previous election will be offered the seat. This process will continue until the seat is filled.
In case this fails to fill the seat, the process to fill the seat is determined by the Technical Committee.

In the event of a resignation or other loss of the elected Technical Committee Chair, the Technical Committee determines the process to elect a new chair from within the remaining members of the Technical Committee.
