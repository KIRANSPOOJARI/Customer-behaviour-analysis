# Customer Behaviour Analysis 📊

Overview

This project analyzes **50,000 customer shopping records** to uncover purchasing patterns, customer behavior, and business insights. The workflow covers the complete data analytics lifecycle—from data loading and cleaning to SQL analysis, interactive dashboard creation, and business reporting.

---

 Dataset

* **Dataset Size:** 50,000 customer records
* **Domain:** Retail / E-commerce
* **Key Features:**

  * Customer ID
  * Age & Age Group
  * Gender
  * Product Category
  * Item Purchased
  * Purchase Amount
  * Review Rating
  * Subscription Status
  * Shipping Type
  * Payment Method
  * Previous Purchases
  * Purchase Frequency
  * Season
  * Discount Applied
  * Location

---

 Tools & Technologies

| Tool                     | Purpose                           |
| ------------------------ | --------------------------------- |
| **Python**               | Data loading, cleaning, EDA       |
| **Pandas**               | Data manipulation                 |
| **NumPy**                | Numerical operations              |             |
| **PostgreSQL / MySQL**   | SQL queries and business analysis |
| **Power BI**             | Interactive dashboard development |
| **Gamma**                | Project presentation (PPT)        |
| **MS Excel**             | Initial data review               |


 Project Workflow

### 1. Data Loading

* Imported the 50K dataset into Python.
* Verified data types and structure.

### 2. Data Cleaning

* Removed duplicates.
* Checked for missing values.
* Standardized column names.
* Corrected data formats.
* Created derived columns (e.g., Age Group).

### 3. Exploratory Data Analysis (EDA)

* Customer demographics analysis.
* Purchase behavior analysis.
* Revenue by category.
* Rating distribution.
* Subscription analysis.
* Shipping preference analysis.
* Payment method analysis.
* Age group comparison.

### 4. SQL Analysis

Performed business queries using PostgreSQL/MySQL, including:

* Total Revenue
* Average Purchase Amount
* Category-wise Revenue
* Customer Count
* Subscription Analysis
* Shipping Type Analysis
* Rating Analysis
* Purchase Frequency
* Top Performing Categories
* Customer Segmentation

### 5. Power BI Dashboard

Built an interactive dashboard featuring:

* KPI Cards
* Customer Count
* Average Purchase Amount
* Average Review Rating
* Revenue by Category
* Sales by Category
* Subscription Distribution
* Revenue by Age Group
* Sales by Age Group
* Interactive Filters:

  * Gender
  * Category
  * Shipping Type
  * Subscription Status

### 6. Reporting

Created a business report summarizing:

* Key findings
* Customer insights
* Revenue trends
* Business recommendations

### 7. Presentation

Developed a professional presentation using **Gamma** to showcase:

* Project overview
* Methodology
* Dashboard walkthrough
* Key insights
* Business recommendations

---

## Dashboard Highlights

**KPIs**

* 👥 Total Customers
* 💰 Average Purchase Amount
* ⭐ Average Review Rating

**Visualizations**

* Subscription Status (Donut Chart)
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Sales by Age Group

**Filters**

* Subscription Status
* Gender
* Category
* Shipping Type

---

## Key Results

* Analyzed 50,000 customer records**.
* Identified top-performing product categories.
* Compared revenue across customer age groups.
* Measured customer subscription trends.
* Evaluated shipping preferences and purchasing behavior.
* Built an interactive Power BI dashboard for business decision-making.
* Generated actionable insights to support marketing and sales strategies.

---

## Project Structure

```text
Customer-Behaviour-Analysis/
│
├── Dataset/
│   └── customer_shopping_data.csv
│
├── Python/
│   └── Customer_shopping_behaviour.ipynb
│
├── SQL/
│    └── PostgreSQL_Queries.sql
│  
├── Power BI/
│   └── Customer Behaviour Analysis.pbix
│
├── Report/
│   └── Customer_Behaviour_Report.pdf
│
├── Presentation/
│   └── Customer_Behaviour_Presentation.pdf
│
└── README.md
```

---

## How to Run

### Python

```bash
git clone https://github.com/yourusername/customer-behaviour-analysis.git

cd customer-behaviour-analysis

pip install pandas numpy  jupyter

jupyter notebook
```

### SQL

* Import the cleaned dataset into PostgreSQL or MySQL.
* Execute the SQL scripts to perform business analysis.

### Power BI

* Open the `.pbix` file.
* Refresh the data.
* Explore the dashboard using the interactive filters.

---

## Business Value

* Improved understanding of customer purchasing behavior.
* Identified revenue-driving product categories.
* Supported data-driven business decisions.
* Demonstrated an end-to-end data analytics workflow using industry-standard tools.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Python (Pandas, NumPy, Matplotlib, Seaborn)
* SQL (PostgreSQL/MySQL)
* Power BI
* Data Visualization
* Dashboard Design
* Business Reporting
* Presentation Development
* Data Storytelling
