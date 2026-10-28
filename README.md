
# DATA 499 Capstone — Supplier Opportunity Analysis

## Project Overview

This capstone project focused on identifying and ranking potential supplier opportunities for sales outreach using internal transaction data and external API data.

Our team developed a data processing pipeline, performed exploratory and statistical analysis, engineered features, and evaluated multiple ranking methodologies to identify organizations with the greatest potential for outreach.

**This repository contains only the final capstone presentation.** The presentation has been scrubbed of organizational, customer, and personal data to protect confidentiality. The underlying datasets, source code, and organizational information are not included.

## Project Objectives

### 1. API Data Processing Pipeline

- Integrated internal customer and transaction data with external API data.
- Cleaned, validated, filtered, and deduplicated records.
- Combined data sources to prepare a consistent dataset for analysis.

### 2. Feature Engineering, Modeling, and Data Exploration

- Engineered features including Store Gap, unique item counts, and organization-size measures.
- Applied log transformations and exploratory data analysis to investigate distributions and relationships.
- Used correlation analysis to identify patterns relevant to supplier opportunities.

### 3. Supplier Ranking Methodology

- Evaluated multiple weighted scoring approaches using operational and transaction-based metrics.
- Developed a final ranking methodology using percentile ranks for Store Gap and average monthly document flow.
- Applied a weighted composite score:
  - **60%** Store Gap Rank
  - **40%** Document Flow Rank
- Prioritized organizations with the greatest potential for additional retailer connections.

## Results

The final analytical dataset included:

- **2,505 organizations** evaluated for ranking.
- **50,426 unique items** and **122,706 unique offers**.
- A ranked list of the **top 100 supplier outreach opportunities**.

The final methodology provided a structured, data-driven approach to identifying organizations with potential opportunities for additional retailer connections.

## Tools & Techniques

- Python
- SQL
- API Data Extraction
- Data Cleaning and Validation
- Data Processing Pipelines
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Correlation Analysis
- Log Transformations
- Weighted Scoring and Percentile Ranking

## Repository Contents

This repository contains the final project presentation, documenting:

1. API data processing and integration.
2. Feature engineering, modeling, and exploratory analysis.
3. Supplier ranking methodology and results.

## Confidentiality

The presentation has been scrubbed of organizational, customer, and personal data. The underlying datasets and source code are not publicly available.

**Note:** This was a collaborative capstone project. The presentation represents the work of the project team.

