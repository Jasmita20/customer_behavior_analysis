# customer_behavior_analysis
Data analytics project showcasing the customer behavior analysis using SQL, Python and PowerBI

📌 **Overview**

This project analyzes customer shopping behavior to uncover purchasing patterns, customer segments, and factors influencing purchase amounts.
Using Python, SQL, and Power BI, the project follows a complete data analytics lifecycle—from raw data exploration to interactive dashboard creation and business-ready reporting.
The objective is to transform transactional customer data into actionable insights that can support marketing, sales, and customer engagement strategies.

📁 **Dataset**

Total Records: 3,900 customer purchases

Total Columns: 18

Data Type: Structured customer transaction data

Key Attributes:

Customer demographics: Age, Gender, Location

Purchase details: Category, Item Purchased, Purchase Amount

Behavioral data: Subscription Status, Previous Purchases, Frequency

Experience metrics: Review Rating, Shipping Type, Discount Applied

Missing values were minimal and handled appropriately during data cleaning.

🛠️ **Tools & Technologies**

Python – Data loading, EDA, and cleaning

Pandas, NumPy, Matplotlib, Seaborn

PostgreSQL Server – Data storage and querying

SQL – Customer segmentation and trend analysis

Power BI – Interactive dashboard and KPI visualization

Gamma – Business presentation (PPT)

Jupyter Notebook / VS Code – Development environment

🔄 **Project Workflow**

1. Data Loading & Exploration
    Loaded dataset using Pandas
    Reviewed schema, data types, and summary statistics
2. Exploratory Data Analysis (EDA)
    Analyzed purchase amounts, ratings, and frequency
    Identified trends by category, age group, and gender
3. Data Cleaning & Preparation
    Handled missing review ratings using imputation
    Standardized column names and data formats
    Engineered features such as age groups and customer segments
4. Database & SQL Analysis
    Loaded cleaned data into PostgreSQL
    Wrote SQL queries to analyze:
    Revenue by category and age group
    Subscription vs non-subscription behavior
    Shipping type impact on purchase amount
    Customer loyalty segmentation
5. Dashboard & Reporting
    Built an interactive Power BI dashboard
    Created a detailed report and presentation using Gamma

📊 **Power BI Dashboard**

The Customer Behavior Dashboard provides an interactive overview of key business metrics:

Key KPIs:

Total Customers: 3.9K

Average Purchase Amount: $59.76

Average Review Rating: 3.75

Visual Insights:

Customer distribution by subscription status

Revenue and sales by product category

Revenue and sales by age group

Impact of subscription status, gender, category, and shipping type

Dynamic slicers for:

Subscription Status

Gender

Category

Shipping Type

The dashboard enables quick decision-making through clear, filterable insights.

📈 **Key Results & Insights**

- Clothing and Accessories generate the highest revenue and sales
- Subscribers contribute significantly higher revenue than non-subscribers
- Express shipping users show higher average purchase values
- Loyal and returning customers drive repeat revenue
- Discounts attract high-value customers without reducing average spend
- Younger and middle-aged customers contribute the most to total sales

▶️ **How to Run the Project**

1. Clone the repository
    git clone <repository-link>
2. Install Python dependencies
    pip install pandas numpy matplotlib seaborn
3. Run Python scripts/notebooks for EDA and data cleaning
4. Load cleaned data into PostgreSQL Server
5. Execute SQL queries for analysis
6. Open the Power BI (.pbix) file to explore the dashboard
7. Review the Gamma PPT for final insights and recommendations
