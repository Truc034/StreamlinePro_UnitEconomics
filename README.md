# Unit Economics Analysis for TechStream Solutions
## 🧐 Project Overview
Welcome to **TechStream Solutions**! This repository contains a comprehensive unit economics analysis for flagship product **Streamline Pro** - a Software as a Service (SaaS) platform that provides comprehensive project management and collaboration tools for businesses of all sizes.

## 🎯 Business Context
**Company:** TechStream Solutions

**Product:** Streamline Pro

**Analysis Period:** March 2023 - Single month analysis for focused insights

TechStream Solutions has been operating for several years and has gathered significant data on costs and revenues. This analysis aims to understand the profitability of Streamline Pro on a per-customer basis through detailed unit economics calculations.

## 🔍 Project Objectives
By performing these calculations, TechStream Solutions aims to:

- **Identify the profitability** of acquiring and retaining customers
- **Assess the efficiency** of marketing and sales strategies
- **Make informed decisions** on scaling operations and optimizing resource allocation
- **Guide strategic decisions** for sustainable growth and profitability maximization

## 💾 Data Sources
### Primary Data Source

The main datasets are available in the shared Google Drive folder:

📁[TechStream Solutions Data](https://drive.google.com/drive/folders/1qhOW9Y2orRXuzbX-kXEmuJ7TMQiRs2Uv)

### Backup Data Repository

⚠️ **Important**: In case the Google Drive link becomes unavailable, all data files are also backed up in this repository:

📁 [Backup Data Repository](https://github.com/Truc034/StreamlinePro_UnitEconomics/tree/main/TechStreamData)

## 📚 Dataset Descriptions
### 1. Monthly Expenses ([`Monthly_expenses.xlsx`](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FTruc034%2FStreamlinePro_UnitEconomics%2Frefs%2Fheads%2Fmain%2FTechStreamData%2FMonthly%2520expenses.xlsx&wdOrigin=BROWSELINK))

- **Purpose**: Track operational expenses by category
- **Fields**: month, category, item, amount

### 2. Payroll Data ([`Payroll.xlsx`](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FTruc034%2FStreamlinePro_UnitEconomics%2Frefs%2Fheads%2Fmain%2FTechStreamData%2FPayroll.xlsx&wdOrigin=BROWSELINK))

- **Purpose**: Track employee compensation by department
- **Fields**: month, department, employee_name, position, paid

### 3. Daily Marketing Spending ([`daily_marketing_spendings.xlsx`](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FTruc034%2FStreamlinePro_UnitEconomics%2Frefs%2Fheads%2Fmain%2FTechStreamData%2Fdaily_marketing_spendings.xlsx&wdOrigin=BROWSELINK))

- **Purpose**: Track marketing investments across channels
- **Fields**: date, channel, spending

### 4. Receipt History ([`receipts_history.xlsx`](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FTruc034%2FStreamlinePro_UnitEconomics%2Frefs%2Fheads%2Fmain%2FTechStreamData%2Freceipts_history.xlsx&wdOrigin=BROWSELINK))

- **Purpose**: Track revenue transactions and customer acquisition
- **Fields**: date, customer_id, receipt_amount, new_customer

### 5. Customer Lifespan ([`customer_lifespan_data.xlsx`](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2FTruc034%2FStreamlinePro_UnitEconomics%2Frefs%2Fheads%2Fmain%2FTechStreamData%2Fcustomer_lifespan_data.xlsx&wdOrigin=BROWSELINK))

- **Purpose**: Track customer lifecycle from acquisition to churn
- **Fields**: customer_id, start_date, churn_date

## 📊 Analysis Notebook
All detail computations and conclusions are included in 📁[this notebook](https://github.com/Truc034/StreamlinePro_UnitEconomics/blob/main/techstream.ipynb), includes:
- Data loading
- Revenue & cost aggregation
- Marketing cost allocation
- Metric calculations
- Conclusion and recommendation

## 📈 Key Metrics Analyzed
This analysis focuses on calculating the following critical unit economics metrics:

1. **Customer Acquisition Cost (CAC)** - Cost to acquire a new customer
2. **Average Revenue Per User (ARPU)** - Average revenue generated per user
3. **Cost of Goods Sold (COGS)** - Direct costs associated with service delivery
4. **Gross Margin** - Profitability after direct costs
5. **Customer Lifetime Value (LTV)** - Total revenue expected from a customer
6. **LTV/CAC Ratio** - Efficiency metric for customer acquisition

| Metric            | Value       |
|-------------------|-------------|
| **CAC**           | $1,213.97   |
| **ARPU**          | $284.36     |
| **COGS**          | $20,264     |
| **Gross Margin**  | 75.6%       |
| **LTV**           | $2,115.65   |
| **LTV/CAC**       | 1.74        |

## 📌 Key Findings
### ✅ Positive Indicators

- **Strong Gross Margin (75.6%)** - Indicates efficient cost management
- **Healthy LTV/CAC Ratio (1.74)** - Company earns $1.74 for every $1 spent on acquisition
- **Stable Customer Base** - Average lifespan of 9.8 months

### ✈️ Areas for Improvement

- **Customer Acquisition Cost** - Opportunities to optimize marketing spend
- **Customer Retention** - Potential to extend average lifespan beyond 9.8 months

## 💡 Business Recommendations

- **Monitor LTV/CAC monthly** to track acquisition performance
- **Optimize marketing channels** to reduce CAC
- **Implement retention strategies** to increase customer lifespan
- **Explore upselling opportunities** to boost ARPU
- **Maintain operational efficiency** to preserve gross margin

## 🎓 Learning Outcomes
This project demonstrates:

- SaaS business metrics calculation
- Data integration from multiple sources
- Financial analysis and interpretation
- Business intelligence reporting
- Python data analysis skills

## 🤝 Contributing
Feel free to fork this repository and submit pull requests for improvements or additional analysis features.

***

**Note:** This analysis is based on simulated data for educational purposes.
