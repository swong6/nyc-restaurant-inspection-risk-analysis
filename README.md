# Reducing Inspection Risk Across NYC Restaurant Operations

## Overview
[cite_start]Poor inspection outcomes can damage brand trust and increase operational risk[cite: 323]. [cite_start]This project analyzes ~296K inspection records to reduce inspection risk, avoid grade drops, and protect brand reputation[cite: 319, 335].

## Objective
[cite_start]Which violation patterns, cuisines, boroughs, and time periods are associated with worse inspection outcomes? [cite: 321]

## Tools Used
- **Python** (Pandas, NumPy) for data cleaning and manipulation
- **Jupyter Notebook** for exploratory data analysis
- **Tableau** for data visualization and presentation

## Process
1. [cite_start]**Data Collection** – Sourced dataset from [NYC Open Data - DOHMH Restaurant Inspection Results](https://data.cityofnewyork.us/Health/DOHMH-New-York-City-Restaurant-Inspection-Results/43nn-pn8j/about_data)[cite: 332].
2. [cite_start]**Data Cleaning** – Removed duplicate records and excluded irrelevant location and administrative fields[cite: 338, 339].
3. [cite_start]**Feature Engineering** – Grouped granular violation descriptions into broader categories such as sanitation, pests, temperature, and food safety[cite: 340, 341].
4. [cite_start]**Analysis** – Evaluated variables including borough, cuisine type, inspection date, score, grade, and violation details[cite: 336].

## Violation Categories & Scores
![Violation Categories](images/5.png)

**Key Highlights:**
- [cite_start]Sanitation and pests are the most frequent violations[cite: 570].
- [cite_start]Temperature and Food Safety score the highest when they occur (avg 27-28)[cite: 577].
- [cite_start]A lower inspection score is better, with scores of 0-13 earning an A grade[cite: 387, 390].

## Geographical Distribution
![Violations by Borough](images/8.png)

**Key Findings:**
- [cite_start]Interestingly, boroughs have similar inspection scores[cite: 507].
- [cite_start]Violation types trend consistently throughout NY Boroughs[cite: 495].
- [cite_start]The top three violations across the board are Sanitation, Pests, and Temperature[cite: 497, 499, 500].

## Temporal Trends
![Inspection Trends](images/11.png)

**Key Findings:**
- [cite_start]Inspection levels stayed relatively stable until 2021[cite: 538].
- [cite_start]There was a sharp increase in inspections beginning in 2022[cite: 539].
- [cite_start]Higher inspection activity leads to more violations being identified across multiple categories[cite: 540, 541].

## Key Insights
- [cite_start]✅ **Cuisine Predictors:** Indian (31.7), Caribbean/African (29.7), and Chinese (29.0) score far worse than Fast Food (20.7) and Cafe/Bakery (21.6)[cite: 585].
- [cite_start]✅ **Violation Consistency:** Sanitation, pests, temperature, and food safety make up the majority of inspection issues[cite: 572].
- [cite_start]✅ **Geography is Secondary:** Cuisine type and repeat violation patterns are stronger predictors of outcomes than geography[cite: 603].

## Conclusion & Recommendations
[cite_start]Violation risk is predictable[cite: 602]. [cite_start]By focusing on targeted training, proactive audits, and predictive monitoring of high-risk locations, the organization can significantly improve inspection scores and strengthen its compliance culture[cite: 604].

- [cite_start]**Target High-Risk Violations:** Sanitation and Pests are the most frequent violations[cite: 577, 610]. [cite_start]Targeted training and kitchen checklists focused here have the biggest chain-wide impact[cite: 578].
- [cite_start]**Shift to Proactive Compliance:** Most violations flagged by city inspectors are operational issues catchable earlier[cite: 580, 611]. [cite_start]Implement monthly internal audits using the official inspection framework so restaurants can fix problems before the city does[cite: 581].
- [cite_start]**Prioritize High-Risk Cuisines:** Direct more compliance resources to higher-risk cuisine formats like Indian, Caribbean/African, and Chinese[cite: 585, 586, 611].
- [cite_start]**Develop an Early Warning Risk Score:** Analyze past violations, scores, and repeat patterns by location to flag restaurants most likely to underperform and intervene early with targeted training or internal audits[cite: 587].

## Deliverables
- **Jupyter Notebook** – Complete data cleaning and exploratory data analysis workflow.
- **Presentation Slides** – Executive summary, geographical visualizations, and strategic recommendations.

## Files
| File | Description |
|------|-------------|
| `Data_Cleaning_Analysis.ipynb` | Python notebook detailing the data processing, cleaning, and categorization |
| `Presentation Slides.pdf` | Executive presentation with visual insights and business recommendations |
| `images/` | Directory containing supporting visualizations used in this documentation |
| `README.md` | This documentation file |

---

**Note:** This project was completed during my Master of Science in Business Analytics program, demonstrating the application of data cleaning, exploratory analysis, and visualization to solve operational risks and protect brand reputation.
