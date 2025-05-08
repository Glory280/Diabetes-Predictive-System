# 🩺 Diabetes Diagnostic Analysis – Pima Indian Women Dataset

## 📌 Project Objective
The aim of this project is to diagnostically detect the primary contributors to diabetes among adult female patients of Pima Indian heritage (aged 21 and above) using medical diagnostic features. The goal is to derive actionable insights that can support early diagnosis and targeted prevention strategies.

---

## 📂 Dataset Overview
The dataset, provided by **MeriSkill Internship**, includes medical information from Pima Indian women. It consists of 9 features and 1 target variable:

| Feature              | Description                                                         |
|----------------------|----------------------------------------------------------------------|
| `Pregnancies`         | Number of times the patient has been pregnant                       |
| `Glucose`             | Plasma glucose concentration from an oral glucose tolerance test    |
| `BloodPressure`       | Diastolic blood pressure (mm Hg)                                    |
| `SkinThickness`       | Triceps skinfold thickness (mm)                                     |
| `Insulin`             | 2-Hour serum insulin (mu U/ml)                                      |
| `BMI`                 | Body Mass Index (weight in kg/(height in m)^2)                      |
| `Diabetes`            | Diabetes Pedigree Function (genetic risk score)                     |
| `Age`                 | Age in years                                                        |
| `Outcome`             | Diagnosis result (0 = Non-diabetic, 1 = Diabetic)                   |

---

## 🧹 Data Cleaning & Preprocessing
Steps carried out to prepare the dataset:

- ✅ **Data loading & inspection**
- 🛠 **Formatting** numeric columns appropriately
- ❗ **Missing value handling** (especially for `Insulin`, `BMI`, `SkinThickness`)
- 🔁 **Duplicate record removal**
- 📊 **Binning** of continuous variables (e.g., age groups, BMI categories)

---

## 🔍 Exploratory Data Analysis (EDA)

### 📈 Total Number of Diabetic Patients
- **268** patients were classified as diabetic (`Outcome = 1`)

### 🧍 Age vs Diabetes
- **21–30 years** age group had the **highest number of diabetic patients**

### ⚖️ BMI vs Diabetes
- Diabetes was more common in **obese individuals (BMI ≥ 30)**

### 🤰 Pregnancies vs Diabetes
- **Lower pregnancy counts (1–3)** had higher diabetes prevalence  
- Suggests early onset and risk during early reproductive years

### 💉 Skin Thickness vs Diabetes
- Diabetic cases concentrated in **21–40 mm skin thickness** range

### 📊 Outcome Distribution
- **Non-diabetic patients outnumber** diabetic patients in the dataset

---

## 🧠 Key Insights

| Feature            | Observation                                                        |
|--------------------|---------------------------------------------------------------------|
| **BMI**             | Obesity strongly correlates with diabetes                          |
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

## 📌 Next Steps (Optional Enhancements)
- [ ] Train machine learning classifiers
- [ ] Perform correlation analysis and feature importance ranking
- [ ] Create visual dashboards with tools like Seaborn, Matplotlib, or Plotly
- [ ] Explore model interpretability with SHAP or LIME

---

## 📁 Project Structure
📦 diabetes-diagnosis
┣ 📊 data/
┃ ┗ pima_diabetes.csv
┣ 📈 notebooks/
┃ ┗ eda_analysis.ipynb
┣ 📄 README.md
┗ 📜 report.pdf (optional export)


---

## 🙌 Acknowledgments
- Dataset: [MeriSkill Internship Program]
- Based on diagnostic data of Pima Indian women, originally sourced from the UCI Machine Learning Repository.

---

## 📬 Contact
If you'd like to collaborate or ask questions, feel free to connect!



# Diabetes Predictive System

### Objective
The aim of this project is to diagnostically diagnostically detect the main cause of diabetes among women based on certain diagnostic measurements included in the dataset. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

### The Dataset
The dataset was provided by MeriSkill Internship and it consists of 8 columns covering the following information;
- Pregnancies
- Glucose 
- Blood Pressure 
- Skin Thickness
- Insulin 
- BMI 
- Diabetes
- Age 
- Outcome

### Data Cleaning and Transformation
After thorough examination of the dataset and having a good understanding of the expected analysis, I proceeded to clean and transform my dataset to prepare it for analysis, The following steps were taken to ensure the data was free from errors;
- Data loading and inspection
- Data formatting 
- Handling missing values
- Handling duplicate values
- Grouping of data

### Data Exploration
Data exploration involved exploring the data to answer key questions such as;
- What is the total number of diabetic patients?
- What Body Mass Index(BMI) has the highest number of diabetic patients?
- What age group has the highest number of diabetic patients?
- Does diabetes prevail more within the first pregnancies? 
- What skin thickness group has the highest number of diabetic patients?

### Insights Gotten from the Data
From the given data;
- A total of 268 diabetic patients was recorded
- Diabetes prevails more among younger females (21-30)
- Diabetes prevails more among obese individuals
- Diabetes prevails more among females with lower skin thickness (21-40)
- The number of non-diabetic patients supersedes that of diabetic patients
  
-[View Dashboard](https://drive.google.com/file/d/1tEiv5PMbW0s1vV8X-dAE-nPeBnnR309H/view?usp=sharing)
