# NHS Operational Performance BI Project (Tableau)

## Overview
This repository contains a Business Intelligence (BI) analysis project focused on operational pressures within the UK National Health Service (NHS). It investigates how analytics and BI can support evidence-based decision-making by analysing performance indicators such as waiting times, bed occupancy, and workforce metrics. The project transforms publicly available NHS data (and synthetically generated operational data where required) into dashboards and insights to support demand forecasting, resource optimisation, and performance improvement.

> **Note:** No identifiable NHS staff/patient data or clinical records are used. Where operational scenarios are required beyond public reporting, synthetic data is created to simulate realistic conditions.
<img width="2900" height="1585" alt="Screenshot 2026-01-28 180839" src="https://github.com/user-attachments/assets/8eb1a993-4c07-46ad-a844-093a91a6badf" />

---

## Project Objectives
- Analyse trends in NHS waiting lists and waiting time distributions over time.
- Explore relationships between bed occupancy and patient waiting list size.
- Evaluate A&E 4-hour target performance trends and potential operational drivers.
- Identify elective backlog hotspots by treatment function/specialty.
- Examine workforce vacancy and sickness absence trends and their operational implications.
- Demonstrate how BI can reduce business–IT misalignment by improving data visibility and performance monitoring.

---

## Research Questions
1. What is the current average patient waiting list across NHS Trusts, and how has this changed over the past three years?
2. How does hospital bed occupancy rate correlate with patient waiting list size in different regions of England?
3. How has A&E performance changed across NHS Trusts, and what factors influence 4-hour target compliance?
4. Which clinical departments or specialties show the largest elective care backlog, and how do staffing levels correlate with delays?
5. How do fluctuations in NHS vacancy rates impact service delivery and patient outcomes across regions and specialties?
6. How do seasonal and annual sickness absence trends impact workforce planning and service delivery capacity?

---


---

## Data Sources (Secondary Data)
This project uses publicly accessible and aggregated NHS-related datasets where available, such as:
- NHS England operational and performance statistics (e.g., waiting lists, A&E performance).
- NHS Digital or equivalent open/statistical publications (where relevant to the analysis scope).
- National/official statistics related to capacity, workforce, or sickness absence.

---

## Synthetic Data (If Applicable)
Where public data does not provide sufficient granularity for demonstration (e.g., simulating patient flow patterns or operational scenarios), synthetic datasets are generated based on:
- generalised assumptions from academic literature, and
- patterns consistent with publicly reported NHS statistics.

Synthetic data contains **no real patient information** and is used only for prototyping and demonstration.

---

## Methodology (High-Level)
1. **Data collection** from official/public NHS sources.
2. **Data cleaning and transformation** (removing duplicates, handling missing values, standardising formats).
3. **Dashboard development** in Tableau to visualise KPIs and trends.
4. **Analysis** using descriptive and diagnostic analytics (trend identification and interpretation).
5. **Interpretation** to produce actionable insights for operational performance improvement.

See `docs/methodology.md` for full details.

---

## Ethical Considerations
- Only **publicly available, aggregated** data is used.
- No primary data is collected from NHS staff or patients.
- No clinical or identifiable personal data is processed.
- Analysis aims to be objective, transparent, and avoids misrepresentation of NHS performance.

---

## Tools
- Tableau for data analysis, visualisation, and dashboard creation.
- Spreadsheet tools (e.g., Excel) for data preparation and cleaning.

---

## Results Summary (What You’ll Find)
The dashboards and analysis highlight:
- sustained pressure in waiting lists and long-wait cohorts,
- a relationship between high bed occupancy and reduced operational flexibility,
- declining A&E 4-hour performance over time,
- specialist elective backlogs concentrated in specific treatment functions,
- workforce vacancy and sickness absence patterns that impact service capacity.

## Author
- **Name:** [Abram De Guzman]
- **Course:** Business Information Systems
- **Institution:** [Cardiff Metropolitan University]
- **Year:** [2026]
