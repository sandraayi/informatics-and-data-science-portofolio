# 👶🏽 Fetal Monitoring Predictive Analysis Using Cardiotocogram (CTG) Data

**Sandra Sefakor Ama Ayi, MSHI**  
*University of Illinois at Chicago — Programming for Health Analytics*

## 🧠 Background  
Timely recognition of fetal distress is critical in obstetric care. Cardiotocography (CTG) is widely used for monitoring fetal well-being, yet its interpretation is often subjective and varies across providers. In this project, I applied predictive modeling to CTG data to classify fetal outcomes—supporting a more objective, data-driven approach to fetal assessment.

## 🎯 Objective  
To analyze CTG data and develop machine learning models that classify fetal health status (normal, suspicious, pathological), with the goal of aiding early intervention and reducing preventable perinatal complications.

## 🩺 Clinical Relevance  
As a physician, this project reflects my commitment to using clinical informatics to strengthen diagnostic precision. By translating complex fetal monitoring data into actionable insights, this work supports obstetric decision-making and may improve outcomes in high-volume labor wards.

## 🔍 Dataset  
- **Source:** Ayres-de-Campos et al., 2000  
- **Sample size:** 2,126 CTG recordings  
- **Features analyzed:** 22 clinical variables including FHR baseline, accelerations, decelerations, variability patterns, and histogram trends  
- **Outcome categories:**  
  - 77.9% Normal  
  - 13.8% Suspect  
  - 8.3% Pathological

## 🧪 Methods  
- Exploratory data analysis and statistical testing (ANOVA)  
- Feature selection based on clinical and statistical significance  
- Predictive modeling using:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
- Model evaluation using accuracy, precision, recall, and F1-score

## ✅ Key Findings  
- **Top predictors**:  
  - Abnormal short-term variability  
  - Fetal movements  
  - Uterine contractions  
  - Light and severe decelerations  
- **Best performing model**: Random Forest  
  - Accuracy: 90%  
  - Precision: 93%  
  - Recall: 97%  
  - F1-score: 95%

## 💡 Insights  
From my analysis, I observed that:
- Fetuses with pathological outcomes showed markedly higher levels of abnormal short-term variability and severe decelerations.
- Suspicious outcomes were associated with elevated baseline fetal heart rates, often above 140 bpm.
- Normal outcomes corresponded with stable variability patterns and more frequent accelerations, suggesting resilience.
- The Random Forest model outperformed others by capturing complex, non-linear interactions between features—making it especially promising for integration into real-time fetal monitoring systems.

## 📌 Conclusion  
This project demonstrates how clinical data can be transformed into practical tools for real-time decision support. The models developed—especially the random forest classifier—effectively predicted fetal outcomes and may assist in reducing variability in CTG interpretation and enhancing perinatal care.

---

## 🔗 Project Files  
- 📓 [Notebook: Predictive Analysis of CTG Data](./BHIS561_Unit07_Assignment_01_Sandra_Ayi.ipynb)  
- 📄 [Exploratory Report (Word)](./BHIS561_Unit07_Assignment01_Sandra_Ayi.docx)

> *This project is part of my applied informatics portfolio developed during my Master of Science in Health Informatics at the University of Illinois at Chicago. It reflects my goal to bridge medicine and data science to improve patient care.*
