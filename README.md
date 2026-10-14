# Customer Shopping Behavior Analysis

**An End-to-End Data Analytics Project Using Python, SQL & Power BI**

An end-to-end data analytics project that explores customer purchasing patterns, product preferences, subscription behavior, discount usage, and payment preferences using Python, SQL, and Power BI.

The project demonstrates data cleaning, exploratory data analysis, SQL-based business analysis, and interactive dashboard development to turn raw shopping data into actionable business insights.

## Project Objectives
- Analyze customer purchasing patterns and product preferences.
- Compare purchase behavior across product categories and customer segments.
- Examine subscription status, discounts, and promotional code usage.
- Analyze payment methods, shipping preferences, and customer ratings.
- Build an interactive Power BI dashboard to support data-driven decision-making.
- 
## 🎯 Business Objectives

- Analyze customer purchasing patterns and product preferences.
- Compare purchasing behavior across product categories and customer demographics.
- Examine the relationship between subscription status and purchasing behavior.
- Evaluate payment methods, shipping preferences, and discount usage.
- Identify patterns in purchase frequency and customer reviews.
- Develop an interactive Power BI dashboard to communicate key business insights.

## 🛠️ Tools & Technologies

| Technology | Purpose |
|:--|:--|
| **Python** | Data cleaning, preparation, and exploratory data analysis |
| **Pandas & NumPy** | Data manipulation and transformation |
| **SQL** | Business analysis, aggregations, and customer segmentation |
| **Power BI** | Interactive dashboards and data visualization |
| **Git & GitHub** | Version control and project documentation |

## Dataset Overview

- **Total records:** 3,900
- **Total columns:** 18
- **Missing values:** 37 in the `Review Rating` column, identified during initial inspection.

The dataset contains customer demographics, product details, purchase amounts, previous purchases, payment methods, shipping preferences, subscription status, discounts, promotional codes, customer ratings, and location information.

### Data Cleaning
- Inspected data types and dataset structure.
- Identified and handled missing values using the documented cleaning method.
- Checked for duplicate records and inconsistent data.
- Prepared the data for exploratory analysis and visualization.

**Data Source:** Add the original dataset source and applicable license or usage terms before publishing.

## 🔄 Project Workflow

### 1. Data Preparation & Exploratory Data Analysis — Python

- Import and inspect the raw dataset.
- Evaluate data types, missing values, and duplicate records.
- Clean and transform data where necessary.
- Explore customer demographics and purchasing behavior.
- Perform exploratory analysis using descriptive statistics and visualizations.

### 2. Business Analysis — SQL

- Analyze purchasing behavior across product categories.
- Calculate average purchase amounts and relevant business metrics.
- Compare customer segments and subscription status.
- Investigate payment preferences and discount usage.
- Answer business questions using SQL queries and aggregations.

### 3. Dashboard Development — Power BI

- Design KPI cards to summarize key business metrics.
- Visualize purchasing patterns across categories and customer segments.
- Analyze payment methods, subscription status, and discount usage.
- Implement interactive slicers and filters for deeper analysis.
- Present insights through a clear, user-friendly dashboard.

### 4. Insights & Business Recommendations

- Interpret findings from Python, SQL, and Power BI.
- Identify meaningful patterns in customer purchasing behavior.
- Develop evidence-based recommendations to support business decisions.

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of customer purchasing behavior, product categories, purchase amounts, and relevant customer attributes.

### Dashboard Highlights

- **Key Performance Indicators (KPIs)**
- **Product Category Analysis**
- **Customer Demographic Analysis**
- **Purchase Frequency & Payment Preferences**
- **Subscription & Discount Analysis**
- **Interactive Filters & Slicers**

### Dashboard Preview

*The screenshot above displays the Power BI dashboard. Replace the image path with the location of your actual dashboard screenshot if needed.*

## 💡 Key Business Questions

The analysis aims to answer the following business questions:

1. Which product categories account for the largest share of purchase records?
2. How do purchase amounts vary across customer demographics?
3. How does subscription status relate to purchasing behavior?
4. Which payment methods are most frequently used?
5. How are discounts and promotional codes used across customer segments?
6. What patterns can be observed in customer purchase frequency and review ratings?

### Key Findings

**Add three to five verified findings from your analysis in this section.** Include actual metrics, relevant comparisons, and the business implications of each finding.

For example:

- **Product Category Analysis:** Identify the category with the highest number of purchase records.
- **Customer Segmentation:** Compare average purchase amounts across relevant customer groups.
- **Subscription Analysis:** Compare purchasing behavior between subscribers and non-subscribers.

*These are analysis prompts, not confirmed findings. Replace them with your actual results.*

## 📁 Repository Structure

```text
customer-shopping-behavior-analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   ├── data_cleaning.ipynb
│   └── exploratory_data_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_shopping_behavior_dashboard.pbix
│
├── images/
│   └── dashboard_overview.png
│
├── requirements.txt
├── .gitignore
└── README.md
```

*Update the filenames and folders to match your actual repository.*

## 🚀 How to Run the Project

### Prerequisites

- Python 3.x
- Jupyter Notebook or VS Code
- MySQL, PostgreSQL, or SQL Server, depending on the SQL queries used
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### Step 2: Set Up the Python Environment

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

### Step 3: Run the Python Analysis

Open the notebooks in the `python/` directory using Jupyter Notebook or VS Code. Execute the cells in order to reproduce the data preparation and exploratory data analysis.

### Step 4: Execute the SQL Queries

Load the dataset into your selected SQL database and execute the queries in `sql/customer_behavior_analysis.sql`. Follow the database setup instructions documented in the repository.

### Step 5: Open the Power BI Dashboard

Open the `.pbix` file in Power BI Desktop. If necessary, update the data source path to point to the CSV file in your local repository and refresh the data.

## 🔮 Future Improvements

- Implement customer segmentation using statistical or machine learning techniques.
- Automate data preparation and reporting workflows.
- Develop additional customer retention and purchasing metrics.
- Enhance dashboard interactivity and usability.
- Incorporate additional data to analyze customer behavior over time.

## 👤 Author

**Aastha Kashyap**

- **GitHub:** [Your GitHub Profile](https://github.com/Aastha0155)
- **LinkedIn:** [Your LinkedIn Profile](https://www.linkedin.com/in/aastha-kashyap-b07267227/)

---

*Developed as a data analytics portfolio project to demonstrate practical skills in Python, SQL, and Power BI.*
