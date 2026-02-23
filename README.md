# 📌 Task 1 – Data Immersion & Wrangling  
**Project:** E-commerce Customer Behavior Analysis  
**Internship:** Data Analytics Internship – ApexPlanet  
**Author:** Tanmay  

---

## 📖 1. Project Objective

The objective of this task is to understand, assess, clean, and prepare raw customer behavior data for further analysis and dashboard development. This ensures data reliability, consistency, and analytical readiness.

---

## 📊 2. Dataset Overview

- Total Records: 350  
- Total Columns: 11  
- Data Type: Structured customer-level dataset  

### Key Features:
- Age  
- Gender  
- Total Spend  
- Items Purchased  
- Average Rating  
- Membership Type  
- Days Since Last Purchase  
- Satisfaction Level  

The dataset represents aggregated customer purchase and behavioral information.

---

## 🔍 3. Data Profiling & Quality Assessment

The following checks were performed:

### ✔ Missing Values
- 2 missing values in "Satisfaction Level" (<1%)
- Rows removed due to negligible impact on dataset size

### ✔ Duplicate Records
- No duplicate records found

### ✔ Data Validation
- Verified no negative spending values
- Ensured ratings were within logical range
- Confirmed age values were reasonable

These checks ensured dataset consistency and integrity.

---

## 🛠 4. Data Cleaning Steps

1. Removed records with missing values  
2. Verified absence of duplicate records  
3. Validated numerical ranges  
4. Standardized dataset for further analysis  

The cleaned dataset is free from inconsistencies and ready for analytical use.

---

## 🚀 5. Feature Engineering

To enhance analytical value, the following features were created:

### 🔹 Spend Category
Customers segmented into Low, Medium, and High spend groups to enable targeted marketing strategies.

### 🔹 Recency Category
Customers categorized as Recent, Moderate, or Inactive based on purchase recency to support retention analysis.

### 🔹 Revenue per Item
Calculated as Total Spend divided by Items Purchased to measure purchasing efficiency.

These engineered features improve segmentation and business insight potential.

---

## 📁 6. Final Output

- Cleaned dataset exported as `cleaned_customer_data.csv`
- Notebook containing complete cleaning workflow

The dataset is now analysis-ready and will be used in Task 2 for exploratory data analysis and dashboard development.

---

## 🧰 7. Tools & Technologies Used

- Python  
- Pandas   
- Jupyter Notebook  
