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

---

## 🧠 Key Insights

| Feature            | Observation                                                        |
|--------------------|---------------------------------------------------------------------|
| **BMI**             | Strong association between obesity and diabetes risk               |
| **Age**             | Younger women show notable vulnerability                           |
| **Pregnancies**     | Risk present even with low parity                                  |
| **Skin Thickness**  | Moderate-to-high adiposity linked to higher prevalence             |
| **Overall Pattern**   | Lifestyle-related factors dominate diabetes risk                 |

---

## 📝 Public Health Implications
This analysis demonstrates that diabetes risk in this population:
-Is not limited to **older age groups**
-Is strongly associated with **modifiable lifestyle factors**
-Can emerge **early in adulthood**, emphasizing the need for earlier intervention

---

## ✅ Recommendations
-Encourage **routine glucose screening** for young and overweight/obese women
-Integrate diabetes risk assessment into **reproductive and primary care services**
-Develop **predictive risk models** (e.g., logistic regression) to support early identification
-Implement **community-based lifestyle interventions** focused on nutrition and physical activity
-Further analyze **interactions between glucose, insulin, and BMI** to refine risk stratification

---

## 🙌 Data Source & Acknowledgment
Dataset provided through the MeriSkill Internship Program, based on the Pima Indian Diabetes Dataset from the UCI Machine Learning Repository.

---

## 📬 Contact
If you'd like to collaborate or ask questions, feel free to connect!

  
-[View Dashboard](https://drive.google.com/file/d/1tEiv5PMbW0s1vV8X-dAE-nPeBnnR309H/view?usp=sharing)
