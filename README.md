# 📊 Customer Churn Analysis and Prediction

This project presents a **comprehensive Power BI dashboard** to analyze customer churn, understand key influencing factors, and segment customers based on tenure, service preferences, and demographics.

---

## 🚀 Objective

To analyze customer churn data, identify high-risk segments, and help businesses take data-driven decisions to improve **customer retention** and reduce **churn rate**.

---

## 📁 Dataset

- Contains details of telecom customers: demographics, service usage, billing info, and churn status.
- Key columns: `tenure`, `MonthlyCharges`, `TotalCharges`, `Contract`, `PaymentMethod`, `InternetService`, `Churn`, etc.

---

## 📌 Dashboard Components

### 📍 A. Churn Rate Overview
- **KPI card** shows overall churn rate (e.g., 26.54%)
- Visual: TenureGroup vs Churn Rate (with color coding)
- **Design Tip**: Red for high churn, Green for low churn

### 📍 B. Customer Demographics
- Visualizes gender, partner status, and dependent status
- Charts: Bar charts & pie chart

### 📍 C. Customer Tenure Analysis
- Tenure grouped into:
  - `New` (0–10 months)
  - `Short-Term` (11–30 months)
  - `Long-Term` (31–59 months)
  - `Very Long-Term` (60–72 months)
- Box plot / bar chart to explore tenure distribution

### 📍 D. Churn by Service Type
- Analyzes churn by:
  - Contract Type
  - Payment Method
  - Internet Service
- Advanced: **Matrix visual** showing churn % across Contract × Payment Method

### 📍 E. Filtering Options
- Interactive slicers for:
  - Phone Service
  - Multiple Lines
  - Internet Service
  - Paperless Billing

---

## 📌 Tools Used

- **Power BI Desktop**
- DAX (for calculated columns & measures)
- Conditional Formatting (churn color coding)
- Data grouping & filtering

---

## 📷 Screenshots

![Overview](./overview%20screenshot.jpg)  
![Churn by Tenure](./second%20page%20screenshot.jpg)  
![Tenure Matrix](./final%20page%20screenshot.jpg)

---

## 📈 Key Insights

- Customers on **Month-to-Month contracts** have the highest churn.
- **Electronic Check** payments correlate with high churn.
- Customers with **short tenure** are more likely to churn.
- Gender and partner status show subtle churn behavior variations.

---

## 📌 Future Improvements

- Integrate machine learning churn prediction using Python.
- Add cohort analysis and revenue impact from churn.
- Deploy Power BI dashboard to Power BI Service with real-time updates.

  
🙋‍♂️ Author
Nikhil Ratagal
Data Analyst | Power BI Enthusiast
