# Customer Churn & Retention Analytics Dashboard

## 📌 Project Overview
Customer churn directly impacts business growth and revenue.  
This project focuses on identifying **high-risk customers**, estimating **revenue at risk**, and recommending **actionable retention strategies** using customer behavioral data.

The project combines **Python-based analytics** with an **interactive Power BI dashboard** to bridge the gap between data insights and business decision-making.

---

## 🎯 Business Problem
Many businesses struggle to answer critical questions such as:
- Which customers are most likely to churn?
- How much revenue is at risk due to churn?
- Which retention actions should be prioritized?

This project addresses these questions by transforming raw transaction data into **decision-ready insights**.

---

## 🧠 Key Objectives
- Analyze customer behavior using transaction data
- Identify high-risk churn customers
- Quantify revenue at risk
- Recommend targeted retention actions
- Present insights through an interactive dashboard

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy)
- **Power BI**
- **Data Analytics & Feature Engineering**
- **Business Intelligence**
- **Data Storytelling**

---

## 📂 Dataset
- Online retail transaction dataset
- Customer-level purchase history
- Fields include invoice date, quantity, price, customer ID, and transaction value

*(Public dataset used for learning and demonstration purposes)*

---

## 🔄 Project Workflow

### Phase 1: Data Cleaning & Preparation (Python)
- Removed missing customer IDs
- Filtered cancelled invoices
- Created total transaction value
- Converted date fields into proper datetime format

### Phase 2: Feature Engineering (RFM Analysis)
- **Recency**: Days since last purchase
- **Frequency**: Number of transactions
- **Monetary**: Total spend per customer

### Phase 3: Churn Risk Identification
- Defined churn risk logic using recency and frequency behavior
- Classified customers into **High Risk** and **Low Risk**
- Calculated churn probability scores

### Phase 4: Retention Strategy Mapping
- Assigned retention actions based on churn risk and customer value
- Examples:
  - Discount Email / Push Notification
  - Personal Call + Premium Offer

### Phase 5: Power BI Dashboard Development
- Built KPI cards:
  - Total Customers
  - High-Risk Customers
  - Revenue at Risk
- Visualized:
  - High-risk customers by retention action
  - Revenue at risk by retention action
- Enabled interactive cross-filtering for business exploration

---

## 📊 Key Insights
- A significant portion of customers fall into the **high-risk churn segment**
- Revenue at risk is not evenly distributed across customers
- Different retention actions impact **customer count** and **revenue** differently
- Retention prioritization should be driven by **financial impact**, not volume alone

---

## 📈 Dashboard Preview
*(Add screenshot of your Power BI dashboard here)*

---

## 💡 Business Value
- Helps businesses proactively reduce churn
- Supports data-driven retention planning
- Translates analytics into clear business actions
- Demonstrates how analytics directly impacts revenue protection

---

## 🧪 Limitations & Future Improvements
- Churn logic is rule-based (can be enhanced with ML models)
- No real-time data integration
- Future scope:
  - Machine learning churn prediction
  - A/B testing of retention strategies
  - Automated data refresh pipelines

---

## 👤 Author
**Prashant Singh**  
Aspiring Data Analyst | Customer Analytics | Business Intelligence  

📌 *This project is part of my learning journey in data analytics and business intelligence.*

---

## ⭐ If You Found This Useful
Feel free to star ⭐ the repository.

