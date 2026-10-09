# SIS Cyber-Safety Assurance: Supplementary Dataset
This repository contains the supplementary dataset supporting a survey of cybersecurity and cyber-safety assurance for Safety Instrumented Systems (SIS). It brings together source-level extractions, evidence coding, architecture definitions, and synthesis tables for 141 sources.
The dataset supports examination of attack pathways, safety impacts, assurance consequences, lifecycle exposure, defensive measures, assessment methods, standards, and human factors. Its counts describe coverage within the reviewed literature; they do not estimate incident frequency or operational risk.

## Current status
The current workbook is **release version V0.1**:

The corpus inventory was frozen on 10 August 2026, as recorded in the workbook.

## Dataset overview
| Item | Coverage |
| --- | --- |
| Retained sources | 141 |
| Peer-reviewed papers | 115: PR001–PR115 |
| Doctoral theses | 6: DT001–DT006 |
| Institutional/practitioner sources | 12: IP001–IP012 |
| Technical reports | 8: TR001–TR008 |
| SIS relevance | 58 primary-focus; 83 secondary-relevance sources |
| Binary coding fields | 84 non-exclusive categories |
| Assessed source–category cells | 11,844 |
| Positive assignments | 1,065 |
| Positive assignments per source | Median 7; range 1–27 |

These figures describe the V1.1 release candidate. Study IDs connect the corpus index, references, coding matrix, evidence statements, and synthesis tables.


## Workbook contents
| Worksheet or group | Contents |
| --- | --- |
| README | Scope, creators, corpus description, coding conventions, and interpretation notes |
| Corpus Index & Evidence Claims | Source titles, SIS relevance, evidence classes, contributions, findings, and reported limitations |
| Reference Index | Bibliographic information linked to stable source IDs |
| Coding Matrix | Source-level Yes/No assignments across 84 categories |
| Coding Evidence | Evidence statements and claim boundaries for every positive assignment |
| Coding Dictionary | Inclusion rules, exclusion boundaries, missing-data conventions, and category counts |
| Coding Decisions | Recorded resolutions of selected coding and consistency issues |
| Eight category summaries | Attack Pathways, Safety Impacts, Assurance Consequences, Lifecycle, Defenses, Methods, Standards, and Human Factors |
| Functional Zones; Controlled Conduits; L-D-X Interactions | Architectural zones, controlled communication paths, lifecycle interactions, dependencies, and exception paths |
| Architecture-Evidence Crosswalk | Connections between architectural elements and supporting evidence |
| Tables S1–S9 | Extended thematic syntheses and research agenda |
| Table S10 Method Evidence | Method-family coverage across six issue dimensions, with evidence states and supporting IDs |
| Table S11 Integrated | Integrated findings, standards connections, required assurance outputs, and evidence gaps |


## How to use the dataset
1. Read the workbook README and Coding Dictionary before interpreting the codes.
2. Locate a source in the Corpus Index and use its stable ID to retrieve its Reference Index entry.
3. Inspect its Coding Matrix assignments and corresponding Coding Evidence statements.
4. Use the category summaries to examine literature coverage and Tables S1–S11 to examine synthesis claims.
5. Consult the original source before reusing a technical claim or transferring a finding to a specific SIS or process.
   
## Coding conventions
- **Yes** means that the source meets the category's inclusion rule.
- **No** means that the inclusion rule was not met. It does not establish that the phenomenon is absent in practice.
- Blank and N/A values are not valid in the binary matrix. Bibliographic blanks indicate unavailable metadata.
- Categories are non-exclusive: one source may contribute to several categories.
- Category proportions use 141 sources as the denominator. Percentages across categories need not sum to 100%.
- A positive assignment records qualifying coverage; it does not by itself establish a demonstrated attack, realized consequence, or effective control.

## Method–dimension evidence states
Table S10 assigns states to individual method-family/issue-dimension relations:
| State | Meaning |
| --- | --- |
| 0 | No qualifying treatment |
| 1 | Conceptual discussion without SIS-specific application or validation |
| 2 | Application in an SIS or comparable safety-critical case, model, or simulation |
| 3 | Direct evaluation of the relation using incident or operating evidence, a commercial device, a hardware-in-the-loop/testbed setup, or a deployed workflow |

A source's overall evidence class does not automatically determine these states. State 3 remains bounded by the reported configuration and evaluation scope; it is not an overall method-quality or plant-suitability rating.

## Citation 
Please cite the associated manuscript if you use this material

## Dataset creators
- Samson O. Oruma
- Mary Ann Lundteigen
- Vasileios Gkioulos
- Sokratis Katsikas

**Corresponding creator:** Samson O. Oruma  
**Email:** [samson.o.oruma@ntnu.no](mailto:samson.o.oruma@ntnu.no)  
**ORCID:** [0000-0001-5784-8481](https://orcid.org/0000-0001-5784-8481)

## Licence
This supplementary material is released under the license specified in this repository.
## Corrections
Please report issues with the affected study ID, worksheet, category or cell, and supporting source details. Where possible, include a page or section locator and explain the proposed correction. Contact the corresponding creator.
