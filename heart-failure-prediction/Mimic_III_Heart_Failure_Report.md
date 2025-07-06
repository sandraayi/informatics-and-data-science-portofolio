# 🫀 Predicting In-Hospital Mortality in Heart Failure Patients Using Machine Learning

**Sandra Sefakor Ama Ayi, MSHI**  
*Capstone Project | BHIS 561: Programming for Health Analytics*  
*University of Illinois at Chicago | August 2024*

## 📌 Project Overview  
This project used machine learning methods to identify predictors of in-hospital mortality among heart failure patients admitted to the ICU. Using real-world clinical data from the MIMIC-III database, I applied exploratory data analysis (EDA), statistical preprocessing, and predictive modeling to support early risk stratification in a critical care setting.

## 🧠 Clinical Context  
Heart failure affects over 6.7 million adults in the U.S. and contributes significantly to hospitalizations and in-hospital deaths. As a physician, I recognized the potential of data science to enhance clinical decision-making in high-stakes environments. This project bridges informatics with frontline care by developing an evidence-based, data-driven approach to predicting patient outcomes.

## 🎯 Objectives  
- Perform exploratory data analysis on a cohort of 1,177 ICU-admitted heart failure patients  
- Identify clinical and laboratory predictors of mortality  
- Build and evaluate machine learning models to predict in-hospital death vs. survival

## 🩺 Key Findings  
- **Mortality rate:** 13.5% (159 of 1177 patients)  
- **Significant comorbidities among non-survivors:** Atrial fibrillation, diabetes, renal failure  
- **Top 20 predictors included:** Systolic/diastolic BP, BMI, blood pH, electrolyte values, depression, COPD, and comorbid cardiovascular conditions  
- **Best performing model:** Logistic Regression  
  - Accuracy: 90%  
  - Recall: 100% for survivors  
  - Limitation: Poor sensitivity for mortality due to class imbalance

## 🧪 Methodology  
- Data sourced from MIMIC-III (a de-identified ICU database)  
- Missing data handled via median/mode imputation  
- Outliers removed conservatively  
- Algorithms: Logistic Regression, Decision Tree, and Random Forest  
- Performance assessed using confusion matrices, precision, recall, and F1-score

## ⚠️ Limitations  
- **Class imbalance**: Fewer mortality cases affected model training  
- **Outlier exclusion**: Some biologically meaningful values may have been excluded

## 💡 Clinical Relevance  
This work reflects my commitment to leveraging clinical informatics for quality improvement and patient-centered care. While the predictive models had limited power to identify mortality, they were effective in stratifying patients likely to survive, enabling earlier interventions and efficient ICU resource allocation.

## 🔗 Related Links  
- 📄 [Final Jupyter Notebook](./SANDRA%20SEFAKOR%20AMA%20AYI%20Covid-19%20Capstone%20Project%20Final%20Notebook.ipynb)  
- 📊 [LOS Analysis Table (CSV)](https://github.com/sandraayi/informatics-and-data-science-portofolio/blob/main/healthcare-quality-assessment/LOS_Analysis_Table.csv)  
- 📂 [Main Portfolio Repository](https://github.com/sandraayi/informatics-and-data-science-portofolio)
