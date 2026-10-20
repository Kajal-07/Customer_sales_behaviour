# Customer_sales_behaviour

## Overview

This project focuses on analyzing customer sales behavior to identify sales patterns, understand customer purchasing trends, and generate actionable business insights.

The project follows an end-to-end data analytics workflow, including data loading, exploratory data analysis (EDA), data cleaning, SQL analysis using PostgreSQL, and interactive dashboard development using Power BI. The findings are summarized in a project report and a presentation created using Gamma.

### Project Objectives
- Explore customer sales data and identify purchasing patterns.
- Understand sales trends across relevant business dimensions.
- Examine customer and product performance.
- Use SQL to answer business-related questions.
- Build an interactive Power BI dashboard.
- Communicate findings through a report and presentation.

## Dataset

The project uses a customer sales dataset containing information relevant to customer transactions and sales behavior.

Dataset source: https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI/blob/main/customer_shopping_behavior.csv

The dataset is examined to understand its structure, identify data-quality issues, and prepare it for analysis.

Key fields and dimensions will depend on the actual dataset and may include customer information, order details, product categories, transaction dates, quantities, and sales values.

## Tools & Technologies

| Tool | Purpose |

| Python | Data loading, exploration, and cleaning |
| Pandas & NumPy | Data manipulation and analysis |
| Matplotlib & Seaborn | Exploratory data visualization |
| PostgreSQL | Database storage and SQL analysis |
| SQL | Querying, aggregations, and business analysis |
| Power BI | Interactive dashboards and visualizations |
| Jupyter Notebook | Documenting Python analysis |
| Gamma | Creating the final presentation |

## Common Steps

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Examined dataset dimensions, column names, and data types.
- Reviewed sample records and descriptive statistics.

### 2. Exploratory Data Analysis (EDA)
- Analyzed numerical and categorical variables.
- Investigated missing values and duplicate records.
- Explored sales distributions and purchasing patterns.
- Used visualizations to identify trends and potential anomalies.

### 3. Data Cleaning
- Investigated missing and inconsistent values.
- Checked for duplicate records and invalid entries.
- Corrected data types and formatting where required.
- Validated the dataset before proceeding with analysis.

### 4. SQL Analysis Using PostgreSQL
- Loaded the prepared dataset into PostgreSQL.
- Wrote SQL queries to answer business questions.
- Used filtering, grouping, sorting, and aggregate functions.
- Analyzed customer and sales patterns across relevant dimensions.
- Used joins and advanced queries where appropriate.

### 5. Power BI Dashboard
- Connected Power BI to the prepared data.
- Created key performance indicators (KPIs).
- Designed charts and visualizations to communicate sales patterns.
- Added interactive filters and slicers where appropriate.
- Organized the dashboard to support business analysis.

### 6. Reporting and Presentation
- Summarized the analytical workflow and findings in a report.
- Created a presentation using Gamma.
- Presented key insights and potential business recommendations.

## Dashboard

The Power BI dashboard provides a visual overview of customer sales behavior and enables users to explore relevant patterns in the dataset.

Potential dashboard components, depending on the available data, include:
- Total Sales
- Total Orders or Transactions
- Customer-Level Sales Performance
- Product or Category Performance
- Sales Trends Over Time
- Regional or Segment-Level Analysis
- Customer Purchasing Patterns

### Dashboard Preview

Add a screenshot of the completed dashboard here.

`![Customer Sales Behavior Dashboard](screenshots/dashboard.png)`

**Power BI File:** Add a link to the `.pbix` file if it is available and safe to share.

## Results & Business Insights

This section will document the findings obtained from the actual analysis.

Areas of investigation may include:
- Products or categories contributing significantly to sales.
- Differences in purchasing patterns across customer groups.
- Changes in sales over time.
- Customer segments with distinct purchasing behavior.
- Potential opportunities to improve sales performance.

### Key Findings
1. [Add your first data-supported finding.]
2. [Add your second data-supported finding.]
3. [Add your third finding or business recommendation.]

All conclusions should be supported by the dataset, SQL results, or Power BI analysis.

## Project Deliverables

- Python notebook containing EDA and data-cleaning steps.
- Prepared dataset, where sharing is permitted.
- SQL scripts for PostgreSQL analysis.
- Power BI dashboard and screenshots.
- Project report.
- Gamma presentation.

## Repository Structure

```text
customer_sales_behavior/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── customer_sales_behavior.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── customer_sales_behavior.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── reports/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── requirements.txt
└── README.md
```

*This is a suggested structure. Adjust filenames and folders to match the actual repository.*

## How to Run It

### Prerequisites
- Python
- VS Code or Jupyter Notebook
- PostgreSQL and a database client such as pgAdmin
- Power BI Desktop
- Required Python libraries

### Step 1: Clone the Repository

```bash
git clone <your-github-repository-url>
cd customer_sales_behavior
```

### Step 2: Create and Activate a Virtual Environment

On Windows PowerShell:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run the Python Analysis

Open the notebook in VS Code or Jupyter Notebook and execute the cells in order to load the data, perform EDA, and clean the dataset.

### Step 5: Run the PostgreSQL Queries

- Start the PostgreSQL server.
- Create the project database.
- Import the prepared dataset into a table.
- Configure the database connection.
- Execute the SQL scripts in the `sql/` directory.

### Step 6: Open the Power BI Dashboard

Open the `.pbix` file in Power BI Desktop, configure the data source if required, and refresh the data.

### Step 7: Review the Report and Presentation

Open the report and presentation to review the methodology, findings, visualizations, and recommendations.


## Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, PostgreSQL, and Power BI. It combines data exploration, data cleaning, SQL querying, and visualization to investigate customer sales behavior and communicate meaningful business insights.

