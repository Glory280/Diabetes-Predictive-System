# 🩺 Diabetes Diagnostic Analysis – Pima Indian Women Dataset
### Population Health Insights from the Pima Indian Women Dataset 

## 📌 Project Objective
This project applies a public health analytics approach to identify key clinical and demographic factors associated with diabetes among adult women of Pima Indian heritage (aged 21+).

The objective is not only diagnostic classification, but to generate population-level insights that can inform early detection, targeted screening, and preventive health interventions in high-risk female populations.

## 📂 Dataset Overview
The dataset (provided through the MeriSkill Internship Program, originally from the UCI Machine Learning Repository) contains medical diagnostic data for Pima Indian women.

It includes 8 predictor variables and 1 binary outcome variable:
| Feature              | Description                                                         |
|----------------------|----------------------------------------------------------------------|
| `Pregnancies`         | Number of pregnancies                                               |
| `Glucose`             | Plasma glucose concentration (oral glucose tolerance test)          |
| `BloodPressure`       | Diastolic blood pressure (mm Hg)                                    |
| `SkinThickness`       | Triceps skinfold thickness (mm)                                     |
| `Insulin`             | 2-Hour serum insulin (mu U/ml)                                      |
| `BMI`                 | Body Mass Index (weight in kg/(height in m)^2)                      |
| `Diabetes`            | Diabetes Pedigree Function (genetic risk score)                     |
| `Age`                 | Age in years                                                        |
| `Outcome`             | Diagnosis result (0 = Non-diabetic, 1 = Diabetic)                   |

---

## 🧹 Data Preparation & Management
To ensure data quality and analytical validity, the following preprocessing steps were performed:

- ✅ **Data loading and structural inspection**
- 🛠 **Standardization and formatting of numerical variables** 
- ❗ **Identification and handling of biologically implausible or missing values** (Identification and handling of biologically implausible or missing values)
- 🔁 **Removal of duplicate records**
- 📊 **Categorization of continuous variables** (Age groups and BMI classifications (normal, overweight, obese))
  
These steps align with real-world public health data cleaning practices, where clinical datasets often contain incomplete or noisy measurements.

---

## 🔍 Exploratory Data Analysis (EDA)

### 📈 Diabetes Prevalence
- **268** women were classified as diabetic. Non-diabetic individuals constituted the majority, reflecting a prevention-opportunity population
### 🧍 Age Distribution
- The **21–30 age group** showed the highest number of diabetes cases. This suggests early onset risk rather than disease limited to older adults

### ⚖️ Body Mass Index (BMI)
- Diabetes prevalence increased significantly among **obese individuals (BMI ≥ 30)**. This highlights obesity as a modifiable public health risk factor
  
### 🤰 Pregnancy History
- Higher diabetes prevalence observed among women with **1–3 pregnancies** which indicates that diabetes risk exists early in reproductive life, not only after multiple pregnancies
  
### 💉 Skin Thickness
- Diabetic cases were most common within the 21–40 mm skinfold thickness range.This supports the role of adiposity indicators in diabetes risk assessment

### 📊 Outcome Distribution
- **Non-diabetic patients outnumber** diabetic patients in the dataset

---

## 🧠 Key Insights

| Feature            | Observation                                                        |
|--------------------|---------------------------------------------------------------------|
| **BMI**             | Strong association between obesity and diabetes risk               |
| **Age**             | Younger women (21–30) show high risk                               |
| **Pregnancies**     | Diabetes occurs even at low pregnancy counts                        |
| **Skin Thickness**  | Moderate levels (21–40 mm) show more diabetic cases                 |
| **General Trend**   | Lifestyle-related factors are strong indicators of diabetes         |

---

## 📝 Conclusion
This analysis highlights key factors contributing to diabetes in the population studied:

- **Obesity and young age** are critical contributors.
- The condition can affect women early in life, even without multiple pregnancies.
- Non-diabetic individuals still make up the majority, providing room for effective prevention.

---

## ✅ Recommendations
- 🔍 Encourage **routine glucose screening** for young, obese women
- 🧪 Build a **predictive model** (e.g., logistic regression, decision tree) for risk assessment
- 📢 Launch **public health campaigns** targeted at lifestyle management in younger age groups
- 🔄 Investigate **feature interactions**, such as between glucose and insulin


---

## 🙌 Acknowledgments
- Dataset: [MeriSkill Internship Program]
- Based on diagnostic data of Pima Indian women, originally sourced from the UCI Machine Learning Repository.

---

## 📬 Contact
If you'd like to collaborate or ask questions, feel free to connect!

  
-[View Dashboard](https://drive.google.com/file/d/1tEiv5PMbW0s1vV8X-dAE-nPeBnnR309H/view?usp=sharing)
