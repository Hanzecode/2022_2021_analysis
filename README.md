# UK Underemployment Analysis (2021–2022) 📊

## 🔎 Project Overview

This repository investigates patterns and determinants of **underemployment in the United Kingdom** during 2021 and 2022, using data from **Understanding Society (UKHLS)**.

Underemployment refers to individuals who are working but **not in jobs that match their skills, qualifications, preferred hours, or wage expectations**. It has strong effects on social mobility, income stability, job satisfaction, and mental well-being.  
This project builds multi-dimensional indicators of underemployment and analyses differences by **gender**, **migration status**, **education**, and other demographic characteristics.

---

## 🧭 Workflow & Repository Structure


---

## 📄 Conceptual Framework: Understanding Underemployment

Underemployment is multi-dimensional. This project considers the following forms:

### **1. Skills Underemployment (Overqualification)**
When individuals possess higher education or skill levels than required for their job.

### **2. Wage Underemployment**
When individuals earn less than expected given their education, occupation, or experience.

### **3. Combined / Multiple Underemployment**
When two or more disadvantages are experienced simultaneously (e.g., low pay and skills mismatch).

### **4. Perceived Underemployment**
Based on self-reported job satisfaction, desire for more hours, dissatisfaction with pay, etc.

These types capture labour market disadvantage that does **not** appear in standard employment metrics.

---

## 👥 Study Population

### **Inclusion Criteria**
Individuals who:
- are aged **16–64**
- are **employed or self-employed**
- provide valid data on occupation, wages, hours, or education
- report **paid work** in the reference period
- provide variables relevant to underemployment indicators

### **Exclusion Criteria**
Exclude:
- full-time students not primarily working
- retired or above statutory retirement age
- workers constrained by external hour restrictions (e.g., visa limits)
- voluntarily part-time individuals satisfied with their hours
- unpaid family workers or volunteers

---

## 📊 Running the Analysis

### **Step 1 — Data Cleaning**
Run the following:

- **main_data_edit.ipynb**  
  → Cleans and aligns the 2021 & 2022 datasets  

- **sub_data_edit.ipynb**  
  → Processes immigration/migration-related variables  

---

### **Step 2 — Merging & Final Dataset**
After cleaning, datasets from both notebooks are merged to produce a unified analytical dataset.

---

### **Step 3 — Analysis**
`analysis.ipynb` includes:

- construction of underemployment indicators  
- descriptive statistics  
- subgroup comparisons (gender, migration status, education, etc.)  
- relationships with mental health and job satisfaction  

---

## 🧩 Key Indicators & Validation Tasks

### **Indicators**
- Skills mismatch  
- Wage mismatch  
- Combined underemployment  
- Perceived underemployment  

### **Validation Tasks**
- Check logical consistency across years  
- Identify subgroup disparities  
- Assess stability of measures across 2021–2022  
- Verify completeness and accuracy of variables  

---

## 📈 Descriptive Analysis Goals

### **Compare underemployment by:**
- gender  
- migration status  
- education  
- disability status  

### **Compare forms of underemployment**
- skills mismatch  
- wage mismatch  
- combined underemployment  

### **Examine associations with:**
- mental health indicators  
- job satisfaction (overall and domain-specific)  

Also:  
- Note inconsistencies across years for future cleaning improvements  

---

## 📚 Acknowledgments
- Data source: **Understanding Society – UK Household Longitudinal Study (UKHLS)**  
- Methodological practices follow standard guidelines for transparent academic data workflows.  

---

## 📝 License & Notes
This project is intended for research and educational use.  
If you reuse or cite this work, please credit the original author.

---

## 🙋 Author
**Hanzecode**  
GitHub: https://github.com/Hanzecode
