# Banking-Analysis-Dashboard
Interactive 7-page Power BI banking dashboard covering customers, accounts, transactions, loans &amp; credit risk, and branch performance, with built-in forecasting and anomaly detection. Data from Kaggle
🏦 Banking Dashboard — Power BI

An interactive, 7-page Power BI dashboard that analyses a retail bank's customers, accounts, transactions, loans, cards and branches, and adds **forecasting** and **anomaly detection** on top of the core KPIs.

> Built as my final Power BI project. Data was imported from Kaggle (Import mode).


## 📌 Project Overview

The goal of this project is to give bank managers one place to answer questions such as:

- Who are our customers, and what accounts do they hold?
- How are transactions distributed across merchants, cities and time?
- How risky is our loan portfolio (credit score, interest rate, loan amount)?
- Which branches perform best?
- Where is the business heading, and which data points look unusual?


## 📊 Dashboard Pages
| 1 | **Overview** | High-level KPIs, map, account/transaction trends and breakdowns |
| 2 | **Customer & Accounts** | Customer distribution, account types, balances, cities |
| 3 | **Transaction Analysis** | Transaction amounts and counts by merchant, city, card type and date |
| 4 | **Loans & Credit Risk** | Loan amounts, interest-rate bands, credit-score bins, loan details table |
| 5 | **Branch Performance** | Branch comparison, managers, map and matrix view |
| 6 | **Forecast** | Six line charts with Power BI's built-in forecasting + written insight under each |
| 7 | **Anomaly Detection** | The same six metrics with anomaly detection (95% sensitivity) + written insight |

The six forecast / anomaly metrics are: transaction count, customer count, account count, total transaction amount, loan count and average loan amount.

🗂️ Data Model

- **Data source:** Kaggle — [(https://www.kaggle.com/datasets/akrambelha/synthetic-banking-dataset-csv-sql-sqlite)]
- **Connection mode:** Import
- **Tables:** `customers` · `accounts` · `transactions` · `loans` · `cards` · `merchants` · `branches`

Main fields include `customer_id`, `account_id`, `transaction_id`, `loan_id`, `card_id`, `merchant_id`, `branch_id`, `amount_usd`, `balance_usd`, `loan_amount`, `interest_rate`, `credit_score`, `city`, `account_type`, `card_type`, `transaction_date`, `open_date` and `start_date`.

Custom elements: credit-score bins, amount bins, interest-rate bands, and measures such as **Avg Balance per Customer** and **Top Account Type**.

## ✨ Key Features

- 7 report pages on a consistent 1920 × 1080 layout
- Slicers for interactive filtering on the analysis pages
- **Reset bookmarks** with buttons to clear all filters quickly
- Map visuals for geographic analysis
- Built-in **forecasting** and **anomaly detection** with written summaries
- Custom visuals (Histogram, Inforiver Charts)

---

## 🛠️ Tools & Skills Demonstrated

- Power BI Desktop
- Data modelling (relationships between 7 tables)
- DAX (measures, bins and groups)
- Data visualisation and dashboard design
- Time-series forecasting and anomaly detection
- Storytelling with data (insight text under visuals)

---

## ▶️ How to Open

1. Download `Banking_dashboard.pbix` (check the **Releases** section if it is not in the file list).
2. Open it with the free [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Windows).
3. The data is already imported inside the file, so no connection setup is needed.

---

## 💡 Key Insights

- [Write your first finding here, e.g. the most common account type]
- [Which city or merchant has the highest transaction amount?]
- [What does the credit-score distribution say about loan risk?]
- [Which metric showed anomalies, and when?]

---

## 👤 Author

**[Khuzama ALwekhyan]**
