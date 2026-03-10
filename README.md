# UKRI Funding Outcomes Meeting Compilation

This repository contains a best attempt at unifying funding panel meeting outcomes and panel attendance for each of the UKRI funding councils into a processable format.

| Council   | Meetings | Applications | Successful | Panellists | With panellists | Unmatched |
|-----------|----------|--------------|------------|------------|-----------------|-----------|
| AHRC      | 449      | 9,112        | 1,610      | 2,102      | 283             | 0         |
| BBSRC     | 31       | 5,215        | 1,432      | 3,109      | 20              | 65        |
| EPSRC     | 308      | 4,557        | 870        | 2,554      | 228             | 0         |
| ESRC      | 158      | 4,992        | 1,434      | 395        | 10              | 9         |
| MRC       | 324      | 7,522        | 3,063      | 339        | 16              | 0         |
| NERC      | 153      | 7,966        | 2,353      | 3,231      | 32              | 299       |
| STFC      | 27       | 1,145        | 283        | 0          | 0               | 0         |
| **Total** | **1450** | **40,509**   | **11045**  | **11,730** | **589**         | **373**   |

The data for each panel is spread across a number of locations and a wide array of document formats and layouts, making analysis across meetings and funding bodies effectively impossible. Interrogation of these meetings is crucial as they mark the actual point at which final funding decisions are made and offers the only insight, publicly available, into unfunded proposals. Without a unified and standardised representation of this data, investigations into systematic bias or the actual competitiveness of particular opportunities is not possible. While imperfect and incomplete, I hope this data allows for further research to tackle pressing questions of inequality in funding allocation under UKRI and its subsidiary councils.

`NOTE:` I make no guarantee to keep this data up-to-date. In the case of errors, omissions, extensions or improvements to this data, please open an issue on this repository. If you believe this data contains information that should not have been made publicly available, please **contact me privately** through the email in my Github profile.

## Important Notes

When using or handling this data, remember that these are real people and real projects, funded or unfunded. While interrogation of this data is important, **the people mentioned in these documents should not be contacted or harassed**.

This is an **incomplete** dataset. While this accounts for nearly all sources of panel meetings and attendance I am aware of, it does not account for proposals that were rejected before the review/panel stages, for certain opportunity types that do not go to panel, where the process is not appropriate (see STFC below), or in cases where the data was deemed sensitive or unsuitable for public disclosure. I also did not have the time to dedicate to mapping absolutely all of this data.

InnovateUK is not included as their funding meeting outcomes are not published.

This data has been curated and filtered to comply with the CC BY-NC-SA 4.0 license outlined in the [UKRI terms of use](https://www.ukri.org/who-we-are/terms-of-use/).

When interpreting this data, UKRI make the following very clear:

> We make funding decisions in circumstances unique to each panel meeting. You should not compare the funding cut-off points made in different meetings.
> 
> We cannot consider challenges to, or enquiries about decisions based on these kinds of comparisons.
> 
> You must wait for official confirmation before making any commitments against your award.

## Source Information and Limitations

### AHRC

https://www.ukri.org/what-we-do/what-we-have-funded/ahrc/board-and-panel-outcomes/

AHRC usually publishes outcomes within three months of a meeting. Each AHRC panel meeting will show the grade and rank of every application assessed at the panel meeting along with the names and roles of panel members. Unsuccessful applications are made confidential.

Meetings from 2014-2019 were obtained from the [Government Web Archive](https://webarchive.nationalarchives.gov.uk/ukgwa/20210322121238/https://ahrc.ukri.org/funding/research/paneloutcomes/) as `.xlsx` files.

Later meetings are only available via the AHRC Tableau dashboards ([2017-2023 dashboard](https://public.tableau.com/app/profile/arts.and.humanities.research.council/viz/PanelsOutcomeAttendance/NavigationDash)) ([2023-present dashboard](https://public.tableau.com/app/profile/arts.and.humanities.research.council/viz/PanelsOutcomeAttendanceTFSApplications/PanelSelectPage)) (currently not available - 10/03/2026).

`NOTE:` AHRC has disabled the data download feature on their dashboards (10/03/2026).

### BBSRC

https://www.ukri.org/what-we-do/what-we-have-funded/bbsrc/committee-and-panel-outcomes/

BBSRC usually publishes outcomes within four weeks of a meeting. These meetings detail the outcomes of standard research grant applications, including: which were funded, fundable or not fundable; reference numbers, principle investigators, institution awarded, project and requested value. Committee membership declares the panel, their organisations and their roles on the panel.

Meeting information is not available pre-2017. Available meetings are shared as `.xlsx`. Attendance is recorded separately as `.pdf`.

`NOTE:` A best attempt was made to align these meetings and panels but in cases of ambiguity, no match was made rather than potentially fabricating a mapping.

### EPSRC

https://www.ukri.org/what-we-do/what-we-have-funded/epsrc/

Meeting information is exclusively available via the [EPSRC Tableau Dashboard](https://public.tableau.com/app/profile/epsrcdatateam/viz/EPSRCFundingApplicationOutcomes/MeetingList) which lists outcomes of EPSRC funding applications assessed at panel meetings. Funding applications that were not assessed at a panel meeting are not included.

Information before 2018 is available via the [Government Web Archive](https://webarchive.nationalarchives.gov.uk/ukgwa/20210323121751/https://epsrc.ukri.org/funding/fundingdecisions/successrates/previous/) but only as "Funding Rates". These have not been included in this dataset.

`NOTE:` EPSRC has disabled the data download feature on their dashboard (10/03/2026).

### ESRC

https://www.ukri.org/what-we-do/what-we-have-funded/esrc/board-and-panel-outcomes/

About half of ESRC proposal decisions are made within five months of application, and around three quarters within six months. Outcomes are published only when ESRC have processed all applications submitted for an opportunity. This can take from a few weeks to a few months for opportunities with a large number of applications. Board and panel outcomes do not include applications that are: reviewer rejects; office rejects; research organisation withdrawals. This means you cannot use outcomes data to work out success rates for individual opportunities.

Panel outcomes and memberships are not available before 2018. From 2018 onwards, data is published as a single `.xlsx` file.

### MRC

https://www.ukri.org/what-we-do/what-we-have-funded/mrc/board-and-panel-outcomes/

MRC usually publishes outcomes within four weeks of a meeting, but it can sometimes take longer. Applications unsuccessful after a shortlisting meeting are not discussed in funding meetings. Details of these applications are not included in board and panel outcomes. Applications are scored using the [MRC scoring structure](https://www.ukri.org/councils/mrc/guidance-for-reviewers/peer-review-panels/peer-review-panel-scoring-and-definitions/). The funding cut-off is dependent on the available budget at any given meeting.

Pre-2017 outcomes are available via the [Government Web Archive](https://webarchive.nationalarchives.gov.uk/ukgwa/20210807005926/https://mrc.ukri.org/research/funded-research/board-panel-meeting-outcomes/meeting-outcomes-archive1/), 2017-2024 outcomes are available on the [UKRI website](https://www.ukri.org/what-we-do/what-we-have-funded/mrc/board-and-panel-outcomes/) as `.xlsx` files and panel outcomes and attendance for 2025-present are available on the [MRC Tableau dashboard](https://public.tableau.com/app/profile/mrcevaluationandanalysis/viz/MRCPanelOutcomes/Overview).

`NOTE:` MRC has disabled the data download feature on their dashboard (10/03/2026).

`NOTE:` I still need to process and upload the pre-2017 MRC data (10/03/2026).

`NOTE:` Panel membership pre-2025 is obtainable from the [UKRI website](https://www.ukri.org/who-we-are/mrc/board-and-panel-membership/) but would need to be fetched from the Government Web Archive at the time of each meeting to attempt an alignment. I do not have time to do this presently (10/03/2026).

### NERC

https://www.ukri.org/what-we-do/what-we-have-funded/nerc/board-and-panel-outcomes/

NERC usually aims to publish outcomes within eight weeks of a meeting.

Outcomes before 2017 were obtained from the [Government Web Archive](https://webarchive.nationalarchives.gov.uk/ukgwa/20210605060011/https://nerc.ukri.org/funding/application/outcomes/awards/). Pre-2017 panels are also available, separately, via the [Government Web Archive](https://webarchive.nationalarchives.gov.uk/ukgwa/20210605054219/https://nerc.ukri.org/funding/application/assessment/panelmembership/). From 2017-present, outcomes and memberships are uploaded to [UKRI's website](https://www.ukri.org/what-we-do/what-we-have-funded/nerc/board-and-panel-outcomes/). All documents are uploaded as `.pdf` files in various formats.

`NOTE:` A limited attempt was made to align these meetings and panels. Only simple mappings were drawn between meetings and panel attendances. I may return to improve on this in the future (10/03/2026).

### STFC

https://www.ukri.org/what-we-do/what-we-have-funded/stfc/board-and-panel-outcomes/

STFC aims to publish outcomes within one month of each board or panel making the final funding decision. STFC note the following on their outcomes page:

> The nature of some of our grants means we cannot show them in board and panel outcomes. For example, we rank our consolidated grants in astronomy, particle physics and nuclear physics by the constituent projects rather than by the grants themselves. For grants like these, we let applicants know how their application did compared to others in written feedback.

STFC board and panel outcomes before 2017 are not available. Outcomes from 2017-present are available on the [UKRI website](https://www.ukri.org/what-we-do/what-we-have-funded/stfc/board-and-panel-outcomes/). Uploaded files are predominantly `.xlsx` with some `.docx` files mixed in.

`NOTE:` Panel membership is obtainable from the [UKRI website](https://www.ukri.org/who-we-are/stfc/how-we-are-governed/advisory-boards/) but would need to be fetched from the Government Web Archive at the time of each meeting to attempt an alignment. I do not have time to do this presently (10/03/2026).

### HPC Access

https://www.ukri.org/publications/access-to-high-performance-computing-hpc-panel-meetings/

Details of successful applications and panel membership for the access to HPC panel, previously known as the resource allocation panel. These panels fall under EPSRC funding.

Data from 2017-present is available on [UKRI's website](https://www.ukri.org/publications/access-to-high-performance-computing-hpc-panel-meetings/).