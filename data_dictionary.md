# 📘 Data Dictionary  
**Project:** E-commerce Customer Behavior Analysis  
**Task:** Data Immersion & Wrangling  

---

## 📌 Original Columns

### 1. Customer ID
- **Type:** Categorical (Identifier)
- **Description:** Unique identifier assigned to each customer.
- **Usage:** Used as a primary key; not used for analytical calculations.

### 2. Gender
- **Type:** Categorical
- **Description:** Gender of the customer.
- **Usage:** Used for demographic segmentation analysis.

### 3. Age
- **Type:** Numerical (Integer)
- **Description:** Age of the customer.
- **Usage:** Used to analyze age-based purchasing behavior.

### 4. City
- **Type:** Categorical
- **Description:** City where the customer resides.
- **Usage:** Used for geographical analysis.

### 5. Membership Type
- **Type:** Categorical
- **Description:** Type of membership (e.g., Basic, Silver, Gold).
- **Usage:** Used to analyze spending behavior across membership tiers.

### 6. Total Spend
- **Type:** Numerical (Float)
- **Description:** Total amount spent by the customer.
- **Usage:** Used to measure customer value and segment customers.

### 7. Items Purchased
- **Type:** Numerical (Integer)
- **Description:** Total number of items purchased by the customer.
- **Usage:** Used to calculate purchasing behavior metrics.

### 8. Average Rating
- **Type:** Numerical (Float)
- **Description:** Average rating given by the customer.
- **Usage:** Used to assess satisfaction trends.

### 9. Discount Applied
- **Type:** Boolean
- **Description:** Indicates whether a discount was applied.
- **Usage:** Used to evaluate impact of discounts on spending.

### 10. Days Since Last Purchase
- **Type:** Numerical (Integer)
- **Description:** Number of days since the customer’s last purchase.
- **Usage:** Used as a recency metric for retention analysis.

### 11. Satisfaction Level
- **Type:** Categorical
- **Description:** Customer satisfaction classification.
- **Usage:** Used to analyze customer experience trends.

---

## 🚀 Engineered Features

### 12. Spend Category
- **Type:** Categorical
- **Description:** Customer segmentation based on total spending (Low, Medium, High).
- **Purpose:** Enables targeted marketing and customer value analysis.

### 13. Recency Category
- **Type:** Categorical
- **Description:** Customer segmentation based on recency (Recent, Moderate, Inactive).
- **Purpose:** Helps identify inactive customers for retention strategies.

### 14. Revenue per Item
- **Type:** Numerical (Float)
- **Description:** Calculated as Total Spend divided by Items Purchased.
- **Purpose:** Measures purchasing efficiency and customer spending behavior.
