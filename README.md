# Thematic Analysis: AI-Enhanced Pattern Mining for Healthcare BPMN Models

## Overview

This repository contains the thematic analysis used in a master's thesis investigating how AI can support pattern mining in healthcare BPMN model repositories.

The analysis synthesises evidence from the reviewed literature to identify recurring challenges and limitations in healthcare BPMN modelling, pattern mining, process mining, and related areas. Relevant excerpts were coded and grouped into higher-level themes. These themes were then used as the evidence base for deriving requirements for a future AI-enhanced pattern mining system.

The complete analysis is provided in the Excel file:

- `Thematic Analysis.xlsx`

## Purpose of the Dataset

The dataset provides traceability between:

**Literature evidence → quotations → codes → themes → derived requirements → pattern-mining phase**

It is intended to make the analytical process transparent and to show how the requirements presented in the thesis were grounded in findings from previous research.

## Analysis Process

The thematic analysis followed a structured qualitative coding process:

1. Relevant academic publications were reviewed.
2. Explicit statements describing challenges, limitations, needs, or observations were extracted as quotations.
3. Each quotation was assigned a concise semantic code.
4. Related codes were grouped into broader themes.
5. Themes were organised according to the relevant pattern-mining phase: **Preparation**, **Discovery**, or **Assessment**.
6. Themes that directly supported the scope of the artefact were translated into design requirements.

Not every identified theme was converted into a standalone requirement. Some themes were retained because they contributed to understanding the problem space but overlapped with stronger themes or fell outside the final artefact scope.

## Spreadsheet Structure

The worksheet **`Thematic analysis results`** contains the following columns:

| Column | Description |
|---|---|
| **Theme ID** | Identifier assigned to each theme (T1–T13). |
| **Theme** | Higher-level theme derived from related codes. |
| **Paper** | Academic publication from which the evidence was extracted. |
| **Quotes** | Relevant excerpt from the source publication. |
| **Codes** | Concise semantic code assigned to the quotation. |
| **Requirement ID** | Requirement derived from the theme, where applicable. |
| **Requirements** | Design requirement supported by the theme. |
| **Phase for the requirement** | Pattern-mining phase in which the requirement applies. |

## Identified Themes

The analysis resulted in **13 themes**:

| ID | Theme | Requirement |
|---|---|---|
| **T1** | Complex and variable healthcare BPMN models | R1 |
| **T2** | Manual effort for parameters | R2 |
| **T3** | Repository and graph-based knowledge extraction | — |
| **T4** | Frequent, rare, and anomalous pattern detection | — |
| **T5** | Domain and modelling knowledge gap | R3 |
| **T6** | Scalability and time-critical mining limitations | R4, R5 |
| **T7** | Struggles with complex BPMN structures | R6 |
| **T8** | Implicit, approximate, and non-contiguous pattern discovery | R7 |
| **T9** | Black-box nature of pattern mining | R8 |
| **T10** | Sequential care pathway mining and its limitations | — |
| **T11** | Automated quality-aware assessment | R9 |
| **T12** | Similarity, clustering, and process consolidation | — |
| **T13** | Syntactic and semantic correctness of merged models | — |

## Derived Requirements

Nine requirements were derived from the thematic analysis:

| ID | Requirement |
|---|---|
| **R1** | Model Standardisation |
| **R2** | Interactive Support |
| **R3** | Contextual and Domain-Aware Explanation |
| **R4** | Mining Time Estimation |
| **R5** | Pattern Ranking and Filtering |
| **R6** | Loop Pattern Detection |
| **R7** | Non-Sequential Pattern Detection |
| **R8** | Mining Explainability |
| **R9** | Pattern Quality Assessment |

The requirements address different stages of the pattern-mining workflow, including model preparation, pattern discovery, and pattern assessment.

## Interpretation of the Dataset

The quotations in the spreadsheet are evidence extracted from the reviewed publications. The **Codes** and **Themes** represent the authors' qualitative interpretation of that evidence.

The spreadsheet should therefore be read as a traceability artefact rather than as a quantitative dataset. The number of quotations associated with a theme does not by itself indicate the importance of that theme.

## Academic Use

This repository supports transparency and reproducibility of the thesis analysis. When reusing material from the spreadsheet, the original academic publications should be cited rather than this repository alone.

Quotations remain the intellectual property of their respective authors and publishers and are included for scholarly analysis and traceability.

## Related Research

The dataset accompanies a master's thesis on requirements for AI-enhanced pattern mining in healthcare BPMN models. The thesis applies a requirements-focused Design Science Research approach supported by a systematic literature review and thematic analysis.

