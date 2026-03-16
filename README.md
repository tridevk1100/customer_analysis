📊 Customer Shopping Behavior – Data Analytics Project
Overview

This project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI. The goal of the project is to analyze customer shopping behavior, identify purchasing patterns, and generate business insights through data exploration, SQL analysis, and interactive dashboards.

The project covers the complete analytics pipeline from data loading and cleaning to visualization and reporting.

Dataset

The dataset used in this project contains customer purchase information, including:

Customer demographics

Product purchased

Purchase amount

Shipping type

Discount usage

Review rating

Subscription status

The dataset was loaded and processed using Python before being stored in a PostgreSQL database for SQL analysis.

Tools & Technologies

The following tools were used to complete the project:

Python – Data loading, cleaning, and exploratory data analysis

Pandas & NumPy – Data manipulation and preprocessing

PostgreSQL – Database storage and SQL queries

Power BI – Interactive dashboards and visualizations

Gamma – Presentation creation

Jupyter Notebook – Development environment

Project Workflow
1. Data Loading

The dataset was imported into Python using Pandas and inspected for structure and data types.

Tasks performed:

Load CSV dataset

Inspect columns and data types

Identify missing values

2. Data Cleaning

Data preprocessing steps were performed to ensure data quality.

Tasks performed:

Handle missing values

Correct inconsistent data formats

Remove duplicates

Prepare fields for SQL analysis

3. Exploratory Data Analysis (EDA)

EDA was performed using Python to understand customer behavior patterns.

Key analysis included:

Purchase distribution

Product popularity

Customer demographics

Spending patterns

Discount usage trends

4. SQL Analysis (PostgreSQL)

The cleaned dataset was loaded into PostgreSQL and analyzed using SQL queries.

Example analysis questions:

Which customers spent more than the average purchase amount?

Which products have the highest review ratings?

Do subscribed customers spend more?

Which products receive the most discounts?

Comparison of average purchase amount by shipping type

These queries helped derive business insights from the dataset.

5. Power BI Dashboard

An interactive dashboard was created in Power BI to visualize key metrics and trends.

Dashboard features include:

Total revenue overview

Customer purchase trends

Product performance analysis

Discount usage insights

Subscription vs non-subscription spending

The dashboard allows users to explore the data interactively.

Key Results & Insights

Some key insights discovered during the analysis:

Customers using express shipping tend to spend more on average.

Subscribed customers generate higher revenue compared to non-subscribers.

Certain products receive significantly more discounted purchases.

Review ratings help identify top-performing products.

These insights can help businesses improve marketing strategies and product positioning.

Presentation

A final project presentation was created using Gamma to summarize:

Project objectives

Analysis methodology

Key insights

Dashboard findings

How to Run the Project
1. Clone the repository
git clone https://github.com/yourusername/customer-shopping-analysis.git
2. Install required libraries
pip install pandas numpy sqlalchemy psycopg2-binary
3. Run the Python notebook

Open the Jupyter Notebook and execute the steps:

Load dataset

Perform data cleaning

Run EDA

Upload dataset to PostgreSQL

4. Run SQL queries

Execute the SQL queries in PostgreSQL to perform analytical analysis.

5. Open Power BI dashboard

Open the Power BI file to explore the interactive dashboard.

Project Structure
project-folder
│
├── data
│   └── customer_shopping_behavior.csv
│
├── notebooks
│   └── analysis.ipynb
│
├── sql
│   └── analysis_queries.sql
│
├── dashboard
│   └── powerbi_dashboard.pbix
│
├── presentation
│   └── project_presentation.ppt
│
└── README.md
Author

Tridev Koneti

Data Analyst | Data Engineering Enthusiast
Skills: Python, SQL, Power BI, PostgreSQL, Data Visualization
