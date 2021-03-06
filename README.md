# The UTM Documentation Repository

This repository is for maintaining publicly available NASA UTM documentation.  Read on for further details on why this repo exists.

## Repository Status
As of the time of this edit (21 Mar 2018), this repo is in a formation stage.  It should NOT be used as 'truth' for the state of UTM documentation by any entity at this time.

The repository will not ever be a comprehensive site for all UTM documentation.  There are many NASA UTM documents that are not yet ready for public release.  As those mature to a state where public release is reasonable, we will endeavor to include them here if they add to understanding the core UTM System concepts and implementation.

## Audience
The primary audience for this repository are current NASA UTM partners or those partners that are currently in the on-boarding process.  There may be value to others as well.

## Externally Avaialble Documentation Collections
In this section we link to important documentation already available elsewhere.

| External location        | Description |
| ------------------------ | ------------- |
| [NASA UTM Publication Repository](https://utm.arc.nasa.gov/documents.shtml) | This the full repository for all conference publications, NASA technical memos, and similar documents. We'll try to pull some of the key docs directly into this repository. |
| [NASA UTM APIs](https://github.com/nasa/utm-apis) | A github repository representing the truth in terms of the current state of NASA APIs. |
| [SwaggerHub API Documentation](https://app.swaggerhub.com/search?owner=utm)  | A conveinence view of the NASA UTM APIs. *NOTE THAT THE GITHUB REPO IS TRUTH FOR THE APIs*. It is possible for the SwaggerHub documenation and our github API repo to drift. Developers must always reference the github repo for building compliant systems. Swagger hub is nice for navigating and discussing the API with others. | 

## Primary Concept Documents
| Document        | Pub Date | Description |
| ------------------------ | --- | ------------- |
| [UTM: Enabiling Low-Altitude Airspace and UAS Operations](UTM-Original-TM-20140013436.pdf) | 2014 April | The original NASA Technical Memo describing UTM. |
| [Unmanned Aircraft System Traffic Management (UTM) Concept of Operations](Aviation2016_UTMConOps_AsPublished_v2.pdf) | 2016 June | The first version of the UTM ConOps. |

## Documentation Supporting Software Development

## Working Group Documents
This section will contain publicly-releaseable documents that originated from within each working group within NASA UTM.  Again, we emphasize that these document lists do not represent the depth and breadth of work since not all documents are able to be publicly released.  We will endeavor to keep this list up to date, but also encourage folks to submit a github issue if you think something is missing or have a suggestion for a helpful doc to include.

The structure of the working groups is somewhat driven by the [NASA-FAA Research Transition Team for UTM](https://www.faa.gov/uas/research/utm/) organization structure.  Please see the [UTM RTT Plan](FAA_NASA_UAS_Traffic_Management_Research_Plan.pdf) for more details on the Research Transition Team.

### Concepts Working Group
The CWG will define the concept of UTM in terms of overall conceptual principles and
assumptions, including those associated with operations, supporting architecture,
information flows and exchanges, and FAA and UAS operator roles and responsibilities.
This scoping and definition will: (1) ensure consistent messaging of a coordinated
FAA/NASA view of UTM; (2) guide the efforts of other UTM RTT working groups; and
(3) support the development of the UTM pilot program.

### Data and Information Architecture Working Group
The objective of the DWG is to identify and collaboratively research and develop
technical capabilities for the data/information exchange needed across stakeholders to
support UAS operations that meet NAS service expectations. The data exchange and
information architecture subgroup will work in conjunction with the Concepts &
Scenarios, SAA, and Communications & Navigation subgroups to identify the data
exchange and information gaps and/or deltas associated with the UTM concepts,
strategies, and system capabilities to support safe expansion of the UAS operating
envelope across the NAS structure.

| Document        | Pub Date | Description |
| ------------------------ | --- | ------------- |
| [UAS Reports (UREPs): Enabling Exchange of Observation Data Between UAS Operations](Rios_NASA-TechMemo_219462_UTM_UREP_20170214.pdf) | 2017 Feb | Description of the UREP concept and data schema. |
| [UTM Data Working Group Demonstration 1: Final Report](Rios_NASA-Tech-Memo-2017-219494v2.pdf) | 2017 April | Description and results from a collaboartive simulation in support of TCL2. |


### Sense and Avoid Working Group
The objective for this subgroup is to explore operator solutions to ensure that unmanned
aircraft do not collide with other aircraft (unmanned or manned).

### Communications and Navigation Working Group
The objective for this subgroup is to explore operator solutions to ensure that UA are
under operational control of the pilot (to the degree appropriate to the scenario) and
remain within a defined area (around a planned trajectory or as a defined area).
