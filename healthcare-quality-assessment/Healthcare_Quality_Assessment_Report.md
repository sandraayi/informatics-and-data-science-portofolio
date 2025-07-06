
# 🏥 Healthcare Quality Assessment Project

## Project Objective
This project involved analyzing a de-identified hospital discharge dataset as part of a simulated quality improvement (QI) initiative.  
The goal was to assess hospital readmission rates and length of stay (LOS) trends across two Midwest facilities—**Center A** and **Center B**—and to explore the data quality, completeness, and operational insights that could inform care improvements.

---

## Data Cleaning and Processing
The dataset required extensive preprocessing:
- **Find and Replace** was used to standardize inconsistent text entries
- **Custom number formats** ensured 9-digit identifiers
- Missing or invalid entries were labeled as `'Null'`
- **DATEDIF** function calculated LOS and time to procedure
- Illogical negative values highlighted potential data entry errors or clinical complications

---

## Facility Summary Metrics

| Facility ID | Medical Center | Average LOS (days) | Readmission Rate (%) | Total Discharges |
|-------------|----------------|---------------------|------------------------|-------------------|
| 5           | Center A       | 4.94                | 13.6                   | 884               |
| 8           | Center B       | 4.3                 | 11.5                   | 408               |

---

## Key Findings
- Center A  had 88 readmissions;Center B had 47  
- Dataset included 650 total admissions (55.03% male, 44.97% female)  
- Some **Time-to-Procedure** values were illogical, occurring *before* admission  
- The **Charlson Comorbidity Index (CCI)** was inconsistently applied and often missing

---

## Analytical Techniques
Analysis was performed using **Microsoft Excel**, incorporating:
- `VLOOKUP` for merging datasets
- `DATEDIF` for LOS calculations
- Logical filters and quality assurance steps to identify anomalies and missing data

---

## Conclusion
This project simulates real-world hospital data challenges commonly addressed in quality improvement.  
It demonstrates **Sandra Sefakor Ama Ayi’s** ability to handle messy clinical data, apply analytical logic, and produce insight-rich reports.  
The project is included in her **ERAS portfolio** to showcase her growing research and informatics competence.

