# 💤 Sleep health Analysis and Disorder Prediction

This project analyzes lifestyle and health factors to predict sleep disorders and evaluate their impact on overall sleep quality. Using **Logistic Regression** and **Random Forest** models, it identifies key determinants such as BMI, stress, sleep duration, and physical activity.

---

##  Dataset

The dataset used in this project is sourced from Kaggle:  
- **Sleep Health and Lifestyle Dataset** — a comprehensive dataset containing information on sleep disorders (None, Insomnia, Sleep Apnea), along with lifestyle metrics and health indicators.  
  Access it here: [Sleep Health and Lifestyle Dataset – Kaggle](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)

---

##  Project Objectives

- Analyze lifestyle and health factors to identify key determinants of sleep quality.
- Develop and compare machine learning models (Logistic Regression and Random Forest) for predicting sleep disorders.
- Conduct feature engineering and exhaustive model evaluation for improved accuracy and insight.
- Provide actionable findings to promote better sleep health.

---

##  Methodology

### 1. Data Preprocessing  
- Handled missing values and encoded categorical variables.  
- Standardized numerical features.  
- Managed class imbalance using stratified splits and balancing class weights.

### 2. Exploratory Data Analysis (EDA)  
- Visualized trends across demographics, stress, BMI, sleep duration, and disorders.  
- Identified strong correlations, particularly involving stress and sleep quality.

### 3. Model Building & Evaluation  
- **Logistic Regression:** Baseline model with regularization and balanced class weights.  
- **Random Forest Classifier:** Leveraged for higher accuracy and interpretability.  
- Evaluated models using precision, recall, F1-score, confusion matrices, and cross-validation.

### 4. Feature Importance Analysis  
- **Random Forest Feature Importance:** Highlighted crucial predictors like stress, sleep duration, and BMI.  
- **Permutation Importance:** Validated feature relevancy by assessing performance drop when features were shuffled.

---

##  Results Summary

- Random Forest outperformed Logistic Regression, achieving higher F1-scores—especially in minority classes.  
- Key predictors of sleep disorders included **Stress Level**, **Sleep Duration**, **BMI**, and **Blood Pressure**.

---

##  Conclusion

- Lifestyle variables—stress, sleep duration, BMI—are pivotal in predicting sleep disorders.  
- The combination of interpretable (Logistic Regression) and robust (Random Forest) models yields both actionable insights and strong predictive performance.

---

##  Tech Stack

- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Visualization:** Matplotlib & Seaborn

---

##  Future Directions

- Incorporate wearable or sequential sleep data for richer analysis.  
- Explore deep learning methods (e.g., LSTMs) for time-series modeling.  
- Develop an interactive dashboard for real-time sleep disorder risk assessment.

---

##  Project Structure

