#  Migration and Unemployment Analysis in Europe

This project investigates the relationship between **migration rates** and **unemployment levels** across European countries using official datasets from **Eurostat** and **OECD**. The analysis was conducted as part of the **YZV211E - Term Project**.

---

##  Project Summary

Migration and unemployment are two deeply intertwined socio-economic phenomena. This project explores whether migration inflows have a measurable impact on unemployment rates across Europe, and if this relation can be modeled or predicted using historical data.

---

##  Objectives

- Analyze the **correlation** between migration rates and unemployment levels
- Study **country-specific patterns** and variations
- Use statistical and time series models to evaluate predictive power
- Identify **policy insights** based on the findings

---

##  Datasets Used

- **Eurostat Unemployment Dataset** (2012–2023): Annual unemployment rates
- **OECD International Migration Database**: Migration inflows, demographics
- **Eurostat Population Dataset** (2013–2024): Country-level population data

---

##  Data Preparation

- Normalized migration numbers into **percentages** using population data
- Harmonized inconsistent **country code formats** using a JSON mapping
- Created a combined dataset with:
  - Country
  - Year
  - Migration Rate (%)
  - Unemployment Rate (%)

---

##  Research Questions

1. Is there a correlation between migration rates and unemployment?
2. Do countries with higher migration inflows experience significant unemployment shifts?
3. Are migration changes linked to long-term unemployment trends?
4. Can historical data predict future migration and unemployment?

---

## Key Findings

- **Correlation** between migration and unemployment: **-0.55**
  - Suggests an **inverse relationship** (higher migration, lower unemployment)
- **High-migration countries** (e.g., Luxembourg, Iceland, Germany) did **not** show significant unemployment change
- Relationship appears **short-term**, not long-term
- **SARIMA-based forecasting failed** to capture nonlinear dynamics effectively

---

## Visual Analysis

Graphs and statistical plots were created using Python (pandas, seaborn, matplotlib). Key visualizations include:

- Correlation matrix
- Country-wise scatter plots
- Year-wise line graphs
- SARIMA prediction results

---

## Challenges

- Merging heterogeneous datasets with different formats and time ranges
- Dealing with missing and inconsistent entries
- Predictive modeling under limited data and external factors

---

## Ethical Considerations

- Avoiding **bias** and **misinterpretation** in migration data
- Ensuring **privacy** and ethical usage of country-level statistics
- Transparent communication to prevent xenophobic narratives

---

## Proposed Tools

- **Policy Insights Platform**: Real-time analytics dashboard
- **Economic Impact Dashboard**: Interactive tool for migration-labor trends

---

## Contributors

- **Ömer Faruk San** - 150220307  
- **Abdullah Vefa Yankın** - 150220318  
- **Mustafa Kerem Bulut** - 150220303  

Department of AI and Data Engineering  
Istanbul Technical University

---

## Contact

For questions or collaboration:

📧 san22@itu.edu.tr
