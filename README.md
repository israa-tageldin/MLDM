# Early Diabetes Risk Prediction

This project develops an explainable machine learning framework for early diabetes risk prediction using the BRFSS 2015 Diabetes Binary dataset.

## Project Aim

The aim is to test whether combining clinical, lifestyle, and socioeconomic features improves diabetes prediction compared with using clinical features alone.

## Dataset

- Source: BRFSS 2015 Diabetes Health Indicators Dataset
- Records: 70,692
- Target: Diabetes_binary
- Classes: No Diabetes, Prediabetes/Diabetes

## Methods Used

- Data preprocessing and EDA
- Mutual Information feature selection
- Logistic Regression
- Random Forest
- XGBoost
- Hyperparameter optimization
- SHAP explainability
- Risk score recommendation engine
- Orange clustering for no-code data mining

## Main Result

The Top 10 Combined Selected feature set improved performance compared with the Clinical Only feature set. XGBoost achieved the best overall performance with ROC AUC of approximately 0.8255.

## Files

- `IT9201_Diabetes_Prediction_Israa.ipynb` — main notebook
- `IT9201_Israa_12010745.docx` — project report
- `figures/` — generated charts and SHAP plots

## Tools

Python, Google Colab, pandas, NumPy, scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn, Orange.

## Author

Israa Mohammed  
MSc Artificial Intelligence  
Bahrain Polytechnic
