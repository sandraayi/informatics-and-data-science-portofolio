
# Healthcare Quality Assessment Project

## Project Objective

This project involved analyzing a de-identified hospital discharge dataset as part of a simulated quality improvement (QI) initiative. The goal was to assess hospital readmission rates and length of stay (LOS) trends across two Midwest facilities - Center A and Center B - and to explore the data quality, completeness, and operational insights that could inform care improvements.

## Data Cleaning and Processing

The dataset required extensive preprocessing. The 'Find and Replace' tool was used to standardize inconsistent text entries. To enforce formatting rules, the custom number format tool in Excel was applied to ensure consistent 9-digit identifiers. Missing and invalid entries were identified, and blanks were explicitly labeled as 'Null' to avoid downstream formula errors. The DATEDIF function was used to calculate the 'Length of Stay' and 'Time to Procedure' variables. Unexpected negative values suggested either complications leading to readmission or potential data entry errors.

## Facility Summary Metrics

| Facility ID | Medical Center | Average LOS (days) | Readmission Rate (%) | Total Discharges |
|-------------|----------------|---------------------|------------------------|-------------------|
| 5           | Center A       | 4.94                | 13.6                   | 884               |
| 8           | Center B       | 4.3                 | 11.5                   | 408               |

## Key Findings

- Center A had 88 readmissions; Center B had 47. However, these figures may be underreported due to missing values in the readmission column.
- The dataset included 650 total admissions, with male patients comprising 55.03% and female patients 44.97%.
- Time-to-Procedure values were not always logical; in some cases, procedures were recorded before admission, indicating possible complications or data errors.
- The Charlson Comorbidity Index (CCI) was inconsistently applied, with several missing values undermining its usefulness as a comparative metric.

## Analytical Techniques

Data analysis was performed using Microsoft Excel. Functions such as VLOOKUP enabled merging of comorbidity scores and facility names. Logical reasoning and quality assurance methods were employed to ensure calculated fields, like LOS and readmission counts, were valid and interpretable.

## Conclusion

This project simulated real-world data challenges encountered in quality improvement initiatives. The findings point to both opportunities for operational insights and the importance of data analytics in enhancing hospital management and improving healthcare performance indices.
