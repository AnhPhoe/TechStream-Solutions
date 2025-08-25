# TechStream-Solutions
## Unit Economics Analysis – TechStream Solutions
### 1 Project Overview
This repository contains a full-cycle data analytics project focused on analyzing the Unit Economics of a fictional SaaS company, TechStream Solutions. It demonstrates practical application of business metrics, including:

- CAC (Customer Acquisition Cost)
- ARPU (Average Revenue Per User)
- COGS (Cost of Goods Sold)
- Gross Margin
- LTV (Customer Lifetime Value)
- LTV/CAC Ratio
Developed in Google Colab using Python and Pandas, this project follows the structure of a real-world analytics case. It is designed to be reproducible, insightful, and aligned with industry best practices.
### 2 Key Objectives
- Extract and transform data from various sources (marketing, payroll, expenses, customer behavior)
- Calculate business-critical metrics that drive profitability
- Interpret insights and recommend strategic improvements
- Showcase a complete ETL and insight pipeline for employers
### 3  Datasets Used
<img width="441" height="125" alt="image" src="https://github.com/user-attachments/assets/d0b0d7b2-3b30-4a53-9d3c-eb87bbbd1339" />

#### 4 Methods & Process
##### 4.1 Data Loading & Cleaning
- Extracted from Google Sheets using pandas.read_excel()
- Standardized date formats, filled missing values
- Filtered datasets by target month (March 2023)
##### 4.2 Metric Calculations

🧠 CAC – Customer Acquisition Cost
CAC = (CRM + Sales Salary + Marketing Salary + Ad Spend) / New Customers

💳 ARPU – Average Revenue Per User
ARPU = Total Revenue / Unique Customers

🧮 COGS – Cost of Goods Sold
Includes:
- Software costs (AWS, GCP, Jira)
- Communication tools (Slack, Zoom – allocated 60%)
- Engineering salaries

📐 Gross Margin
Gross Margin (%) = (Revenue - COGS) / Revenue \* 100

🔁 LTV – Life Time Value
LTV = ARPU × Avg Lifespan (in months) × Gross Margin / 100

⚖️ LTV/CAC Ratio
Benchmarks the efficiency of marketing spend.

#### 5  Results Summary
<img width="191" height="159" alt="image" src="https://github.com/user-attachments/assets/4116d8e5-d6f2-434f-9ead-5b7b52aa3ed0" />

#### 6 Insights & Recommendations

-  High CAC (>$1200) relative to LTV → risk of unsustainable growth
-  Strong Gross Margin (75.6%) indicates product is cost-efficient
-  LTV/CAC ratio below industry benchmark (3:1)
→ Marketing spend is not generating high-value customers effectively

- Recommended Actions:
Reallocate ad budget to more efficient channels (e.g., Google Ads vs Meta)
Improve onboarding and retention to increase LTV
Optimize acquisition funnel or offer freemium trials to lower CAC

 - Skills Demonstrated
- ✅ Data Cleaning & Preprocessing (Pandas)
- ✅ Business Metric Modeling (CAC, LTV, etc.)
- ✅ Real-World Data Simulation from Google Sheets
- ✅ Documentation & Insight Communication
- ✅ Reproducibility using Jupyter Notebook (.ipynb)
