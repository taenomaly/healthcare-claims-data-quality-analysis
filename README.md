# Healthcare Claims Denial & Data Quality Analysis

## Project Overview

An Excel-based healthcare data analytics portfolio project examining 150 synthetic healthcare claims to identify denial and rejection patterns, missing information, potential duplicate claims, and payer-specific trends.

This project demonstrates practical applications of healthcare data validation, revenue cycle analysis, Excel reporting, and data-driven problem-solving.

**Data privacy:** All records are fictional and were created for educational purposes. No real patient, employer, or claims information is included.

## Tools & Skills Demonstrated

- Microsoft Excel
- PivotTables and PivotCharts
- COUNTIF and other Excel calculations
- Data filtering, categorization, and validation
- Data quality flagging and duplicate identification
- Dashboard development and data visualization
- Healthcare claims and denial analysis
- Interpretation of findings and development of follow-up recommendations

## Dashboard Summary

| Metric | Result |
|---|---:|
| Total claims analyzed | 150 |
| Denied claims | 51 |
| Rejected claims | 22 |
| Denial and rejection rate | 48.7% |
| Claims flagged for missing information | 32 |
| Unique claims flagged for data-quality review | 35 |
| Potential duplicate claims | 4 |

## Key Findings

### 1. Missing Insurance IDs
13 claims (8.7%) were flagged for missing Insurance IDs. Their denial/rejection rate was 53.8%, compared with 48.2% for claims without this flag.

**Recommendation:** Review denial and rejection reasons to investigate whether the missing information contributed to claim outcomes.

### 2. Missing Information Patterns
32 of 150 claims (21.3%) were flagged for missing information. The most frequently missing fields were Insurance ID (13), Provider ID (7), Diagnosis Code (6), and Authorization Number (6).

**Recommendation:** Compare original EHR records with submitted claims to identify whether information was missing at the source or during claim processing.

### 3. Potential Duplicate Claims
Four claims (2.7%) were flagged as potential duplicates. Two were denied, one was paid, and one remained pending.

**Recommendation:** Review submission histories and related claim details to investigate potential duplicate submissions.

### 4. Medicaid Duplicate Submission Patterns
Of 32 denied or rejected Medicaid claims, seven (21.9%) were categorized under Duplicate Submission, the most frequent denial/rejection reason for that payer.

**Recommendation:** Investigate submission histories and workflows to identify potential causes and determine whether process improvements are needed.

## Workbook Contents

- **START HERE:** Project navigation and overview
- **Claims Data:** 150 synthetic claims and data-quality indicators
- **Pivot Tables:** Summaries of missing fields, duplicates, and denial reasons
- **Dashboard:** Key performance indicators and visualizations
- **Analysis:** Calculated metrics and claim statistics
- **Analysis Notes:** Detailed findings and recommendations
- **Definitions:** Data field explanations

## Project File

The Excel workbook is available in this repository:

[Healthcare Claims Denial and Data Quality Analysis.xlsx](Healthcare_Claims_Denial_and_Data_Quality_Analysis.xlsx)

*This is an independent portfolio demonstration using synthetic data, not an analysis of actual organizational performance.*
