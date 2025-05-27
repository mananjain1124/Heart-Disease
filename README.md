# 🫀 Heart Disease Detection

This project aims to build a machine learning model that can accurately predict whether a patient has heart disease based on medical parameters and personal health data.

## 📌 Objective

Develop a classification model that determines whether a patient has heart disease using various health indicators.

## 📂 Dataset

The dataset contains anonymized patient health data including both numeric and categorical features. Each row corresponds to a patient, with a target label indicating the presence or absence of heart disease.

### 🔍 Features

| Feature | Description | Type |
|--------|-------------|------|
| age | Age of the patient (in years) | Numeric |
| sex | Sex (0 = female, 1 = male) | Binary |
| chest pain type | Type of chest pain (1 = typical angina, 2 = atypical angina, 3 = non-anginal, 4 = asymptomatic) | Nominal |
| resting bp | Resting blood pressure (in mm Hg) | Numeric |
| cholesterol | Serum cholesterol (in mg/dl) | Numeric |
| fasting blood sugar | >120 mg/dl (1 = true, 0 = false) | Binary |
| resting ecg | Resting electrocardiogram results (0 = normal, 1 = ST-T abnormality, 2 = LV hypertrophy) | Nominal |
| max heart rate | Maximum heart rate achieved | Numeric |
| exercise angina | Exercise-induced angina (1 = yes, 0 = no) | Binary |
| oldpeak | ST depression induced by exercise | Numeric |
| ST slope | Slope of the ST segment (1 = up, 2 = flat, 3 = down) | Nominal |
| target | Diagnosis (1 = Heart Disease, 0 = Normal) | Binary |

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

## 📊 Model Approach

1. *Data Cleaning & Preprocessing*:
   - Handling missing values
   - Encoding categorical features
   - Feature scaling

2. *Exploratory Data Analysis (EDA)*:
   - Visualizing distributions and correlations
   - Understanding feature importance

3. *Modeling*:
   - Logistic Regression
   - Random Forest
   - Support Vector Machines (SVM)
   - Evaluation with metrics like Accuracy, Precision, Recall, F1 Score, ROC-AUC

## 👩‍💻 Authors

- [Manan jain] – [GitHub Profile]((https://github.com/mananjain1124))
