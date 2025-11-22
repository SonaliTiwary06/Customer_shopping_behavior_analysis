Customer Shopping Behavior Analysis

This repository presents an end-to-end data analysis project focused on understanding **customer shopping behavior** using Python, SQL, and Power BI. The project uncovers insights into customer demographics, spending patterns, product preferences, and subscription behavior. 


📌 Table of Contents

* [Project Overview](#project-overview)
* [Dataset Summary](#dataset-summary)
* [Exploratory Data Analysis (Python)](#exploratory-data-analysis-python)
* [SQL Analysis](#sql-analysis)
* [Power BI Dashboard](#power-bi-dashboard)
* [Business Recommendations](#business-recommendations)
* [Technologies Used](#technologies-used)
* [How to Run](#how-to-run)
* [Contact](#contact)



📍 Project Overview

This project analyzes 3,900 customer transactions to extract actionable insights that help businesses improve marketing, customer engagement, and product strategy. 



🗂️ Dataset Summary

* Rows:3,900
* Columns:18
* Includes:
    *Customer demographics (Age, Gender, Location, Subscription Status)
    *Purchase details (Item, Category, Amount, Season, Size, Color)
    *Shopping behavior (Discount, Promo Code, Frequency, Review Rating, Shipping Type)
* Missing Values:
    *37 missing entries in Review Rating column. 


🐍 Exploratory Data Analysis (Python)

Key steps performed during EDA: 

 ✔️ Data Preparation

* Loaded the dataset using pandas
* Explored structure using

   `df.info()`
   `df.describe()`

 ✔️ Handling Missing Data

* Imputed missing Review Rating values using median rating by category

 ✔️ Standardization

* Converted column names to snake_case

 ✔️ Feature Engineering

* Created age_group from age bins
* Derived purchase_frequency_days
* Removed redundant feature promo_code_used

 ✔️ Database Integration

* Connected Python to PostgreSQL
* Loaded cleaned data for SQL-based business analysis



🧮 SQL Analysis

A series of business questions were answered using SQL queries: 

1. Revenue comparison between genders
2. High-spending discount users
3. Top 5 rated products
4. Purchase amount comparison based on shipping type
5. Subscriber vs. Non-subscriber revenue
6. Items most dependent on discounts
7. Customer segmentation (New, Returning, Loyal)
8. Top 3 products per category
9. Relation between repeat purchases & subscription
10. Revenue contribution by age group



📊 Power BI Dashboard

An interactive dashboard was built to: 

* Visualize spending trends
* Compare demographics
* Analyze repeat purchase behavior
* Track top-performing products and categories

*(You can add the dashboard screenshot here when uploading to GitHub.)*


💡 Business Recommendations

Based on findings, the following strategies were proposed: 

* Boost subscription program with exclusive perks
* Introduce loyalty rewards for frequent buyers
* Optimize discount strategy to balance sales & margins
* Highlight top-rated products in marketing campaigns
* Target high-value age groups with personalized marketing



🛠️ Technologies Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* PostgreSQL
* Power BI
* Jupyter Notebook
* GitHub



🚀 How to Run

1️⃣ Clone the Repository


git clone https://github.com/your-username/customer-shopping-analysis.git


2️⃣ Install Dependencies


pip install -r requirements.txt


3️⃣ Run Python Notebook

Open `.ipynb` file and execute the cells.

4️⃣ SQL Setup

Import the cleaned dataset into PostgreSQL and execute SQL scripts.

5️⃣ Open Power BI File

Load the `.pbix` file to explore insights visually.



📬 Contact

Author: Sonali
Email: [sonai.dtg1@gmail.com](mailto:sonai.dtg1@gmail.com)
Skills: Data Analyst | Python | SQL | Power BI | Visualization



Just tell me!
