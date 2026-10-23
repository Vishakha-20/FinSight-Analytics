# FinSight Analytics — Financial Performance & ETL Dashboard

An end-to-end financial data analytics project that uses **Python, MySQL, SQL, and Power BI** to transform financial datasets into meaningful business insights.

## 📌 Project Overview

FinSight Analytics focuses on analyzing financial operations through a structured ETL (Extract, Transform, Load) pipeline and interactive dashboard reporting. It brings together financial transactions, payables, receivables, budgets, and employee expense claims to support financial monitoring and decision-making.

## 🎯 Project Objectives

- Automate financial data extraction and transformation using Python.
- Store and organize processed financial data in MySQL.
- Analyze financial performance and budget variances using SQL.
- Explore accounts payable, accounts receivable, and expense claims.
- Present key financial metrics through Power BI dashboards.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Data cleaning and ETL automation |
| Pandas & NumPy | Data manipulation and transformation |
| MySQL | Relational database and data storage |
| SQL | Financial data querying and analysis |
| Power BI | Interactive dashboards and visualization |
| Excel | Source financial datasets |

## 📂 Project Structure

```text
FinSight-Analytics/
├── data/
│   ├── General-Ledger.xlsx
│   ├── Accounts-Payable.xlsx
│   ├── Accounts-Receivable.xlsx
│   ├── Budget-Forecast.xlsx
│   └── Expense-Claims.xlsx
├── sql/
│   ├── schema.sql
│   └── finance_analytics_data.sql
├── screenshots/
├── etl_pipeline_1.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 📊 Areas of Analysis

- **General Ledger:** Financial transaction records and ledger analysis.
- **Accounts Payable:** Outstanding payments and supplier obligations.
- **Accounts Receivable:** Customer balances and receivables.
- **Budget & Forecast:** Comparison of budgeted and actual financial performance.
- **Expense Claims:** Employee expense monitoring and analysis.

## ⚙️ Setup and Installation

### 1. Clone the repository

```bash
git clone https://github.com/Vishakha-20/FinSight-Analytics.git
cd FinSight-Analytics
```

### 2. Install dependencies

Make sure Python 3.9 or later is installed.

```bash
pip install -r requirements.txt
```

### 3. Configure MySQL

- Install and start MySQL Server.
- Create a database named `finance_analytics`.
- Execute the SQL scripts in the `sql/` directory as appropriate for your setup.
- Configure the database connection settings in `etl_pipeline_1.py`.

**Security note:** Use environment variables or a local configuration file excluded by `.gitignore` to store database credentials. Never commit real passwords to GitHub.

### 4. Run the ETL pipeline

After confirming the input files and database configuration, run:

```bash
python etl_pipeline_1.py
```

The pipeline is intended to extract, transform, and load the financial datasets into MySQL.

### 5. Build the Power BI dashboard

Connect Power BI Desktop to the MySQL database, select the relevant tables, and create visualizations for financial performance and operational metrics.

## 📈 Expected Outcomes

- A structured financial analytics database.
- A repeatable Python ETL workflow.
- Financial reporting across multiple business areas.
- Interactive visualizations to support data-driven decisions.

## 🔮 Future Enhancements

- Add KPI cards for key financial metrics.
- Create trend analysis for monthly expenses and cash flow.
- Add automated data quality checks and validation.
- Expand SQL analysis with advanced queries and performance metrics.
- Improve dashboard interactivity with filters and drill-through reports.

## ⚠️ Data and Project Notes

This project uses financial practice datasets. Validate the source data, schema, and database configuration before running the pipeline. Dashboard metrics depend on the available fields and implemented calculations.

## 👩‍💻 Author

**Vishakha Bisen**

GitHub: [Vishakha-20](https://github.com/Vishakha-20)

---

*FinSight Analytics — Turning financial data into actionable insights.*
