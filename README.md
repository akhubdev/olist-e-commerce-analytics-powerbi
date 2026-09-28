# Olist E-Commerce Analytics | Power BI

An end-to-end e-commerce data analytics project built using Microsoft Power BI and the Brazilian E-Commerce Public Dataset by Olist.

## 📌 Project Overview

This project analyzes an e-commerce business across sales, customers, products, payments, geographical distribution, delivery performance, and customer reviews.

The objective was to transform raw multi-table transactional data into an interactive Power BI dashboard and identify meaningful business insights and potential improvement opportunities.

## 🎯 Business Questions

The analysis focuses on questions such as:

- How are sales and order volumes changing over time?
- Which product categories and states generate the most sales?
- How are customers distributed across different locations?
- What is the proportion of new and repeat customers?
- Which payment methods are most commonly used?
- How does installment behavior affect payment value?
- How is delivery performance?
- What does customer review data tell us about satisfaction?
- Which areas could provide opportunities for business improvement?

## 📂 Dataset

The project uses the Brazilian E-Commerce Public Dataset by Olist.

The dataset contains 9 related CSV files:

- Customers
- Geolocation
- Orders
- Order Items
- Order Payments
- Order Reviews
- Products
- Sellers
- Product Category Translation

The tables were analyzed together through a relational Power BI data model.

## 🧹 Data Preparation

Data preparation was performed using Power Query.

Key preparation activities included:

- Reviewing column quality and data types
- Identifying missing values
- Handling missing product categories as "Unknown"
- Reviewing missing delivery-related dates
- Cleaning and transforming geographical data
- Aggregating geolocation records by ZIP-code prefix
- Preparing the product category translation table
- Validating the structure of the individual datasets

## 🔗 Data Modeling

A relational data model was created in Power BI using relationships between:

- Customers and Orders
- Orders and Order Items
- Order Items and Products
- Order Items and Sellers
- Orders and Payments
- Orders and Reviews
- Products and Product Category Translation

A dedicated Date Table was also created for time-based analysis.

## 🧮 DAX & KPI Development

DAX measures were created to calculate key business metrics, including:

- Total Orders
- Total Revenue
- Total Product Sales
- Unique Customers
- Average Order Value
- Average Review Score
- Total Freight Cost
- Repeat Customers
- Repeat Customer %
- On-Time Delivery %
- Average Delivery Days
- Product Sales per Order
- YoY Sales Growth %
- New Customers
- Average Orders per Customer

## 📊 Power BI Dashboard

The final report contains 7 analytical pages:

### 1. Overview
Provides a high-level view of overall business performance, orders, revenue, customers, order status, states, product categories, payment methods, and customer growth.

### 2. Sales Analytics
Analyzes product sales, order trends, revenue by category and state, payment types, year-over-year sales growth, and top-performing categories.

### 3. Customer Analytics
Analyzes customer growth, new vs. repeat customers, customer distribution by state and city, and high-value customers.

### 4. Product Analytics
Analyzes product sales, category performance, product pricing, products sold, and freight costs.

### 5. Payment Analytics
Analyzes payment value, payment methods, installments, average payment value, and payment trends.

### 6. Geolocation Analytics
Analyzes the geographical distribution of customers and sellers across states, cities, and ZIP-code locations.

### 7. Reviews Analytics
Analyzes review scores, customer satisfaction trends, review distribution, product-category ratings, review volume by state, and recent customer feedback.

## 💡 Key Insights

Some key observations from the analysis include:

- The dashboard contains around 99K orders and approximately 96K unique customers.
- Repeat customers represent a relatively small share of the overall unique customer base.
- Customer and sales activity is geographically concentrated in specific states, particularly São Paulo.
- Credit card is the dominant payment method by payment value.
- The overall average review score is around 4.09, while negative reviews still represent a significant volume.
- Delivery performance is strong overall, while a smaller portion of orders experienced delivery delays.
- Product sales are concentrated among specific product categories.

## 💼 Business Recommendations

Based on the analysis, potential areas for further business action include:

- Develop targeted customer retention strategies to encourage repeat purchases.
- Investigate negative reviews by product category, seller, and delivery performance.
- Continue monitoring the customer experience around the dominant payment method.
- Analyze inventory and seller coverage in high-demand geographical regions.
- Investigate the relationship between delivery delays and customer satisfaction.

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Kaggle Dataset
