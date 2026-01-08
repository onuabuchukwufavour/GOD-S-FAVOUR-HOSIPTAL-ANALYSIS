# GOD’S FAVOUR HOSPITAL  
## Patient Record Analysis Project

**Project Name:** GOD’S FAVOUR HOSPITAL PATIENT RECORD ANALYSIS  
**Prepared by:** Onuabuchukwu Favour Chimdindu  

---

## 📌 Project Overview

This project focuses on analyzing hospital patient records containing demographic details, diagnoses, billing information, admission dates, discharge dates, and length of stay.

The dataset initially contained dirty and inconsistent values such as:
- Misspelled diagnoses  
- Invalid ages  
- Missing admission/discharge dates  
- Incorrect phone number formats  

The goal of this project is to clean, analyze, and extract insights that support hospital operations, medical quality improvement, and financial decision-making.

---

## 🎯 Project Objectives

- Clean and prepare the hospital dataset for accurate analysis  
- Standardize patient information (age, gender, diagnosis, dates, billing)  
- Analyze patient demographics and disease distribution  
- Identify the most common diagnoses and disease burden  
- Evaluate financial performance and billing patterns  
- Assess admission trends, discharge behavior, and length of stay  
- Provide actionable insights for hospital management  
- Present findings using clear and understandable visualizations  

---

## ❓ Business Questions Answered

1. What age groups make up the majority of hospital admissions?  
2. What diagnoses are most common among patients?  
3. Which medical conditions contribute most to hospital admissions?  
4. What is the distribution of bill amounts across patients?  
5. How long do patients typically stay in the hospital?  
6. Are there patterns in admission and discharge dates?  
7. What is the average bill amount per diagnosis?  
8. Which diagnoses result in higher average billing amounts?  

---

## 🛠️ Technologies Used

- **Python** – Data cleaning, manipulation, and analysis  
- **Pandas** – Handling missing values and data transformations  
- **NumPy** – Numerical data cleaning  
- **Matplotlib** – Data visualization  
- **Seaborn** – Statistical plots  
- **Jupyter Notebook / VS Code** – Development environment  
- **CSV** – Data storage format  

---

## 🗂️ Data Overview

| Column Name           | Description |
|----------------------|-------------|
| PatientID            | Unique ID assigned to each patient |
| Name                 | Patient full name (cleaned & standardized) |
| Age                  | Patient age (invalid values removed) |
| Gender               | Standardized to Male, Female, Unknown |
| Diagnosis             | Medical condition (cleaned & corrected) |
| AdmissionDate        | Cleaned and formatted admission date |
| DischargeDate        | Cleaned and formatted discharge date |
| BillAmount           | Cleaned financial charges |
| Phone                | Standardized to 11-digit format |
| Address              | Cleaned patient address |
| LengthOfStay_Days    | Total days spent in the hospital |

---

## 📊 Key Metrics

| Metric | Value |
|------|-------|
| Total patients analyzed | 30 |
| Total billing generated | Calculated sum |
| Average bill amount | Mean value |
| Most common diagnosis | Malaria / Diabetes / Hypertension |
| Average patient age | Mean age |
| Average length of stay | ~3–7 days |
| Missing values cleaned | 20+ fields |

---

## 🔍 Key Insights

- Majority of patients were between **ages 20–55**, indicating high usage by the working population  
- **Malaria, Diabetes, and Hypertension** were the most frequent diagnoses  
- Diagnosis spelling errors significantly affected disease counts before cleaning  
- Bill amounts showed wide variation, suggesting inconsistent billing or treatment intensity  
- Length of stay was strongly linked to diagnosis type and severity  
- Missing admission/discharge dates required cleaning before stay calculation  
- Phone number inconsistencies revealed weak data entry controls  

---

## 📈 Visualizations Included

- Age Distribution Histogram  
- Diagnosis Frequency Bar Chart (Descending Order)  
- Bill Amount Box Plot  
- Gender Distribution Count Plot  
- Length of Stay Histogram  
- Admissions Over Time  
- Age vs Bill Amount Scatter Plot  
- Average Bill Amount per Diagnosis Bar Chart  

---

## ✅ Conclusion

The hospital dataset required extensive cleaning due to misspellings, invalid values, missing records, and formatting errors. After cleaning, the dataset produced meaningful insights into patient demographics, disease prevalence, billing behavior, and hospital stay patterns.

These insights provide valuable support for improving hospital operations, medical service delivery, and financial planning.

---

## 📌 Recommendations

### 1. Improve Data Entry Processes
- Use dropdown fields for Diagnosis, Gender, etc.  
- Enforce validation rules for age, phone numbers, and billing amounts  

### 2. Standardize Medical Coding
- Adopt **ICD-10 medical codes** to eliminate diagnosis misspellings  

### 3. Implement Electronic Medical Records (EMR)
- Reduce human errors and missing values  

### 4. Audit Billing Procedures
- Investigate wide billing variations  
- Ensure consistent pricing policies  

### 5.	Monitor Common Diseases
- High frequency conditions (e.g., malaria, Diabetes) require targeted medical resources.

## 6.	Improve Patient Flow Management

-	Analyze length-of-stay patterns to reduce hospital congestion.

## 7.	Automate Data Quality Checks

-	Run scripts to detect invalid dates, incorrect phone formats, and missing fields.



