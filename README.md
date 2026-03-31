# Reducing Inspection Risk Across NYC Restaurant Operations

## Overview
Poor inspection outcomes can damage brand trust and increase operational risk. This project analyzes ~296K inspection records to reduce inspection risk, avoid grade drops, and protect brand reputation. 

## Objective
Which violation patterns, cuisines, boroughs, and time periods are associated with worse inspection outcomes?

## Tools Used
- **Python** (Pandas, NumPy) for data cleaning and manipulation
- **Jupyter Notebook** for exploratory data analysis
- **Tableau** for data visualization and presentation

## Process
1. **Data Collection** – Sourced dataset from NYC Open Data - DOHMH Restaurant Inspection Results.
2. **Data Cleaning** – Removed duplicate records and excluded irrelevant location and administrative fields.
3. **Feature Engineering** – Grouped granular violation descriptions into broader categories such as sanitation, pests, temperature, and food safety.
4. **Analysis** – Evaluated variables including borough, cuisine type, inspection date, score, grade, and violation details.

## Violation Categories & Scores

![Violation Categories](images/5.png)

**Key Highlights:**
- Sanitation and pests are the most frequent violations.
- Temperature and Food Safety score the highest when they occur (avg 27-28).
- A lower inspection score is better, with scores of 0-13 earning an A grade.

## Geographical Distribution

![Violations by Borough](images/8.png)

**Key Findings:**
- Interestingly, boroughs have similar inspection scores.
- Violation types trend consistently throughout NY Boroughs.
- The top three violations across the board are Sanitation, Pests, and Temperature.

## Temporal Trends

![Inspection Trends](images/11.png)

**Key Findings:**
- Inspection levels stayed relatively stable until 2021.
- There was a sharp increase in inspections beginning in 2022.
- Higher inspection activity leads to more violations being identified
