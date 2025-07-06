# COVID‑19 Predictive Testing Using Routine Lab Data  
**Capstone Project – UT Austin PGP-DSBA/Great Learning**

## Summary  
Developed machine learning models to predict COVID‑19 test outcomes using routine blood parameters. This project aimed to support rapid triage decisions in clinical settings where molecular testing was delayed or limited.

## Key Highlights  
- Utilized a publicly available dataset (originally released by Hospital Israelita Albert Einstein, São Paulo, Brazil) with anonymized clinical lab data and COVID-19 RT-PCR test results  
- Conducted extensive data preprocessing including handling of missing values, normalization, and outlier detection  
- Explored variable distributions and correlations across hematologic parameters (e.g., leukocytes, lymphocytes, eosinophils)  
- Built and evaluated several ML models:
  - Random Forest (best performing)
  - Decision Tree
  - Logistic Regression
- Evaluated models using accuracy, ROC-AUC, precision, and recall  
- Visualized key patterns using heatmaps, boxplots, and confusion matrices  
- Interpreted feature importance to identify lab variables most predictive of COVID-19 positivity  
- Documented clinical implications for resource-limited triage workflows

## Tools Used  
Python, scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Clinical Relevance  
This project demonstrates the feasibility of using routine bloodwork and machine learning to guide COVID-19 testing decisions, especially in overwhelmed or under-resourced healthcare settings. The approach offers insights for scalable, non-invasive diagnostic support during public health emergencies.

## Files in This Folder  
- `covid19_model.ipynb` – Complete code with step-by-step analysis  
- `covid19_model.html` – Read-only web-friendly version  
