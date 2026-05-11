# Customer Behavior Analytics Project

## Overview
This project analyzes customer purchasing behavior to uncover business insights and support data-driven decision-making. The workflow includes data loading, cleaning, exploratory data analysis (EDA), SQL-based analysis, interactive dashboard development, and final business reporting.

The main objective is to identify customer trends, sales performance, and opportunities for business improvement through data analytics.

---

## Dataset
The dataset contains customer transaction and behavior data, including:

- Customer demographics (Age Group, Gender, Location)
- Product categories
- Purchase amounts
- Subscription status
- Review ratings
- Shipping methods
- Sales records

**Dataset Size:** ~5,000 customer records

---

## Tools & Technologies

- **Python**  
  - Pandas  

- **PostgreSQL**  
  - Data storage and SQL querying

- **Power BI**  
  - Interactive dashboard creation

- **Gamma**  
  - Presentation (PPT) generation

- **Jupyter Notebook**  
  - Data analysis workflow

---

## Project Steps

### 1. Data Loading
- Imported dataset into Python using Pandas
- Performed initial data inspection
- Checked data types and missing values

### 2. Data Cleaning
- Removed duplicates
- Handled missing/null values
- Standardized column names
- Corrected inconsistent data entries

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer demographics
- Evaluated sales and revenue trends
- Compared category performance
- Measured subscription adoption
- Assessed customer satisfaction ratings

### 4. SQL Analysis (PostgreSQL)
- Loaded cleaned dataset into PostgreSQL
- Wrote SQL queries for:
  - Revenue analysis
  - Customer segmentation
  - Category performance
  - Subscription insights
  - Sales aggregation

### 5. Power BI Dashboard Development
Built an interactive dashboard featuring:

- Customer count
- Average purchase amount
- Average review rating
- Subscription status breakdown
- Revenue by category
- Sales by category
- Revenue by age group
- Sales by age group
- Dynamic filters for gender, category, and shipping type

### 6. Business Report & Presentation
- Created insight-based analytics report
- Summarized key findings and recommendations
- Designed presentation slides using **Gamma**

---

## Dashboard Preview

**Customer Behavior Dashboard Highlights:**
- 5K Total Customers
- $198.84 Average Purchase Amount
- 3.62 Average Review Rating
- Electronics generates highest revenue
- Clothing has highest sales volume
- Senior customers contribute highest revenue
- Young adults make the most purchases

---

## Key Results

### Insights
1. Low Subscription Adoption

  -68.42% customers are non-subscribers, only 31.58% are subscribers.
  -Opportunity to increase retention and recurring revenue.

2. Electronics Generates Highest Revenue

  -Electronics contributes the most revenue (~$500K).
  -High-value products make it the main profit-driving category.

3. Clothing Has Highest Sales Volume

  -Clothing has the highest number of sales (~1,900 units).
  -Drives customer traffic and repeat purchases.

4. Outerwear Underperforms

  -Lowest sales and revenue among all categories.
  -May need better pricing, marketing, or product review.

5. Seniors Generate Highest Revenue

  -Senior customers spend the most overall.
  -Targeted campaigns can maximize profits.

6. Young Adults Buy Most Frequently

  -Highest number of purchases but lower spending per order.
  -Good opportunity for upselling.

7. Customer Satisfaction Needs Improvement

  -Average rating is 3.62/5.
  -Improving service and product quality can boost loyalty.

### Recommendations
1. Increase Subscription Sign-ups

  -Offer discounts, rewards, and exclusive subscriber benefits.

2. Expand Electronics Category

  -Add more products, bundles, and premium offers.

3. Improve Clothing Profitability

  -Use cross-selling and premium product recommendations.

4. Optimize Outerwear Category

  -Review pricing, promote seasonal sales, or remove weak products.

5. Focus on Senior Customers

  -Provide personalized offers and VIP experiences.

6. Upsell Young Adults

  -Offer bundles and premium suggestions.

7. Improve Customer Satisfaction

  -Enhance service, shipping, and collect customer feedback.

---

## How to Run

### 1. Clone Repository
```bash
git clone <repository-link>
cd customer-behavior-analytics

###2. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

###3. Run Python Analysis
Open Jupyter Notebook and execute:
jupyter notebook

###4. PostgreSQL Setup
Create PostgreSQL database
Import cleaned dataset
Run SQL queries provided in /sql

###5. Open Power BI Dashboard
Open .pbix file in Power BI Desktop

###6. View Report & Presentation
Read project report
Open Gamma presentation slides
