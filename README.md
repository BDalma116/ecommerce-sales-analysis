# E-commerce Sales Analysis

## Overview
This project is a data analysis and dashboarding exercise using an e-commerce dataset. The goal was to practice data cleaning, pivot table analysis, and dashboard design while building a portfolio-ready project.

The analysis focuses on understanding sales performance across time, products, customers, and regions using structured data exploration in Google Sheets.

---

## 📌 Objective
The goal of this project is to analyze e-commerce sales data and identify key trends and patterns in business performance, including:

- Sales trends over time
- Product and category performance
- Customer behavior
- Regional distribution
- Shipping and delivery performance

---

## 📊 Dataset
The dataset contains order-level information, including:
- Order and shipping dates
- Sales
- Product details (category, sub-category, product)
- Customer information
- Geographic data (region, state, city)

---

## 🧹 Data Preparation

### Raw Data
- Original dataset kept unchanged

### Working Data
- Converted dataset into a structured table
- Checked for duplicates (none found)
- Checked for missing values
  - Missing values identified in **Postal Code** column
  - No changes applied as it was not critical for analysis

### Helper Columns Created
- Order Year
- Order Month (numeric)
- Order Month (name format)
- Order Year-Month
- Data quality check column (Postal Code blanks)

---

## 📈 Analysis

### 1. Key Metrics (KPIs)

- **Total Sales:** £2,261,536.78  
- **Total Orders:** 4,922  
- **Total Customers:** 793  
- **Average Order Value (AOV):** £459.48  

---

### 2. Time Analysis

#### Yearly Sales

- 2015: £479,856.21  
- 2016: £459,436.01  
- 2017: £600,192.55  
- 2018: £722,052.02  

#### Monthly Performance

**Top Months:**
- November: £350,161.71  
- December: £321,480.17  
- September: £300,103.41  

**Weakest Months:**
- February: £59,371.12  
- January: £94,291.63  

#### Trend Insight
There is a small dip in 2016, but overall the business is growing. Sales peak toward the end of the year (November–December), with a secondary peak in September, while January and February are consistently the weakest months.

---

### 3. Product Performance

#### Sales by Category

- Technology: £827,455.87 (36.59%)  
- Furniture: £728,658.58 (32.22%)  
- Office Supplies: £705,422.33 (31.19%)  

Sales are relatively evenly distributed across categories, with Technology slightly leading.

---

#### Top Sub-Categories

- Phones: £327,782.45 (14.49%)  
- Chairs: £322,822.73 (14.27%)  
- Storage: £219,343.39 (9.70%)  
- Tables: £202,810.63 (8.97%)  
- Binders: £200,028.79 (8.84%)  

---

#### Insight

There is no extreme dependency on a single category or sub-category.  
Revenue is fairly well distributed, although Phones and Chairs stand out slightly as the top-performing sub-categories.

---

### 4. Customer Analysis

#### Top Customers

The highest-spending customer contributed approximately £25K, followed by others at £19K and £15K.  
This represents roughly around 1% of total sales, indicating that no single customer dominates revenue.

Overall, customer spending appears to be relatively distributed.

---

#### Repeat Behavior

There are many repeat customers in the dataset, indicating that customers tend to place multiple orders rather than making only one-time purchases.

---

### 5. Segment Analysis

- Consumer: £1,148,060.53  
- Corporate: £688,494.07  
- Home Office: £424,982.18  

The Consumer segment generates the highest total sales.

Average order value is relatively similar across segments:
- Consumer: £225.07  
- Corporate: £233.15  
- Home Office: £243.40  

---

#### Insight

While the Consumer segment drives the largest share of revenue, spending behavior across segments is fairly consistent, with no major differences in average order value.

---

### 6. Geographic Analysis

Sales by Region
- West: £710,219.68 (31.40%)
- East: £669,518.73 (29.60%)
- Central: £492,646.91 (21.78%)
- South: £389,151.46 (17.21%)

#### Insight

Sales are relatively well distributed across regions, with the West and East contributing the majority of revenue. Together they account for over 60% of total sales, indicating stronger performance in coastal regions compared to Central and South.

Top States
- California: £446,306.46 (19.73%)
- New York: £306,361.15 (13.55%)
- Texas: £168,572.53 (7.45%)
- Washington: £135,206.85 (5.98%)
- Pennsylvania: £116,276.65 (5.14%)

#### Insight

California and New York are the strongest performing states, together contributing over 30% of total sales. This shows a clear concentration of revenue in highly populated and economically active states.

Top Cities
- New York City: £252,462.55 (11.16%)
- Los Angeles: £173,420.18 (7.67%)
- Seattle: £116,106.32 (5.13%)
- San Francisco: £109,041.12 (4.82%)
- Philadelphia: £108,841.75 (4.81%)

#### Insight

Sales are heavily concentrated in major metropolitan areas. New York City and Los Angeles are the top-performing cities, suggesting that urban centers are key revenue drivers due to higher population density and purchasing power.

---

### 7. Shipping Analysis

Sales by Ship Mode
- Standard Class: £1,340,831.31
- Second Class: £449,914.18
- First Class: £345,572.26
- Same Day: £125,219.04

#### Insight

Standard Class is the dominant shipping method, accounting for the majority of sales. This indicates that customers generally prefer more cost-efficient shipping options over faster delivery.

Orders by Ship Mode
- Standard Class: 2,945
- Second Class: 944
- First Class: 772
- Same Day: 261

#### Insight

The order distribution confirms a strong preference for Standard Class shipping, while expedited shipping options are used significantly less.

Shipping Time Analysis
- Fast (0–2 days): 2,172
- Normal (3–5 days): 5,843
- Slow (6+ days): 1,785
- Average Shipping Time: 4 days

#### Insight

Most orders fall within the “Normal” delivery timeframe, with an average shipping time of 4 days. This suggests a stable and predictable delivery performance across the business.

---

## 📊 Dashboard

The final dashboard includes:

- KPIs (Sales, Orders, AOV, Customers)
- Sales trends over time
- Product performance
- Customer insights
- Regional performance
- Shipping analysis

---

## 🛠 Tools Used
- Google Sheets
- Pivot Tables
- Data cleaning and transformation using formulas
