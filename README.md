# Mahesh Customer Retention & Churn Analysis

## 📊 Project Overview

This Power BI dashboard focuses on **Customer Retention and Churn Analysis** to help understand why customers leave, how different features are used, and how revenue is distributed across plan tiers and regions. The dashboard enables data-driven decision-making to reduce churn and improve customer satisfaction.

---

## 🧩 Dashboard Components

### 1. Churn Reasons Analysis

* Table visual showing **reason codes** such as:

  * Budget
  * Competitor
  * Missing Features
  * Pricing
  * Support
  * Unknown
* Helps identify the most common reasons customers churn

### 2. Beta Feature Adoption

* Gauge chart showing **Count of is_beta_feature**
* Indicates how many users are using beta features

### 3. Churn Count

* Gauge chart representing **Count of churn_flag**
* Gives a quick snapshot of total churned customers

### 4. Feature Usage Trend

* Area/line chart showing **Sum of usage_count by feature_name**
* Helps understand which features are heavily used and which are declining

### 5. Revenue by Plan Tier

* Donut chart showing **Sum of ARR amount by plan tier**
* Plan tiers included:

  * Enterprise
  * Pro
  * Basic
* Useful for identifying revenue contribution by plan

### 6. Seats Distribution by Country

* Pie chart showing **Sum of seats by country**
* Countries include US, India, UK, AU, CA, FR

### 7. Support Resolution Time

* Bar chart showing **Sum of resolution_time_hours by ticket_id**
* Helps analyze customer support efficiency

---

## 📌 Key Metrics (KPIs)

* **Beta Feature Users:** ~25,000
* **Total Churned Customers:** 500
* **Highest Revenue Contribution:** Enterprise Plan
* **Top Country by Seats:** United States

---

## 🗺️ Filters & Slicers

* Industry (Cybersecurity, DevTools, EdTech, FinTech, HealthTech)
* Account Name
* Churn Flag
* Country
* Feedback / Churn Event Type

All visuals are fully interactive and cross-filtered.

---

## 🛠 Tools & Technologies Used

* Microsoft Power BI Desktop
* DAX Measures
* Data Modeling & Relationships
* Interactive Visual Analytics

---

## 🎯 Business Use Cases

* Identify key churn drivers
* Improve feature adoption
* Optimize pricing and plans
* Enhance customer support efficiency
* Strategic customer retention planning

---

## 👤 Author

**Mahesh S**
Customer Retention & Churn Analysis – Task 2

---

## 📄 Notes

* Dataset used for learning / internship purposes
* Dashboard can be extended with predictive churn models
* Suitable for internship tasks, interviews, and portfolio projects
