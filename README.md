# 🧠 Alzheimer’s Disease Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting the likelihood of Alzheimer’s disease using machine learning techniques applied to patient health data. The dataset includes demographic, lifestyle, medical history, clinical measurements, cognitive assessments, and symptoms.

The goal is to build predictive models that can assist in early detection of Alzheimer’s disease and provide insights into key risk factors.

---

## 🎯 Objectives

* Analyze healthcare data related to Alzheimer’s disease
* Perform Exploratory Data Analysis (EDA)
* Identify key factors influencing Alzheimer’s diagnosis
* Build and compare machine learning models
* Develop a web-based prediction system using Streamlit

---

 📊 Dataset Description

* **Total Records:** 2,149 patients
* **Age Range:** 60–90 years

 Features Included:

* **Demographics:** Age, Gender, Ethnicity, Education Level
* **Lifestyle Factors:** BMI, Smoking, Alcohol Consumption, Physical Activity, Diet Quality, Sleep Quality
* **Medical History:** Diabetes, Hypertension, Depression, Cardiovascular Disease
* **Clinical Measurements:** Blood Pressure, Cholesterol Levels
* **Cognitive Assessments:** MMSE, ADL, Functional Assessment
* **Symptoms:** Memory Complaints, Confusion, Disorientation

 🎯 Target Variable

* `Diagnosis`

  * 0 → No Alzheimer’s
  * 1 → Alzheimer’s Disease

---

## 🧹 Data Cleaning & Preparation

* Removed irrelevant columns (`PatientID`, `DoctorInCharge`)
* Checked and handled missing values
* Removed duplicate records
* Validated data ranges (BMI, BP, Cholesterol)
* Categorized variables into numerical and categorical
* Applied feature scaling using **StandardScaler**

---

## 📈 Exploratory Data Analysis (EDA)

Performed various visualizations and analysis:

* Histograms & Boxplots (distribution analysis)
* Count plots (categorical variables)
* Correlation heatmap

### 🔍 Key Insights:

* Alzheimer’s risk increases with age
* Lower MMSE scores strongly indicate cognitive decline
* Memory complaints and functional impairment are major indicators

---

## 📊 Statistical Analysis

* **Chi-Square Test:** Used for categorical variables
* **T-Test:** Used for numerical variables
* Hypothesis testing performed to identify significant features

---

## 🤖 Machine Learning Models

The following models were implemented:

* Logistic Regression (baseline model)
* Random Forest (ensemble learning)
* Gradient Boosting (best performing model)

---

## 📊 Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

### 🏆 Best Model:

Gradient Boosting achieved the highest performance among all models.

---

## 🌐 Web Application (Streamlit)

A web-based application was developed using **Streamlit** to allow users to:

* Input patient details
* Predict Alzheimer’s risk
* View probability score

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/alzheimers-project.git
cd alzheimers-project
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
Alzheimers_Project/
│
├── app.py
├── alzheimers_model.pkl
├── scaler.pkl
├── notebook.ipynb
├── requirements.txt
└── README.md
```

---

## ⚠️ Limitations

* Limited dataset size
* No imaging or genetic data included
* Model performance depends on data quality

---

## 🔮 Future Work

* Use larger and more diverse datasets
* Integrate medical imaging data
* Improve model performance using advanced techniques
* Deploy application online

---

## 👥 Team Members

* Vishal Sharma
* Harjeet Kaur
* Om Patel
* Kirti Sharma
* Krupa Patel

---

## 📌 Conclusion

This project demonstrates how machine learning can be applied to healthcare data to predict Alzheimer’s disease. The results highlight the importance of cognitive assessments and lifestyle factors in early detection.

---

## ⭐ Acknowledgements

* St. Clair College
* Open-source dataset providers
* Python & Scikit-learn community
