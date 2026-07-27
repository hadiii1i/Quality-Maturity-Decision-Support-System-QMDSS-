# Quality Maturity Decision Support System (QMDSS)

> **Transforming Quality Assessment Data into Executive Decisions**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-Scoring%20Engine-217346?logo=microsoft-excel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-Analytics-blue)
![MDI](https://img.shields.io/badge/Framework-MDI-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Executive Summary

The **Quality Maturity Decision Support System (QMDSS)** is an Executive Decision Support System designed to assess the maturity of an organization's Quality Management System (QMS) using the **Maturity Diagnostic Instrument (MDI)**.

Instead of simply collecting questionnaire responses, this project transforms assessment data into meaningful business insights that help management understand:

- Current Quality Maturity
- Organizational Capability Gaps
- Similarity to World-Class Organizations
- Strategic Improvement Priorities
- Executive-Level Decision Support

The project combines structured assessment, automated scoring, analytical models, and interactive Power BI dashboards into a complete workflow.

---

## Why This Project?

Many organizations invest in Lean, Six Sigma, ISO, or Continuous Improvement initiatives **before understanding whether their organization is mature enough to successfully implement them.**

Without a maturity assessment, improvement programs often become expensive initiatives with limited long-term impact.

QMDSS helps answer one fundamental question:

> **"Where are we today, and what should we improve first?"**

Instead of relying on intuition, the system provides an evidence-based assessment supported by data analysis and executive reporting.

---

## Project Objectives

This project aims to:

- Assess organizational Quality Maturity
- Identify capability strengths and weaknesses
- Measure organizational similarity against maturity profiles
- Support evidence-based management decisions
- Prioritize improvement initiatives
- Visualize results through an Executive Power BI Dashboard

---

## Key Features

- 84-question Quality Maturity Assessment
- Automated Weighted Scoring Engine
- Capability Analysis
- Organization Level Analysis
- Similarity Analysis
- Executive Dashboard
- Management Report
- Improvement Prioritization
- Confidential Assessment Workflow

---

> **Important Notice**

This repository **implements** the Maturity Diagnostic Instrument (MDI) methodology as a practical analytics and decision-support solution.

The original MDI methodology is described in:

**Rocha-Lona, L., Garza-Reyes, J. A., & Kumar, V. (2013). Building Quality Management Systems: Selecting the Right Methods and Tools. Springer.**

This repository is **not** the original methodology. It is an implementation designed to automate assessment, analysis, visualization, and executive reporting.
# Business Problem

Organizations continuously invest in Quality Management Systems (QMS), Lean Manufacturing, Six Sigma, ISO Standards, Operational Excellence, and Continuous Improvement initiatives.

However, one critical question is often overlooked:

> **"Is the organization mature enough to successfully implement these initiatives?"**

Many organizations adopt advanced quality tools without first understanding the maturity of their management systems. As a result, improvement programs frequently suffer from:

- Poor leadership commitment
- Weak employee engagement
- Inconsistent implementation
- Misaligned strategic objectives
- Low return on investment (ROI)
- Initiative fatigue caused by adopting management "fads"

Without a structured maturity assessment, management decisions are often based on intuition rather than objective organizational evidence.

---

# Proposed Solution

The **Quality Maturity Decision Support System (QMDSS)** provides an evidence-based framework that converts organizational assessment data into executive insights.

Instead of generating only survey results, the system transforms assessment responses into:

- Organizational Maturity Profile
- Capability Assessment
- Similarity Analysis
- Executive Dashboard
- Management Report
- Improvement Priorities

The objective is not simply to measure quality maturity, but to support strategic decision-making using reliable organizational data.

---

# Scientific Foundation

This project is based on the **Maturity Diagnostic Instrument (MDI)** presented in:

> Rocha-Lona, L., Garza-Reyes, J. A., & Kumar, V. (2013). *Building Quality Management Systems: Selecting the Right Methods and Tools*. Springer.

The methodology itself is derived from internationally recognized research in Quality Management and Organizational Maturity, particularly the six-level maturity model developed by Dale and Lascelles.

This repository does **not** introduce a new maturity model.

Instead, it implements the published methodology as an integrated assessment and decision-support system.

---

# Why MDI?

The Maturity Diagnostic Instrument (MDI) was developed to help organizations objectively evaluate the maturity of their Quality Management System (QMS).

Rather than focusing only on compliance, the framework evaluates whether quality has become an integrated organizational capability.

The assessment measures three fundamental dimensions:

- Organizational practices
- Management capabilities
- Continuous improvement culture

The resulting maturity profile enables organizations to understand their current position before selecting future improvement initiatives.

---

# Organizational Maturity Levels

The methodology classifies organizations into six maturity levels:

| Level | Description |
|--------|-------------|
| Level 1 | Uncommitted |
| Level 2 | Drifters |
| Level 3 | Tool Pushers |
| Level 4 | Improvers |
| Level 5 | Award Winners |
| Level 6 | World-Class |

These maturity profiles provide a structured roadmap for long-term organizational development rather than focusing solely on short-term quality improvements.

---

# Assessment Principles

According to the original methodology, reliable maturity assessment depends on several key principles:

- Cross-functional participation
- Multiple organizational perspectives
- Structured evaluation criteria
- Standardized scoring methodology
- Consistent assessment teams over time

Following these principles reduces subjective bias and improves the reliability of assessment results.

---

# Assessment Team

The assessment should **not** be completed by the Quality Department alone.

The recommended approach is to form a **multidisciplinary assessment team** representing different functional areas and organizational levels.

Suggested participants include:

- Top Management
- Middle Management
- Quality
- Production
- Materials
- Human Resources
- Supervisors
- Shop-floor Operators

The original methodology recommends an assessment team consisting of approximately **six participants** representing different organizational functions.

Maintaining the same assessment team during future evaluations improves consistency and minimizes subjective variation between assessment cycles.

---

# Assessment Scale

The MDI assessment consists of **84 indicators** evaluated using a **7-point Likert scale**.

The scoring scale ranges from:

| Score | Interpretation |
|------:|----------------|
| 1 | Strongly Agree / Best Practice |
| 2 | Agree |
| 3 | Slightly Agree |
| 4 | Neutral |
| 5 | Slightly Disagree |
| 6 | Disagree |
| 7 | Strongly Disagree / Critical Weakness |

Assessment responses are subsequently processed through the analytical workflow implemented in this repository.

---

> **Implementation Note**

The scientific methodology belongs to the original authors.

This repository focuses on implementing the complete analytical workflow, including data processing, weighted scoring, capability analysis, similarity analysis, executive visualization, and management reporting.
# System Architecture

The **Quality Maturity Decision Support System (QMDSS)** follows a structured end-to-end analytical workflow that transforms organizational assessment responses into executive-level decision support.

The implementation consists of multiple processing stages, beginning with questionnaire design and ending with management reporting.

---

## High-Level Architecture

```text
                MDI Framework
                      │
                      ▼
        Questionnaire Development
                      │
                      ▼
      Assessment Data Collection
             (Porsline Survey)
                      │
                      ▼
          Excel Response Dataset
                      │
                      ▼
             Data Validation
                      │
                      ▼
        Weighted Scoring Engine
                      │
                      ▼
      ┌───────────────┼───────────────┐
      ▼               ▼               ▼
Capability       Organization      Similarity
 Analysis       Level Analysis      Analysis
      └───────────────┼───────────────┘
                      ▼
          Executive Power BI Dashboard
                      │
                      ▼
         Executive Management Report
                      │
                      ▼
        Data-Driven Management Decisions
```

---

# System Components

The system consists of seven analytical modules.

| Module | Description |
|----------|-------------|
| Questionnaire | MDI assessment questionnaire |
| Data Collection | Organizational responses collected through Porsline |
| Scoring Engine | Automated weighted scoring using Excel formulas |
| Analytical Engine | Capability, maturity level and similarity calculations |
| Visualization | Interactive Power BI dashboard |
| Reporting | Executive management report |
| Decision Support | Prioritized improvement recommendations |

---

# Data Pipeline

The project follows a structured data pipeline.

```text
Questionnaire
      ↓
Survey Responses
      ↓
Raw Excel Data
      ↓
Data Cleaning
      ↓
Weighted Calculations
      ↓
Capability Scores
      ↓
Organization Maturity
      ↓
Similarity Analysis
      ↓
Dashboard
      ↓
Management Report
```

---

# Analytical Workflow

The analytical engine performs the following sequence:

### 1. Import Assessment Data

Assessment responses are exported from the questionnaire platform and imported into the scoring engine.

---

### 2. Validate Data

The system verifies:

- Missing responses
- Invalid values
- Data consistency
- Assessment completeness

---

### 3. Calculate Weighted Scores

Each assessment indicator is processed according to the MDI scoring methodology.

The engine automatically calculates weighted values required for maturity analysis.

---

### 4. Capability Analysis

Individual capability scores are calculated to identify organizational strengths and weaknesses.

Example capability dimensions include:

- Leadership
- Strategy
- Customer Focus
- Quality Management System
- Continuous Improvement
- Process Management
- People Development
- Organizational Culture
- Quality Methods

---

### 5. Organization Level Analysis

Overall organizational maturity is calculated using the aggregated capability scores.

The result represents the organization's current maturity level.

---

### 6. Similarity Analysis

The system compares the organization's assessment profile against the six maturity profiles defined by the MDI methodology.

The closest maturity profile is identified using similarity scoring.

---

### 7. Executive Dashboard

Processed analytical data is visualized using Power BI.

The dashboard provides:

- Overall Maturity
- Capability Analysis
- Similarity Score
- Organizational Profile
- Improvement Priorities

---

### 8. Executive Report

The final stage produces an executive-level report designed to support management decision-making.

The report summarizes:

- Current maturity level
- Organizational strengths
- Capability gaps
- Critical weaknesses
- Recommended improvement priorities

---

# System Outputs

The project produces multiple business outputs.

| Output | Purpose |
|---------|----------|
| Executive Dashboard | Interactive management visualization |
| Capability Analysis | Identify organizational strengths and weaknesses |
| Organization Level | Overall maturity assessment |
| Similarity Analysis | Compare against maturity profiles |
| Management Report | Executive summary for decision-makers |
| Improvement Priorities | Support strategic planning |

---

# Design Philosophy

This project was designed with one objective:

> **Transform assessment data into executive decisions.**

Rather than producing static reports, the system creates actionable business intelligence that helps organizations understand where they are today and where improvement efforts should be focused first.

---

# End-to-End Workflow

```text
Scientific Framework
        ↓
Assessment
        ↓
Data
        ↓
Analysis
        ↓
Insight
        ↓
Decision
        ↓
Continuous Improvement
```
# Repository Structure

The project is organized into independent modules to separate data collection, analytical processing, visualization, documentation, and reporting.

```text
QMDSS/
│
├── README.md
│
├── docs/
│   ├── methodology.md
│   ├── workflow.md
│   ├── dashboard-guide.md
│   └── screenshots/
│
├── questionnaire/
│   ├── mdi-questionnaire.pdf
│   ├── porsline-template.pdf
│   └── questionnaire-structure.xlsx
│
├── sample-data/
│   ├── raw-responses.xlsx
│   ├── processed-data.xlsx
│   └── anonymized-dataset.xlsx
│
├── excel-engine/
│   ├── scoring-engine.xlsx
│   ├── capability-analysis.xlsx
│   ├── similarity-analysis.xlsx
│   └── organization-level.xlsx
│
├── powerbi/
│   ├── QMDSS.pbix
│   ├── data-model.png
│   └── dashboard-preview.png
│
├── reports/
│   ├── executive-report.pdf
│   ├── capability-report.pdf
│   └── improvement-priorities.pdf
│
├── images/
│   ├── architecture.png
│   ├── workflow.png
│   ├── dashboard.png
│   └── screenshots/
│
└── references/
    ├── bibliography.md
    └── citations.bib
```

---

# Project Modules

The repository consists of several independent modules, each responsible for a specific stage of the assessment process.

| Module | Purpose |
|----------|---------|
| questionnaire | Assessment design and survey structure |
| sample-data | Example assessment data (anonymized) |
| excel-engine | Scoring calculations and analytical models |
| powerbi | Dashboard and visualization |
| reports | Executive reporting |
| docs | Technical documentation |
| images | Repository figures and screenshots |
| references | Scientific references |

---

# Folder Description

## docs/

Contains the complete project documentation, workflow explanation, methodology overview, and dashboard guide.

---

## questionnaire/

Contains the assessment questionnaire and supporting documents used to collect organizational responses.

The questionnaire is derived from the MDI framework described in the referenced publication.

---

## sample-data/

Contains anonymized demonstration datasets.

These files are provided exclusively for educational and demonstration purposes.

No confidential organizational information is included.

---

## excel-engine/

This folder contains the analytical core of the project.

The Excel Scoring Engine performs:

- Data validation
- Weighted scoring
- Capability calculations
- Organization maturity calculations
- Similarity calculations

This module transforms raw questionnaire responses into structured analytical outputs.

---

## powerbi/

Contains the Power BI report used for executive visualization.

The dashboard provides an interactive view of:

- Overall Maturity
- Capability Analysis
- Organization Profile
- Similarity Analysis
- Executive KPIs
- Improvement Priorities

---

## reports/

Contains executive reports generated from the processed assessment data.

Typical outputs include:

- Executive Summary
- Organizational Strengths
- Capability Gaps
- Recommended Improvement Priorities

---

## images/

Repository images used throughout the documentation.

These include:

- Dashboard screenshots
- Workflow diagrams
- Architecture diagrams
- Illustrations

---

## references/

Contains scientific references supporting the methodology implemented in this project.

The implementation follows published research and does not replace the original scientific work.

---

# Confidentiality

This repository includes a demonstration project based on a real organizational assessment.

To protect organizational confidentiality:

- Company names have been removed.
- Participant identities have been anonymized.
- Sensitive operational information has been excluded.
- The published dataset is intended solely to demonstrate the analytical workflow.

---

# Design Principles

The repository has been designed according to the following principles:

- Modularity
- Reproducibility
- Transparency
- Scientific Traceability
- Executive Usability
- Confidentiality

Each module can be updated independently without affecting the overall analytical workflow.
# Implementation Guide

This section describes the recommended implementation workflow for applying the Quality Maturity Decision Support System (QMDSS) within an organization.

The workflow follows the principles of the Maturity Diagnostic Instrument (MDI) while extending the methodology through automated scoring, analytics, visualization, and executive reporting.

---

# Implementation Workflow

The implementation consists of eight sequential stages.

```text
Planning
      ↓
Assessment Team
      ↓
Questionnaire
      ↓
Data Collection
      ↓
Scoring Engine
      ↓
Data Analytics
      ↓
Executive Dashboard
      ↓
Management Decisions
```

---

# Step 1 — Prepare the Assessment

Before conducting the assessment, management should define the scope of the evaluation.

Typical assessment objectives include:

- Understanding current Quality Maturity
- Identifying organizational capability gaps
- Supporting strategic planning
- Prioritizing improvement initiatives

The assessment should represent the organization as a whole rather than evaluating a single department.

---

# Step 2 — Form the Assessment Team

According to the MDI methodology, the assessment should be completed by a multidisciplinary team.

Recommended participants include:

- Executive Management
- Middle Management
- Quality
- Production
- Materials
- Human Resources
- Supervisors
- Shop-floor Operators

Recommended team size:

> Approximately **six participants** representing different organizational functions.

Using the same team during future assessments improves consistency and reduces subjective variation.

---

# Step 3 — Complete the Assessment

Participants complete the MDI questionnaire individually.

The assessment contains:

- 84 assessment indicators
- 7-point Likert scale
- Organizational capability evaluation

Each participant should answer independently based on current organizational practices rather than desired future conditions.

---

# Step 4 — Export Assessment Data

After the assessment is completed, export all responses from the survey platform.

Supported format:

- Microsoft Excel (.xlsx)

The exported dataset becomes the input for the analytical workflow.

---

# Step 5 — Import into the Scoring Engine

Load the exported assessment file into the Excel Scoring Engine.

The scoring engine automatically performs:

- Response validation
- Missing value detection
- Weighted score calculation
- Capability aggregation
- Organizational maturity calculation
- Similarity calculation

No manual calculations are required.

---

# Step 6 — Generate Analytical Results

After processing the assessment data, the system automatically generates analytical outputs including:

## Overall Maturity

Represents the current maturity level of the organization.

---

## Capability Analysis

Identifies strengths and weaknesses across organizational capabilities.

---

## Organization Level Analysis

Determines the organization's maturity profile.

---

## Similarity Analysis

Compares organizational results against the six maturity profiles defined in the MDI methodology.

The profile with the highest similarity score represents the organization's current maturity classification.

---

# Step 7 — Load Data into Power BI

Import the processed analytical dataset into Power BI.

The dashboard automatically visualizes:

- Overall Maturity
- Current Maturity Profile
- Capability Analysis
- Similarity Score
- Organizational Strengths
- Organizational Weaknesses
- Executive KPIs
- Improvement Priorities

The dashboard is designed specifically for executive decision support.

---

# Step 8 — Executive Review

The final deliverable is an Executive Management Report.

The report summarizes:

- Current organizational maturity
- Capability strengths
- Critical weaknesses
- Highest-risk capabilities
- Improvement priorities
- Strategic recommendations

Management should use these findings to prioritize improvement initiatives based on organizational readiness rather than intuition.

---

# Assessment Frequency

Although assessment frequency depends on organizational objectives, periodic reassessment is recommended to monitor progress over time.

Using the same assessment methodology and a consistent multidisciplinary team improves comparability between assessment cycles.

---

# Expected Deliverables

At the end of each assessment cycle, the following deliverables are produced:

- Completed Assessment Dataset
- Weighted Scoring Results
- Capability Analysis
- Organization Level Analysis
- Similarity Analysis
- Executive Power BI Dashboard
- Executive Management Report

---

# Demonstration Case

This repository includes one demonstration project created from a real organizational assessment.

To protect confidentiality:

- Company names have been removed.
- Individual identities have been anonymized.
- Sensitive organizational information has been excluded.

The published example is intended solely to demonstrate the implementation workflow and analytical capabilities of the system.

---

# Best Practices

For the most reliable results:

- Form a multidisciplinary assessment team.
- Encourage honest and independent responses.
- Avoid completing the questionnaire as a group discussion.
- Preserve the original response dataset.
- Use consistent assessment criteria across evaluation cycles.
- Repeat assessments periodically to measure organizational progress.

Following these practices improves reliability, minimizes subjective bias, and enables meaningful comparison over time.
