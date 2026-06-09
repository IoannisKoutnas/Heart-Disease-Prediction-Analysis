# Heart Disease Diagnostic Analysis | Portfolio Project

**End-to-End Data Analysis & Machine Learning Project**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-FF9E0F?style=for-the-badge&logo=scikit-learn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-1A73E8?style=for-the-badge)

## 📋 Project Objective

To identify key risk factors and patterns associated with heart disease using a large clinical dataset of over **900,000 patient records**. The goal was to build accurate, interpretable, and explainable machine learning models to predict the presence of heart disease.

---

## 🚀 Key Highlights

- **Best Model**: **LightGBM** with **88.80% accuracy** and **0.87 Recall**
- **ROC-AUC Score**: **0.9548** (Excellent discriminative power)
- **Advanced Techniques**: SHAP Explainability, Cross-Validation, Threshold Optimization
- **Clinical Insight**: Retained medical outliers (e.g., high BP) as they carry important predictive signal
- **Strongest Predictors**: Thallium Stress Test, Chest Pain Type, Max Heart Rate

---

## 📊 Project Structure

- **Chapter 1–5**: Project Setup, Data Loading & Cleaning
- **Chapter 6–8**: Exploratory Data Analysis & Feature Relationships
- **Chapter 9**: Data Preprocessing & Feature Engineering
- **Chapter 10–14**: Model Development (Logistic Regression → Random Forest → XGBoost → LightGBM)
- **Chapter 15**: Advanced Evaluation (ROC-AUC, Threshold Tuning, Cross-Validation)
- **Chapter 16**: Model Explainability with SHAP
- **Chapter 17**: Final Conclusion & Recommendations

---

## 📈 Key Insights

- Male patients are over **3x more likely** to have heart disease than females (56% vs 18%)
- **Asymptomatic** chest pain patients had **70%** probability of heart disease
- **Thallium Stress Test** (especially Reversible Defect) is the strongest predictor
- Age and reduced Max Heart Rate are significant risk factors

---

## 🛠️ Technologies Used

- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-Learn, XGBoost, LightGBM
- **Explainability**: SHAP
- **Evaluation**: Cross-Validation, ROC-AUC, Precision-Recall

---

## 📁 Files in Repository

- `Heart_Disease_Analysis.ipynb` → Main Jupyter Notebook
- `heart_disease_LightGBM.csv` → Final Submission File (Best Model)
- `heart_disease_XGBoost.csv`, `heart_disease_RF.csv` → Other submissions
- `README.md` (this file)

---

## 🏆 What I Learned

- End-to-end ML workflow on large-scale data
- Importance of domain knowledge in outlier treatment
- Balancing model performance with clinical interpretability
- Using SHAP for trustworthy model explanations

---

**Status**: Ready for Production / Deployment

---

**Feel free to explore the notebook!**  
Any feedback or suggestions for improvement are welcome.

---

**Ioannis Koutnas — Aspiring Junior Data Analyst**
