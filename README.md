# E-commerce Sales Data Analysis

A data analysis project focused on exploring and deriving insights from e-commerce sales data using **MySQL** and **Python (Jupyter Notebook)**.

## Table of Contents
- [Overview](#overview)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Data Description](#data-description)
- [Process](#process)
- [Key Insights](#key-insights)
- [Conclusion](#conclusion)
- [How to Run](#how-to-run)

---

## Overview

This project involved cleaning, querying, and analyzing e-commerce sales data stored in a MySQL database. The analysis was conducted in Jupyter Notebook using Python, and aimed to uncover trends, customer behavior, and sales performance over time.

---

## Objectives

- Understand sales trends across different product categories
- Identify top-performing products and regions
- Analyze customer purchase behavior
- Provide business insights to improve sales and marketing strategies

---

## Technologies Used

- **MySQL** – For data storage and complex queries
- **Python** – For data processing and analysis
- **Jupyter Notebook** – For interactive exploration
- **Pandas** – For data manipulation
- **Matplotlib & Seaborn** – For data visualization

---

## Data Description

The dataset included:
- Order ID, Customer ID
- Product, Category, Quantity
- Price, Revenue, Discount
- Date of Purchase, Region

---

## Process

1. **Data Extraction**
   - Connected to MySQL and imported tables into Jupyter Notebook
2. **Data Cleaning**
   - Handled missing values, standardized formats
3. **Exploratory Data Analysis (EDA)**
   - Analyzed trends by category, region, and time
   - Visualized key metrics
4. **Insights Extraction**
   - Identified top products, peak seasons, and high-revenue regions

---

## Key Insights

- **Customer Reviews Drive Sales**: Product categories with the highest number of reviews should be prioritized for discounts, as customers tend to lean toward products with strong social proof.
  
- **Discount Strategy**: Rather than offering high-percentage discounts a few times, it’s more effective to apply smaller discounts more frequently. This encourages consistent sales while maintaining profitability.

- **Holiday Sales Boost**: Applying high-percentage discounts (like 50%) during major holidays boosts engagement, increases overall sales volume, and limits potential losses by concentrating discounts in short, high-traffic windows.

- **Encouraging Reviews**: Implementing strategies to prompt customers to leave reviews can significantly influence future purchase behavior.

- **Anomalies in Discounts**: Some products were found to have extremely high discount percentages, which may lead to revenue loss. This suggests a need to review the discounting policy to avoid over-discounting.
---

## Conclusion

The analysis revealed valuable insights that can help shape marketing strategies, stock planning, and customer engagement for the e-commerce business. Future improvements could include predictive analytics and dashboard integration.

---

## How to Run

1. Clone this repository  
2. Import the SQL dump into your MySQL server  
3. Open the Jupyter Notebook  
4. Update the database connection credentials  
5. Run the notebook cell by cell

---