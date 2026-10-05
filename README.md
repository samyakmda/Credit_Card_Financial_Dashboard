# 💳 Credit Card Financial Dashboard – Customer & Transaction Analysis

*Analyzing credit card customer behavior, transaction trends, and financial performance to support strategic business and customer decisions using SQL and Power BI.*

---

## 📌 Table of Contents

* <a href="#overview">Overview</a>
* <a href="#business-problem">Business Problem</a>
* <a href="#dataset">Dataset</a>
* <a href="#tools--technologies">Tools & Technologies</a>
* <a href="#project-structure">Project Structure</a>
* <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
* <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
* <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
* <a href="#dashboard">Dashboard</a>
* <a href="#how-to-run-this-project">How to Run This Project</a>
* <a href="#final-recommendations">Final Recommendations</a>
* <a href="#author--contact">Author & Contact</a>

---

<h2><a class="anchor" id="overview"></a>Overview</h2>

This project evaluates credit card customer behavior, transaction trends, revenue, interest earnings, and customer performance to drive strategic insights for financial and customer management. A complete data pipeline was built using SQL for database creation and data preparation, and Power BI for interactive visualization and reporting.

---

<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Effective credit card performance and customer management are critical for monitoring revenue growth, transaction activity, and customer engagement. This project aims to:

* Monitor revenue and transaction performance across weekly and quarterly periods
* Determine customer and card-category contributions to revenue and transactions
* Analyze customer demographics and financial behavior
* Evaluate transaction patterns across different transaction types and expenditure categories
* Monitor customer activation and delinquency rates

---

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

* Multiple CSV files containing credit card transaction and customer information
* Customer data includes demographics, income, education, employment, and satisfaction information
* Transaction data includes card category, fees, transaction amount, transaction count, utilization, interest, and delinquency information
* Additional Week-53 data was appended to the customer and transaction tables for weekly performance analysis

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

* SQL (Table Creation, Data Import, Filtering)
* Power BI (Interactive Visualizations)
* DAX (Calculated Measures & Customer Segmentation)
* CSV

---

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```text
Credit_Card_Financial_Dashboard/
│
├── README.md
├── SQL Query - Financial Dashboard Data.sql
├── Credit Card Financial Dashboard-Customer.pdf
├── Credit Card Financial Dashboard-Transaction.pdf
├── Credit Card Financial Weekly Dashboard Report.pdf.pdf
│
├── credit_card.csv
├── cc_add.csv
├── customer.csv
└── cust_add.csv
```

---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

* Created SQL database and structured transaction and customer tables
* Imported credit card and customer CSV datasets into PostgreSQL
* Created separate tables for credit card transaction and customer-level data
* Handled date-format issues using PostgreSQL `datestyle` configuration
* Appended additional Week-53 transaction and customer records for updated analysis
* Prepared structured data for Power BI reporting and visualization

---

<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Revenue & Transaction Analysis:**

* Analyzed total revenue, transaction amount, transaction count, and interest earned
* Evaluated week-on-week and quarterly revenue trends
* Compared transaction performance across different periods

**Customer Analysis:**

* Analyzed revenue contribution by gender, age group, income group, education, and customer job
* Evaluated customer behavior across different demographic segments

**Credit Card Analysis:**

* Compared revenue and transaction contribution across card categories
* Analyzed transaction behavior across different card categories and transaction types

**Geographical & Risk Analysis:**

* Compared revenue contribution across states
* Monitored customer activation and delinquency rates
* Identified major geographic contributors to overall revenue

---

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Revenue Performance**: Overall revenue reached **₹57M**, while total interest earned was **₹8M** and total transaction amount reached **₹46M**.

2. **Week-on-Week Growth**: Week 53 revenue increased by **28.8%** compared with the previous week.

3. **Gender Contribution**: Male customers contributed **₹31M** in revenue, compared with **₹26M** from female customers.

4. **Card Category Performance**: Blue and Silver credit cards contributed **93% of overall transactions**, indicating a strong concentration in these card categories.

5. **Geographical Performance**: **TX, NY, and CA contributed 68% of overall revenue**, making these states major contributors to credit card performance.

6. **Customer Risk & Activation**: The overall customer activation rate was **57.5%**, while the overall delinquency rate was **6.06%**.

---

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

* Power BI Dashboard shows:

  * Revenue and Transaction Performance
  * Customer Demographics
  * Card Category Analysis
  * Transaction Type Analysis
  * State-wise Revenue
  * Customer Activation & Delinquency
  * Weekly and Quarterly Trends

The project includes separate **Customer** and **Transaction** dashboard reports for analyzing financial performance and customer behavior.

---

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone the repository:

```bash
git clone https://github.com/samyakmda/Credit_Card_Financial_Dashboard.git
```

2. Create the PostgreSQL database:

```sql
CREATE DATABASE ccdb;
```

3. Create the required tables and import the CSV files using:

```text
SQL Query - Financial Dashboard Data.sql
```

4. Load the primary datasets:

```text
credit_card.csv
customer.csv
```

5. Load the additional Week-53 datasets:

```text
cc_add.csv
cust_add.csv
```

6. Open the Power BI Dashboard reports:

```text
Credit Card Financial Dashboard-Customer.pdf
Credit Card Financial Dashboard-Transaction.pdf
```

---

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

* Focus customer engagement strategies on high-revenue customer segments
* Monitor the performance of Blue and Silver card categories due to their 93% transaction contribution
* Strengthen revenue strategies across major contributing states such as TX, NY, and CA
* Improve customer activation to increase the proportion of active customers
* Monitor delinquent accounts and develop targeted strategies to reduce delinquency
* Track weekly and quarterly revenue trends to identify changes in financial performance

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Samyak Meshram**
Data Analyst
📧 Email: [samyakmda@gmail.com](mailto:samyakmda@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/samyakmda/)  
🔗 [Portfolio](https://samyakmda.github.io/)
