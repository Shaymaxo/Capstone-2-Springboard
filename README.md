# 💳 Credit Card Fraud Detection Capstone Project

**Author**: Shayma Remy  
**Capstone Title**: *Conquering Class Imbalance: Strategic Sampling for High-Recall Credit Card Fraud Detection*  
**Cohort**: Springboard Data Science Career Track  

---

## 🧠 Problem Statement

Credit card fraud is a high-impact, low-frequency event—just 3.5% of transactions are fraudulent, yet they account for billions in losses annually. The client’s primary goal was to develop a machine learning model that prioritizes identifying fraudulent transactions (high recall) even if it means flagging some legitimate ones.

---

## 📊 Dataset Overview

- **Source**: IEEE-CIS Fraud Detection Dataset  
- **Rows**: 590,540 transactions  
- **Supplementary Data**: 144,233 identity records  
- **Final Feature Count**: 434 columns after preprocessing

---

## 🔧 Project Structure

| File/Notebook | Description |
|---------------|-------------|
| `2_Data_Wrangling_Capstone2.ipynb` | Merges datasets, handles missing values, begins cleaning |
| `3_EDA_new_capstone.ipynb` | Exploratory Data Analysis – univariate, bivariate, and insights |
| `4_Preprocessing_balancing_encoding_scaling.ipynb` | Feature engineering, encoding, SMOTE balancing, and scaling |
| `5_Modeling_and_Threshold_Tuning.ipynb` | Model training, evaluation, and threshold tuning |
| `model_metrics.txt` | Summary of final model performance and hyperparameters |
| `Capstone_Final_Report.pdf` | Full project report with methodology, results, and recommendations |

---

## 🧪 Modeling Approach

- **Algorithms Tested**: Logistic Regression, Decision Tree, XGBoost, Random Forest  
- **Final Model**: Threshold-tuned Random Forest  
- **Threshold**: 0.69 for optimized fraud recall  
- **Sampling**: SMOTE to handle class imbalance  
- **Evaluation**: 80/20 train-test split, cross-validation used for reliability

---

## 📈 Final Model Performance (Random Forest)

| Metric | Value |
|--------|-------|
| Accuracy | 86.80% |
| Precision (Fraud) | 85.02% |
| Recall (Fraud) | 73.34% |
| F1 Score (Fraud) | 78.75% |
| ROC AUC | 0.9176 |

---

## ✅ Key Takeaways & Recommendations

1. **Deploy the threshold-tuned Random Forest** model in production to catch the majority of fraudulent transactions.
2. **Use model scores to triage edge cases** (e.g., transactions with probability 0.5–0.69) for additional human review.
3. **Monitor and retrain** the model quarterly to reflect evolving fraud tactics and data drift.

---

## 🔮 Future Work

- Explore time-based or behavioral features (e.g., IP-to-location matching, login frequency)
- Evaluate ensemble methods like stacking or voting classifiers
- Improve runtime and scalability with LightGBM or other gradient boosting methods

---

## 📎 Appendix

- [Data Wrangling Notebook](https://github.com/Shaymaxo/Capstone-2-Springboard/blob/main/2_Data_Wrangling_Capstone2.ipynb)  
- [EDA Notebook](https://github.com/Shaymaxo/Capstone-2-Springboard/blob/main/3_EDA_new_capstone.ipynb)  
- [Preprocessing Notebook](https://github.com/Shaymaxo/Capstone-2-Springboard/blob/main/4_Preprocessing_balancing_encoding_scaling.ipynb)  
- [Modeling & Threshold Tuning](https://github.com/Shaymaxo/Capstone-2-Springboard/blob/main/5_Modeling_and_Threshold_Tuning.ipynb)

---

## 📫 Contact

**Shayma Remy**  
*Data Scientist | Financial Crimes Analyst*  
[LinkedIn](https://www.linkedin.com/in/shayma-remy)  
[Email](shayma.remy@gmail.com)

---
