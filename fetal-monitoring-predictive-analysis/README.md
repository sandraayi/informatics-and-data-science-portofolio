# Predicting Fetal Health Outcomes Using CTG Data and Machine Learning 
*Academic Project | UIC Programming for Health Analytics*  
*July 2024*

## Project Overview  
This project explores the use of machine learning to predict fetal health outcomes based on cardiotocogram (CTG) readings. Using a clinically validated dataset by Ayres de Campos et al. (2000), I performed exploratory data analysis and predictive modeling to identify features associated with normal, suspicious, and pathological outcomes.

## Clinical Context  
Fetal monitoring is critical to detecting distress during labor. However, the interpretation of CTG data is often subjective. By applying data science tools to CTG recordings, this project aims to support clinical judgment and reduce perinatal morbidity and mortality through earlier detection of risk.

## Objectives  
- Conduct exploratory analysis on a dataset of 2,126 CTG readings  
- Identify key predictors of fetal outcomes (normal, suspect, pathological)  
- Build and evaluate machine learning models to classify fetal health status  

## Methodology  
- Data from Ayres de Campos et al. (2000), publicly available and pre-cleaned  
- Univariate and bivariate statistical analysis of 22 features  
- Key predictors: abnormal short-term variability, fetal movements, uterine contractions, baseline FHR, decelerations  
- Models: Logistic Regression, Decision Tree, Random Forest  
- Model performance evaluated by accuracy, precision, recall, and F1-score

## Key Findings  
- **Normal outcomes:** 77.9%  
- **Suspicious outcomes:** 13.8%  
- **Pathological outcomes:** 8.3%  
- **Best performing model:** Random Forest  
  - Accuracy: 90%  
  - Precision: 93%  
  - Recall: 97%  
  - F1-score: 95%  

## Clinical Relevance  
This project demonstrates how data-driven tools can enhance early detection of high-risk fetal conditions. As a physician, I value the potential of machine learning to complement obstetric care by improving interpretability and consistency in fetal monitoring.

## Related Links  
- [View Full Notebook](./BHIS561_Unit07_Assignment_01_Sandra_Ayi.ipynb)  
- [Main Portfolio Repository](https://github.com/sandraayi/informatics-and-data-science-portofolio)
