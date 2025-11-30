💳 **Credit Card Transaction & Customer Report – Spending & Demographic Insights**
Analyzing transaction patterns, customer demographics, and card usage to uncover revenue drivers and optimize financial strategies using Excel, PostgreSQL, and Power BI.

---

📌 **Table of Contents**

* Overview
* Business Problem
* Dataset
* Tools & Technologies
* Project Structure
* SQL Integration
* Dashboard
* Research Questions & Key Findings
* How to Run This Project
* Final Recommendations

---

📊 **Overview**
This project analyzes **656K customers and 45M transactions** to uncover spending trends, card usage behavior, and demographic insights. Two dashboards—**Transaction Insights** and **Customer Insights**—were developed to help stakeholders explore revenue patterns, monitor usage behavior, and support data-driven business decisions.

---

❓ **Business Problem**
Banks and financial institutions need to understand what drives **transaction volume, card usage, and customer profitability**. This project aims to:

* Segment customers by demographics and card category
* Identify high-revenue states, age groups, and professions
* Assess transaction gateways (swipe, chip, online) for adoption opportunities
* Recommend strategies for revenue growth and customer engagement

---

📂 **Dataset**

* File: `data/credit_card.csv`,`data/customer.csv`,`data/cc_add.csv`,`data/cc_add.csv`,`data/cust_add.csv`
* Records: 45M transactions, 656K customers
* Attributes: Customer demographics, card category, transaction type, revenue, interest earned, and state

---

🛠️ **Tools & Technologies**

* **Excel**: Source file for transactional and customer data
* **PostgreSQL**: Used to import Excel data for Power BI integration
* **Power BI**: Interactive dashboards for stakeholder reporting

---

🗂️ **Project Structure**

```
credit-card-transaction-report/
├── sql/                      # SQL import scripts
│   └── SQL Query - Financial Dashboard Data.sql
├── dashboard/                # Power BI dashboards
│   └── Powerbi.pbix
├── data/                     # Dataset
│   └── credit-card-transactions.csv
├── images/                   # Dashboard previews
│   └── transaction-dashboard.png
└── README.md                 # Documentation
```

---

🧾 **SQL Integration**

* No data cleaning or transformation was performed
* Excel file was imported into PostgreSQL using basic SQL commands
* Data was then exported from PostgreSQL into Power BI for dashboard creation
* This setup ensured smooth integration and dashboard refresh capability

---

📈 **Dashboard**

The report includes **two dashboards**, each serving a different analytical purpose:

---

#### **📌 Dashboard 1 — Transaction Insights (Primary Page)**

This dashboard provides detailed visibility into transaction volume, revenue distribution, and usage behavior. It includes:

* **Revenue breakdown by transaction type** (swipe, chip, online)
* Top **spending categories** such as fuel, bills, groceries, and entertainment
* **Weekly revenue trend chart** to track seasonal and behavioral patterns
* **Card category-wise spending and frequency analysis**
* KPIs showing revenue, total transactions, and interest contribution

Purpose: *Designed for operations and product teams to track spending behavior and identify adoption opportunities for online transactions.*

---

#### **📌 Dashboard 2 — Customer Insights**

This dashboard highlights customer behavior and segmentation patterns. It includes:

* Revenue distribution based on **age, gender, income level, and education**
* **Profession-wise contribution** to spending and profitability
* **Card category adoption rate** across customer types
* State-wise revenue distribution heatmap
* Customer satisfaction score (CSS) overview

Purpose: *Used by marketing, analytics, and customer engagement teams for targeted campaigns and portfolio strategies.*

---

💡 **Key Business Insights**

* **Card Category:** Blue cards dominate (₹46M, 83% of revenue)
* **Spending Categories:** Bills (₹14M), Entertainment (₹10M), Fuel & Grocery (₹9M each)
* **Transaction Gateway:** Swipe (₹35M), Chip (₹17M), Online (₹3M) → digital adoption gap
* **Demographics:**

  * Age 30–50 contributes most revenue
  * Males slightly higher spend (₹30M vs ₹25M females)
  * High-income group contributes ₹22M
* **Geography:** CA, TX, NY are top-performing states

---

🔍 **Research Questions & Key Findings**

| Question                                     | Key Findings                               |
| -------------------------------------------- | ------------------------------------------ |
| Which card category drives the most revenue? | Blue cards contribute 83% of total revenue |
| Which age group is most profitable?          | 30–50 years dominate spending              |
| How do transaction gateways perform?         | Swipe leads, online adoption remains low   |
| Which states generate the highest revenue?   | CA, TX, NY are top contributors            |
| Which professions contribute most?           | Businessmen and white-collar professionals |

---

⚙️ **How to Run This Project**

1. Clone the repository

   ```bash
   git clone https://github.com/swarnali2001/Credit-card-transaction-and-customer-report.git  
   cd Credit-card-transaction-and-customer-report
   ```
2. Open dataset → `data/credit-card-transactions.csv`
3. Import into PostgreSQL → `sql/transaction-import.sql`
4. View dashboard → `dashboard/credit-card.pbix`

---

✅ **Final Recommendations**

* Promote **online transactions** to close the digital adoption gap
* Target **high-income and business segments** for profitability
* Launch **regional campaigns** in CA, TX, NY
* Focus on **age 30–50 demographic** for maximum impact
* Enhance **loyalty programs** to retain high-value customers

---

If you want next:
✨ **LinkedIn Post Version**
📄 **Resume Bullet**
🎙️ **Interview Pitch (30-60 seconds)**

Just say: **“Make all three.”**
