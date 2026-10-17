# 📊 PhonePe Transaction Analysis using Power BI

An interactive data analytics and visualization project built using **Microsoft Power BI** to explore PhonePe transaction data, analyze transaction amounts, examine service categories, and understand payment outcomes.

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Power Query](https://img.shields.io/badge/Power%20Query-Data%20Transformation-217346?style=for-the-badge)](https://learn.microsoft.com/en-us/power-query/)
[![Excel](https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)

## 📌 Project Overview

This project focuses on analyzing PhonePe transaction data using Power BI to transform raw data into meaningful information through data preparation, exploration, and visualization.

The report uses an Excel dataset and Power Query to prepare transaction records for analysis. The resulting Power BI report provides a foundation for examining transaction amounts, user activity, service types, payment statuses, and transaction reasons.

The goal is to demonstrate practical skills in data cleaning, data profiling, business intelligence, and interactive dashboard development.

## 🎯 Project Objectives

- Transform and prepare raw transaction data for analysis.
- Analyze transaction amounts and transaction records.
- Examine transaction distribution across different service categories.
- Understand successful and failed payment outcomes.
- Explore transaction reasons and user-level activity.
- Present information through clear and interactive Power BI visualizations.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI Desktop | Report development and data visualization |
| Power Query Editor | Data cleaning and transformation |
| Microsoft Excel | Source dataset and data storage |
| Column Profiling | Inspecting data quality and value distributions |
| DAX (if implemented) | Creating calculated measures and KPIs |

## 📂 Repository Structure

```text
PhonePay_Transaction_Analysis_Using_Power_BI/
│
├── PhonePay_Analysis.pbix
├── Phonepe-Final-Dataset.xlsx
├── README.md
├── Screenshot 2026-10-18 013220.png
├── Screenshot 2026-10-18 013946.png
└── Screenshot 2026-10-18 014143.png
```

## 📈 Dataset Description

The project uses `Phonepe-Final-Dataset.xlsx` as its source dataset.

The transaction data includes fields such as:

| Column | Description |
|---|---|
| `Transaction_ID` | Unique identifier associated with a transaction |
| `Amount` | Transaction amount |
| `User_ID` | Identifier associated with a user |
| `Service` | Service category |
| `Service Type` | Specific service or transaction type |
| `Payment_Status` | Transaction outcome, such as successful or failed |
| `Reason` | Recorded transaction reason or status-related information |

These fields support the exploration of transaction patterns, service distribution, payment outcomes, and user activity.

## 🔄 Project Workflow

1. **Data Collection:** Load the Excel dataset into Power BI Desktop.
2. **Data Transformation:** Use Power Query Editor to inspect columns, assign appropriate data types, and prepare the data for analysis.
3. **Data Profiling:** Examine column quality, value distribution, distinct values, and potential data-quality issues.
4. **Data Analysis:** Explore transaction amounts, service categories, payment statuses, and related fields.
5. **Data Visualization:** Build Power BI report visuals to present patterns and comparisons.
6. **Reporting:** Save the report as a `.pbix` file for further analysis and reuse.

## 🔍 Key Business Questions

The report can be used to investigate questions such as:

- What is the distribution of transaction amounts?
- Which service categories appear most frequently?
- What proportion of recorded transactions is successful or failed?
- Which transaction reasons occur most frequently?
- How are transaction records distributed across users?
- What patterns can be identified by comparing transaction amount, service type, and payment status?

## 🖼️ Project Screenshots

### Screenshot 1

![PhonePe Power BI Project Screenshot 1](Screenshot%202026-10-18%20013220.png)

### Screenshot 2

![PhonePe Power BI Project Screenshot 2](Screenshot%202026-10-18%20013946.png)

### Screenshot 3

![PhonePe Power BI Project Screenshot 3](Screenshot%202026-10-18%20014143.png)

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open `PhonePay_Analysis.pbix`.
4. If Power BI requests the source file, update the data source path to `Phonepe-Final-Dataset.xlsx`.
5. Refresh the data if necessary.
6. Explore the available report pages and visualizations.

## 💡 Skills Demonstrated

- Data cleaning and transformation
- Exploratory data analysis
- Data quality assessment and profiling
- Business intelligence and reporting
- Data visualization
- Working with Excel datasets in Power BI

## 👨‍💻 Author

**Saurav Singh**

Electronics and Instrumentation Engineering Student

[GitHub Profile](https://github.com/saurav13singh2003-crypto)

## 📄 License

This repository is intended for educational and portfolio purposes. Dataset ownership and usage rights remain with their respective owners. Please verify the dataset's redistribution permissions before reusing it.

---

⭐ If you find this project useful, consider giving the repository a star.
