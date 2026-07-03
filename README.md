# 🛡️ Insurance Analytics Dashboard using Power BI

An interactive **Business Intelligence Dashboard** developed using **Microsoft Power BI** to analyze insurance policies, customer demographics, premium collections, coverage amounts, and claim performance. This dashboard enables stakeholders to monitor key business metrics, identify trends, and make data-driven decisions.

---

## 📌 Project Overview

Insurance companies manage large volumes of policy and claims data. Manual reporting is time-consuming and often fails to provide actionable insights.

This project transforms raw insurance data into an interactive dashboard that helps analyze:

- Premium Revenue
- Coverage Amount
- Claim Amount
- Policy Performance
- Claim Status
- Customer Demographics
- Business KPIs

---

## 📊 Dashboard Preview

<img width="1375" height="736" alt="Image" src="https://github.com/user-attachments/assets/25ce45b7-5732-4695-9582-569ca7dcd489" />

## 🎯 Business Objectives

- Monitor overall insurance business performance
- Analyze premium revenue by policy type
- Track claim settlement status
- Compare active and inactive policies
- Analyze customer demographics
- Support data-driven business decisions

---

## 📂 Dataset

The dataset contains information related to insurance policies, customers, and claims.

### Policy Information

- Policy Number
- Policy Type
- Policy Status
- Premium Amount
- Coverage Amount

### Customer Information

- Customer ID
- Gender
- Age Group

### Claim Information

- Claim Number
- Claim Status
- Claim Amount

---

## 📈 Dashboard KPIs

| KPI | Value |
|------|--------|
| Premium Amount | ₹5.98M |
| Coverage Amount | ₹600.55M |
| Claim Amount | ₹16.91M |
| Active Policies | 5.82K |
| Inactive Policies | 4.19K |

---

## 📊 Dashboard Features

### 📌 Executive KPIs

- Total Premium Amount
- Total Coverage Amount
- Total Claim Amount

### 📌 Policy Analysis

- Premium Amount by Policy Type
- Active vs Inactive Policies
- Policy Performance Summary

### 📌 Claims Analysis

- Claim Status Distribution
- Claim Amount by Age Group
- Claim Status Matrix

### 📌 Customer Analysis

- Gender Distribution
- Customer Segmentation

### 📌 Interactive Filters

- Policy Number
- Claim Number
- Customer ID

---

## 💡 Key Business Insights

- Travel insurance generates the highest premium revenue.
- More than 58% of policies are currently active.
- Rejected claims are higher than settled claims, indicating opportunities to improve the claim approval process.
- Adults contribute the highest claim amount among all age groups.
- Male and female customer distribution is nearly equal.

---

## 🛠️ Power BI Features Used

### Data Preparation

- Power Query
- Data Cleaning
- Data Transformation

### Data Modeling

- Relationships
- Star Schema
- Data Model Optimization

### DAX Measures

Example:

```DAX
Total Premium =
SUM(InsuranceData[PremiumAmount])

Total Coverage =
SUM(InsuranceData[CoverageAmount])

Total Claim =
SUM(InsuranceData[ClaimAmount])

Active Policies =
CALCULATE(
COUNT(InsuranceData[PolicyNumber]),
InsuranceData[PolicyStatus]="Active"
)
```

---

## 📊 Visualizations Used

- KPI Cards
- Bar Chart
- Donut Chart
- Line Chart
- Matrix Table
- Interactive Slicers

---

## 🧰 Technologies Used

| Tool | Purpose |
|------|----------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI Calculations |
| CSV Dataset | Data Source |

---

## 📁 Repository Structure

```text
Insurance-Analytics-Dashboard/
│
├── Dashboard/
│   └── Insurance_Dashboard.pbix
│
├── Dataset/
│   └── InsuranceData.csv
│
├── Screenshots/
│   └── Dashboard_Overview.png
└── README.md
```

---

## 🚀 How to Use

1. Clone the repository.

```bash
git clone https://github.com/yourusername/Insurance-Analytics-Dashboard.git
```

2. Open the project using **Microsoft Power BI Desktop**.

3. Load the dataset if prompted.

4. Explore the interactive dashboard using slicers and filters.

---

## 📚 Skills Demonstrated

- Business Intelligence
- Data Visualization
- Dashboard Design
- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- Power Query
- KPI Reporting
- Analytical Thinking
- Business Analytics

---

## 📈 Future Enhancements

- Real-time dashboard using SQL Server
- Automated data refresh
- Forecasting using Power BI
- Customer churn prediction
- Fraud detection analytics
- Drill-through reports
- Row-Level Security (RLS)

---

## 👨‍💻 Author

**Vivekananda Survi**


## ⭐ If you found this project useful, consider giving it a star!
