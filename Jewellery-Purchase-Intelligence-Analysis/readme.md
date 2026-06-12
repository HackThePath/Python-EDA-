# 💎 Jewellery Purchase Intelligence Analysis (Python EDA)

![Restaurant Banner](https://github.com/HackThePath/Python-EDA-/blob/041abec31725da8e920765beb15e8cc484b23888/Jewellery-Purchase-Intelligence-Analysis/img.png)

## Project Overview

The jewellery industry experiences significant fluctuations in customer demand across brands, product categories, cities, and festive seasons.

Understanding customer purchase behavior is essential for identifying top-performing brands, optimizing inventory planning, improving marketing campaigns, and helping customers make cost-effective purchasing decisions.

In this project, I analyzed 300+ jewellery purchase transactions across multiple brands and categories to uncover purchasing patterns, customer preferences, festival sales trends, and value-for-money opportunities.

---

## Business Problem

Jewellery retailers often struggle to answer questions such as:

* Which jewellery brand generates the highest revenue?
* Which category drives maximum customer demand?
* How do festivals like Akshaya Tritiya and Diwali impact sales?
* Which brands provide the best value for money?
* What factors influence customer satisfaction?
* How can customers save money without compromising quality?

This project aims to answer these questions using data-driven analysis.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---
## Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Missing Value Handling
* Duplicate Removal
* Exploratory Data Analysis (EDA)
* Data Visualization
* GroupBy Operations
* Lambda Functions
* Ranking
* Multi-condition Filtering
* Business Intelligence
* Customer Analytics
* Retail Analytics
---
## Dataset Information

The dataset contains synthetic jewellery purchase transactions collected across multiple cities, brands, categories, and festival seasons.

### Dataset Features

| Column Name      | Description                     |
| ---------------- | ------------------------------- |
| Transaction_ID   | Unique transaction identifier   |
| Purchase_Date    | Date of purchase                |
| Customer_ID      | Customer identifier             |
| Brand            | Jewellery brand name            |
| Category         | Gold, Diamond, Silver, Platinum |
| Product          | Product purchased               |
| Festival         | Festival season                 |
| City             | Purchase location               |
| Quantity         | Number of items purchased       |
| Original_Price   | Product price before discount   |
| Discount_Percent | Discount applied                |
| Final_Price      | Final purchase price            |
| Rating           | Customer rating                 |
| Payment_Mode     | Payment method                  |
| Sales_Channel    | Online / Offline                |
| Return_Status    | Product return indicator        |
| Making_Charges   | Additional making charges       |

### Dataset Size

* Total Records: 383
* Total Columns: 17

---

# Project Workflow

```text
Data Collection
        ↓
Data Quality Assessment
        ↓
Data Cleaning
        ↓
Missing Value Treatment
        ↓
Duplicate Removal
        ↓
Univariate Analysis
        ↓
Bivariate Analysis
        ↓
GroupBy Analysis
        ↓
Lambda Functions
        ↓
Ranking Analysis
        ↓
Multi-condition Filtering
        ↓
Data Visualization
        ↓
Business Insights
        ↓
Recommendations
```

---

# Data Cleaning Performed

The dataset intentionally contained real-world data quality issues.

### Cleaning Activities

* Removed duplicate transactions
* Standardized brand names
* Standardized category names
* Standardized city names
* Standardized festival names
* Converted date columns into proper datetime format
* Removed currency symbols and commas from price columns
* Converted numeric columns into appropriate data types
* Handled missing values using:

  * Median
  * Mode
  * Business assumptions

---

# Exploratory Data Analysis (EDA)

## Univariate Analysis

Performed analysis on:

* Brand Distribution
* Category Distribution
* Festival Distribution
* City Distribution
* Quantity Distribution
* Price Distribution
* Rating Distribution
* Payment Mode Distribution
* Sales Channel Distribution
* Return Status Distribution

### Objective

To understand customer purchasing patterns and individual feature behavior.

---

## Bivariate Analysis

Performed analysis on:

* Brand vs Revenue
* Brand vs Rating
* Category vs Revenue
* Festival vs Revenue
* City vs Revenue
* Discount vs Rating

### Objective

To identify relationships between business variables and customer behavior.

---

## GroupBy Analysis

Used Pandas GroupBy operations to evaluate:

* Brand Performance
* Category Performance
* Revenue Contribution
* Customer Satisfaction
* Transaction Volume

### Objective

To compare performance across different business dimensions.

---

## Lambda Functions

Applied lambda functions for customer segmentation:

```python
df['Price_Segment'] = df['Final_Price'].apply(
    lambda x: 'Budget'
    if x < 50000
    else 'Premium'
)
```

### Objective

To classify customers based on spending behavior.

---

## Ranking Analysis

Performed ranking based on:

* Revenue
* Customer Ratings

### Objective

To identify top-performing jewellery brands.

---

## Multi-Condition Filtering

Applied:

```python
&
|
```

operators to identify:

* Premium Diamond Purchases
* Highly Rated Products
* Festival Purchases
* High-Value Customers

### Objective

To uncover valuable customer segments.

---

# Data Visualizations

Created visualizations using Matplotlib and Seaborn.

### Visuals Included

* Brand Revenue Bar Chart
* Brand Rating Comparison
* Category Revenue Analysis
* Festival Revenue Analysis
* Correlation Heatmap
* Best Value Brand Analysis

---

# Key Business Insights

### Insight 1

Gold and Diamond categories generated the highest customer demand and revenue.

### Insight 2

Festival seasons such as Akshaya Tritiya and Diwali significantly increased jewellery purchases.

### Insight 3

Customer satisfaction varied across brands, highlighting differences in product quality and service experience.

### Insight 4

Certain brands generated high revenue but did not always achieve the highest customer ratings.

### Insight 5

Best-value brands provided a strong balance between affordability and customer satisfaction.

---

# Business Recommendations

* Increase inventory for Gold and Diamond products.
* Launch targeted campaigns during festival seasons.
* Promote highly-rated jewellery brands.
* Improve service quality for lower-rated brands.
* Use customer feedback to optimize product offerings.
* Focus marketing efforts on value-for-money products.

---

# Project Outcome

This project successfully transformed raw jewellery transaction data into meaningful business insights using Python-based Exploratory Data Analysis.

The analysis identified:

* Top Revenue Generating Brands
* Most Popular Jewellery Categories
* Festival Sales Trends
* Customer Satisfaction Patterns
* Best Value Jewellery Brands

These insights can help businesses improve sales strategies while enabling customers to make smarter purchasing decisions.




Skills: Python • SQL • Power BI • Excel • Machine Learning • Business Analytics

