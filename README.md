# ZARA Product Performance Analysis

## Project Overview

This project analyzes ZARA product-level data to evaluate product performance, sales volume, estimated revenue, pricing, product positioning, promotion, seasonal status, and category performance.

The objective is to transform raw product data into meaningful business insights and an interactive Power BI dashboard that supports product and performance analysis.

---

## Business Objectives

The analysis focuses on answering key business questions such as:

- Which product categories generate the highest estimated revenue?
- Which products have the highest sales volume?
- Which products contribute the most to estimated revenue?
- Does product positioning relate to sales volume?
- How do promoted products compare with non-promoted products?
- How does seasonal status affect product performance?
- Which product categories represent the main revenue drivers?
- What is the relationship between product price and sales volume?

---

## Tools & Technologies

- Microsoft Excel
- Power Query
- Microsoft Power BI
- DAX / Power BI calculations
- Data Cleaning & Transformation
- Data Analysis & Visualization

---

## Data Preparation

The raw dataset was reviewed and transformed before analysis.

Key data preparation steps included:

- Removing errors and blank rows
- Trimming unnecessary spaces
- Standardizing text values
- Cleaning categorical fields
- Assigning appropriate data types
- Splitting and transforming fields where required
- Removing unnecessary columns
- Creating calculated fields for analysis
- Reviewing potential outliers
- Validating the resulting dataset before loading it into Power BI

---

## Analysis

The analysis covers:

### Product Performance
- Total products
- Sales volume
- Average product price
- Top-performing products
- Estimated revenue by product

### Category Performance
- Estimated revenue by product category
- Sales volume by category
- Category contribution to total estimated revenue

### Product Positioning
- Sales volume by product position
- Estimated revenue by product position

### Promotion Analysis
- Performance of promoted vs. non-promoted products

### Seasonal Analysis
- Performance of seasonal vs. non-seasonal products

---

## Key KPIs

The dashboard tracks the following key indicators:

| KPI | Description |
|---|---|
| Estimated Revenue | Product-level estimated revenue based on sales volume and listed price |
| Total Products | Number of unique products in the dataset |
| Total Sales Volume | Total recorded sales volume |
| Average Product Price | Average listed price of products |
| Product Name Count | Number of unique product names |

---

## Dashboard

The Power BI dashboard provides an interactive view of ZARA product performance.

### Dashboard Preview

![ZARA Product Performance Dashboard](Images/ZARA_Dashboard.png)

---

## Key Insights

Based on the analyzed dataset:

- Jackets are the dominant revenue-driving product category.
- Jackets also generate the highest sales volume among the analyzed categories.
- A small group of products contributes a significant portion of estimated revenue.
- Product placement shows differences in sales volume across store positions.
- Seasonal and non-seasonal products show relatively close revenue contributions.
- Promotional products represent a significant share of the analyzed revenue.
- The dataset is heavily concentrated toward men's products compared with women's products.

> Note: Estimated revenue is calculated from product-level sales volume and listed price and should not be interpreted as ZARA's official financial revenue.

---

## Data Limitations

This analysis is based on product-level data rather than transactional sales data.

Therefore:

- Estimated revenue is derived from available product-level fields.
- The dataset may not represent the full ZARA product catalog.
- The analysis should not be interpreted as official ZARA financial reporting.
- Product-level sales volume may not represent complete real-world transaction data.
- Scraped or collected product data may contain limitations related to time, coverage, or availability.

