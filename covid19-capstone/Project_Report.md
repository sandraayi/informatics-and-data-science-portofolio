# COVID-19 Predictive Modeling Capstone Project

**Author:** Sandra Sefakor Ama Ayi  
**Program:** Health Informatics / Data Science  
**Institution:** University of Illinois Chicago (UIC)  
**Project Type:** Capstone – Machine Learning & Clinical Informatics  
**Dataset Source:** Hospital Israelita Albert Einstein, São Paulo, Brazil (public dataset)

---

## 🎯 Objective

This project aimed to build a machine learning model that predicts whether a patient is likely to test positive for COVID-19 based on routine laboratory test results and clinical admission data. The motivation was to assist in **early screening and triage**, especially in **resource-limited environments** where universal PCR testing is not feasible.

---

## 📊 Dataset Overview

- **Patients:** 5,644 unique individuals
- **Features:** Lab values (e.g., leukocytes, hematocrit), age quantile, hospital ward admission, co-infection test results
- **Labels:** SARS-CoV-2 test result (positive/negative)

---

## ⚙️ Machine Learning Methods

Four models were trained and evaluated:

- Decision Tree (tuned)
- Random Forest
- AdaBoost
- Gradient Boosted Machine (GBM)

The final selected model was the **tuned Decision Tree**, chosen for its **high recall rate**, making it ideal as a screening tool.

### 📈 Final Model Metrics

| Metric      | Value   |
|-------------|---------|
| Recall      | 0.868   |
| Accuracy    | 0.402   |
| Precision   | 0.128   |
| F1 Score    | 0.223   |

---

## 🔍 Key Features Used in Prediction

1. Patient Age Quantile  
2. Leukocyte Count  
3. Hematocrit  
4. Hospital Ward Admission  
5. Rhinovirus/Enterovirus Test  
6. Influenza B Test  

---

## 🧠 Clinical and Public Health Insights

- **High Recall**: Ensures most COVID-positive cases are flagged for follow-up testing or isolation.
- **Low Precision**: Acceptable for early screening since false positives can be safely retested.
- **Data-Driven Triage**: Improves care delivery in hospitals with limited testing capacity.
- **Adaptable Model**: Can be retrained with local data for greater accuracy.

---

## 🏥 Implementation Considerations

### ✅ Benefits
- Reduces testing burden  
- Speeds up triage and isolation  
- Protects healthcare workers  
- Informs public health strategies  

### ⚠️ Challenges
- Requires reliable data infrastructure  
- Needs integration with hospital EHRs  
- Generalizability may vary by setting  
- Continuous validation and oversight required

---

## 📁 Files Included

- `COVID19_Prediction_Notebook.ipynb` – Jupyter Notebook with full model development
- `README.md` – This project summary
- `Dataset.csv` – Public dataset used for training (not redistributed here; available on Kaggle)
- `Model_Outputs/` – Charts and evaluation metrics

---

## 📎 Data Source

The dataset was released by [Hospital Israelita Albert Einstein](https://www.kaggle.com/datasets/einsteindata4u/covid19) and is publicly available on Kaggle. It has been anonymized and is intended for educational and research purposes.

---

## ✅ Conclusion

This project demonstrates how clinical informatics and machine learning can be used to address urgent healthcare needs. By leveraging routine lab data, hospitals can implement **proactive screening tools** that enhance pandemic response and optimize limited resources.

