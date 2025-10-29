# CodeAlpha_DiseasePrediction
.

**Objective:**
To build a Machine Learning model that predicts whether a person is diabetic or not based on medical attributes such as glucose level, blood pressure, BMI, and age.

**Dataset:**
Source: Kaggle Diabetes Dataset
Records: ~768 samples
Target Column: Outcome (1 = Diabetic, 0 = Non-Diabetic)

**Technologies Used:**
Language: Python
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn
Environment: Google Colab

**Steps Followed:**
1-Imported and explored the dataset (EDA)
2-Checked for null or missing values
3-Split data into training and testing sets
4-Scaled features using StandardScaler
5-Trained two ML models:
    Logistic Regression
    Random Forest Classifier
6-Compared model performance
7-Visualized feature importance

**Results:**
Logistic Regression : 0.75
Random Forest : 0.76
