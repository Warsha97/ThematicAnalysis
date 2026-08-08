# Thematic Analysis Repository

## Thesis Context

This repository contains the thematic analysis supporting the master's thesis:

**Requirements for an AI-Enhanced Pattern Mining System for Healthcare BPMN Models**

The study investigates the research question:

> **How can AI support pattern mining for healthcare BPMN models?**

The thesis follows a requirements-focused Design Science Research (DSR) approach. A Systematic Literature Review (SLR), guided by PRISMA, was used to identify relevant literature, and thematic analysis was applied to derive recurring challenges and requirements for an AI-enhanced pattern mining system.

## Purpose of This Repository

The repository provides the detailed evidence base behind the thematic analysis reported in the thesis. It is intended to make the derivation of themes and requirements transparent and traceable.

The analysis links:

**Literature source → quotation → code → theme → requirement → pattern-mining phase**

The main dataset is provided in:

- `Thematic Analysis.xlsx`

## Literature Selection

The literature search identified **461 records** across Google Scholar and SpringerLink.

After screening:

- **184 papers** were retained for abstract review.
- **31 papers** were selected for full-text review.
- **15 papers** were included in the final thematic analysis.

## Thematic Analysis Process

The analysis followed a structured thematic coding procedure based on Braun and Clarke's six-phase framework.

The process consisted of:

1. Familiarising with the selected literature.
2. Extracting text segments that explicitly described challenges, limitations, needs, or opportunities related to pattern mining in healthcare BPMN models.
3. Assigning concise semantic codes to the extracted quotations.
4. Iteratively refining, merging, or splitting codes.
5. Grouping related codes into higher-level themes.
6. Examining the themes to identify where AI-enhanced support could address the reported challenges.
7. Translating relevant themes into design-oriented requirements.

Coding was performed at a **semantic level**, focusing on explicit statements in the literature rather than latent interpretations.

## Spreadsheet Structure

The worksheet **`Thematic analysis results`** contains the following columns:

| Column | Description |
|---|---|
| **Theme ID** | Identifier assigned to the theme (T1-T13). |
| **Theme** | Higher-level theme derived from related codes. |
| **Paper** | Academic publication from which the evidence was extracted. |
| **Quotes** | Relevant quotation or excerpt from the source publication. |
| **Codes** | Concise semantic code assigned to the quotation. |
| **Requirement ID** | Requirement derived from the theme, where applicable. |
| **Requirements** | Requirement statement supported by the theme. |
| **Phase for the requirement** | Pattern-mining phase associated with the requirement. |

## Identified Themes

The thematic analysis resulted in **13 themes**:

| Theme ID | Theme | Requirement Derived |
|---|---|---|
| **T1** | Complex and Variable Healthcare BPMN Models | Yes |
| **T2** | Manual Effort for Parameters | Yes |
| **T3** | Repository- and Graph-Based Knowledge Extraction | No |
| **T4** | Frequent, Rare, and Anomalous Pattern Detection | No |
| **T5** | Domain and Modelling Knowledge Gap | Yes |
| **T6** | Scalability and Time-Critical Mining Limitations | Yes |
| **T7** | Struggles with Complex BPMN Structures | Yes |
| **T8** | Implicit, Approximate, and Non-Contiguous Discovery | Yes |
| **T9** | Black-Box Nature of Pattern Mining | Yes |
| **T10** | Sequential Care Pathway Mining and Its Limitations | No |
| **T11** | Automated Quality-Aware Assessment | Yes |
| **T12** | Similarity, Clustering, and Process Consolidation | No |
| **T13** | Syntactic and Semantic Correctness of Merged Models | No |

Themes **T3, T4, T10, T12, and T13** contributed to understanding the problem space but were not translated into standalone requirements.

## Derived Requirements

Nine requirements were derived from the thematic analysis:

| Requirement | Name | Theme | Phase |
|---|---|---|---|
| **R1** | Models Standardisation | T1 | Preparation |
| **R2** | Interactive Support | T2 | Discovery |
| **R3** | Contextual and Domain-Aware Explanation | T5 | Assessment |
| **R4** | Mining Time Estimation | T6 | Discovery |
| **R5** | Pattern Ranking and Filtering | T6 | Assessment |
| **R6** | Loop Pattern Detection | T7 | Discovery |
| **R7** | Non-Sequential Pattern Detection | T8 | Discovery |
| **R8** | Mining Explainability | T9 | Assessment |
| **R9** | Pattern Quality Assessment | T11 | Assessment |

The requirements are organised around the three pattern-mining phases used in the thesis:

- **Preparation** - preparing healthcare BPMN models before pattern discovery.
- **Discovery** - configuring and executing pattern discovery and handling complex structures.
- **Assessment** - interpreting, prioritising, explaining, and evaluating discovered patterns.

## Traceability

The spreadsheet provides detailed traceability from each requirement back to the literature evidence used in its derivation.

The thesis also contains an appendix table mapping:

**Theme ID → Requirement ID → Phase → Paper Sources**

This repository contains the more detailed quotation- and code-level analysis underlying that mapping.

## Interpretation of the Dataset

The quotations originate from the reviewed academic publications. The **codes**, **themes**, and **requirement mappings** represent the authors' qualitative analysis of those sources.

This dataset should therefore be interpreted as a qualitative traceability artefact rather than a quantitative dataset. The number of quotations associated with a theme should not be treated as a measure of the theme's importance.

Not every identified theme was converted into a requirement. Themes were operationalised into requirements when they directly supported analyst needs or system-level challenges relevant to the scope of the proposed AI-enhanced pattern mining system.

## Academic Use

When reusing or discussing evidence contained in this repository, the **original academic publication should be cited**. The quotations remain the intellectual property of their respective authors and publishers and are included here for scholarly analysis and traceability.

## Authors

- Reziye Tuersun
- Warsha Vimanga Kiringoda

Master's Degree Project in Strategic Information Systems Management  
Department of Computer and Systems Sciences  
Stockholm University  
Spring 2026
