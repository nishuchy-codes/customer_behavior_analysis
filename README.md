🛍️ Customer Shopping Behavior Analysis

📌 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to identify spending patterns, customer segments, product preferences, and subscription behavior that can support strategic business decisions.

The project demonstrates an  end-to-end Data Analytics workflow using Python , MySQL,SQL and Power BI ,covering data cleaning , exploratory data analysis(EDA) ,database analysis,dashboard development, and business reporting.


🎯 Business Problem

Retail businesses collect large volumes of customer transaction data, but valuable insights often remain hidden without proper analysis.

This project aims to:
- Understand customer purchasing behavior
- Identify high-value customer segments
- Analyze product performance
- Evaluate subscription effectiveness
- Measure discount impact on sales
- Generate actionable business recommendations

---

📊 Dataset Summary

Dataset Type-Customer Shopping Transactions
Total Records-3,900
 Total Features-18
 Missing Values - 37 records in Review Rating 

Key Features

Customer Information

- Age
- Gender
- Location
- Subscription Status

Purchase Information

- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

Shopping Behavior

- Discount Applied
- Promo Code Used
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type

Data Quality

- Missing values found in the "Review Rating" column
- 37 missing records were handled during data cleaning


🛠️ Tools & Technologies

Programming Language - Python
Data Analysis-Pandas, NumPy
Visualization- Matplotlib, Seaborn
Database- MySQL
Query Language- SQL
Dashboarding- Power BI
Development Environment| Jupyter Notebook
Reporting| PowerPoint


🔄 Project Workflow

1. Data Preparation & Cleaning
The dataset was loaded into Python using Pandas and cleaned before analysis.

Tasks Performed

- Imported dataset using Pandas
- Inspected structure using "df.info()"
- Generated descriptive statistics using "df.describe()"
- Identified missing values
- Imputed missing Review Ratings using median values by product category
- Renamed columns using snake_case conventions
- Removed redundant features
- Validated data consistency

2. Feature Engineering
Created additional features to improve analysis:

Age Group
Customer ages were grouped into meaningful segments for demographic analysis.
Purchase Frequency

These features helped improve customer segmentation and behavioral analysis.

3. Database Integration

After cleaning:
- Connected Python to MySQL
- Loaded the processed dataset into a MySQL database
- Executed SQL queries to answer business questions
- Retrieved results for reporting and dashboard creation


4.📈 Exploratory Data Analysis (EDA)

The EDA focused on:

Customer Demographics
- Age distribution
- Gender distribution
- Location analysis

Purchasing Behavior
- Purchase amount distribution
- Seasonal purchasing trends
- Frequency of purchases

Product Performance
- Category popularity
- Product ratings
- Revenue contribution by product type

Promotions & Discounts
- Impact of discounts on spending
- Customer response to promotions

5.📊 Power BI Dashboard Development 
An interactive dashboard was created to visualize key business insights.

Dashboard Features

KPI Cards
- Total Revenue
- Total Customers
- Average Purchase Amount
- Subscriber Count

Interactive Visualizations
- Revenue by Gender
- Revenue by Age Group
- Product Category Performance
- Top-Rated Products
- Customer Segmentation
- Shipping Type Analysis
- Subscription Status Analysis

User Controls
- Filters
- Slicers
- Drill-down functionality


🔍 Key Insights

Customer Spending
Subscribers generally contribute higher revenue than non-subscribers.

Product Performance
Top-rated products consistently drive customer satisfaction and repeat purchases.

Discounts Dependency
Certain products rely heavily on discount-based purchases, highlighting pricing sensitivity.

Customer Loyalty
Customers with more purchase history show a stronger tendency to subscribe.

Demographics Insights
Specific age groups generate a larger share of total revenue and should be targeted through personalized marketing.


💡 Business Recommendations

Increase Subscription Adoption

Offer:
- Exclusive discounts
- Early access promotions
- Loyalty rewards

Strengthen Loyalty Programs
Encourage repeat customers to become loyal customers through incentive programs.

Optimize Discount Strategy
Balance revenue growth and profitability by reducing unnecessary discount dependency.

Promote High-Performing Products
Feature top-rated and best-selling products in marketing campaigns.

Target High-Value Segments

Focus marketing efforts on:
- High-revenue age groups
- Frequent shoppers
- Express shipping users

---

📂 Project Structure

Customer-Shopping-Behavior-Analysis/
│
└── customer_shopping_behavior.csv
└── customer_shopping_behavior.ipynb
└── customer_shopping.sql
└── customer_behavior dashboard.pbix
└── README.md

🚀 How to Run

Clone Repository
git clone https://github.com/https://github.com/nishuchy-codes/nishuchy-codes/customer-shopping-behavior-analysis.git
Install Required Packages
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
Launch Notebook :jupyter notebook
Execute SQL Queries
1. Import cleaned data into MySQL
2. Run scripts from:
sql/business_queries.sql

Open Power BI Dashboard
Open:customer_shopping_dashboard.pbix
using Power BI Desktop.

📦 Deliverables

- Cleaned Dataset
- Python Analysis Notebook
- SQL Business Queries
- Power BI Dashboard
- Business Analysis Report
- GitHub Documentation

👨‍💻 Author

Nishu Kumari

Data Analyst | SQL | Python | Power BI

⭐ If you found this project useful, feel free to star the repository.
