# 💤 Sleep Health Analysis and Disorder Prediction

This is a **Data Analysis** and **Machine Learning** project that explores lifestyle and health factors to identify key determinants of sleep quality. It applies data preprocessing, exploratory analysis, and classification models (Logistic Regression & Random Forest) to predict sleep disorders and provide actionable insights.

---

##  Dataset

The dataset includes features such as:
Demographics: Age, Gender, Occupation
Lifestyle Factors: Physical Activity, Sleep Duration, Stress, BMI
Health Indicators: Blood Pressure, Sleep Disorder (Target Variable)  

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

### 3. Model Building 
- **Logistic Regression:** Used as a baseline model with L2 regularization and balanced class weights. 
- **Random Forest Classifier:** Used for robust predictions and feature importance analysis.  
- Evaluated models using precision, recall, F1-score, confusion matrices, and cross-validation.

### 4. Evaluation
- Evaluated models using:
  - Precision, Recall,
  - F1-score
  - Confusion Matrix
  - Cross-validation with weighted F1 scoring

### 4. Feature Importance Analysis  
- **Random Forest Feature Importance:** Highlighted crucial predictors like stress, sleep duration, and BMI.  
- **Permutation Importance:** Validated feature relevancy by assessing performance drop when features were shuffled.

---

##  Results

- **Random Forest** Classifier outperformed Logistic Regression, achieving an F1-score of ~94% on the test set.
- Key features influencing sleep quality: **Stress, BMI, Sleep Duration, Physical Activity.**
- Visualizations highlighted strong lifestyle-health correlations with sleep disorders.

---

##  Conclusion

- Lifestyle and health factors such as **BMI, stress,** and **sleep duration** are major determinants of sleep quality.
- Random Forest demonstrated superior predictive performance compared to Logistic Regression.
- Proper preprocessing, feature engineering, and importance analysis improved model accuracy and interpretability.
---

##  Tech Stack

- **Languages:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  
- **Visualization:** Matplotlib & Seaborn

---

👤 Author

- Bhanu Prabhavi
- 📧 bhanuprabhavi@gmail.com
