# Black Friday Sales Data Analytics

## Project Overview

This project presents an end-to-end retail analytics solution built on over **550,000 Black Friday transaction records**. The objective is to analyze customer purchasing behavior, identify high-value customer segments, evaluate product performance, and generate actionable business insights using **Python** and **Power BI**.

The project combines data preprocessing, exploratory data analysis (EDA), statistical testing, customer segmentation, and interactive dashboard development to support data-driven decision-making in a retail environment.

---

## Business Problem

Retail businesses generate massive amounts of transactional data, but often struggle to transform it into actionable insights.

This project addresses key business questions such as:

* Who are the most valuable customers?
* Which age groups generate the highest revenue?
* How do demographics influence purchasing behavior?
* Which products and categories drive the most sales?
* What factors contribute to customer retention and repeat purchases?

---

## Project Objectives

* Analyze customer purchasing patterns
* Identify high-value and low-value customer segments
* Evaluate demographic impact on spending behavior
* Analyze product category performance
* Study repeat customer behavior
* Build interactive dashboards for business decision-making
* Generate strategic recommendations for revenue growth

---

## Dataset Information

The dataset contains approximately **550,000 retail transactions** collected during a Black Friday sales event.

### Key Features

| Feature            | Description                |
| ------------------ | -------------------------- |
| User_ID            | Customer Identifier        |
| Product_ID         | Product Identifier         |
| Gender             | Customer Gender            |
| Age                | Customer Age Group         |
| Occupation         | Occupation Code            |
| City_Category      | City Classification        |
| Marital_Status     | Married / Single           |
| Product_Category_1 | Primary Product Category   |
| Product_Category_2 | Secondary Product Category |
| Product_Category_3 | Tertiary Product Category  |
| Purchase           | Transaction Amount         |

---

## Tools & Technologies

### Data Analysis

* Python
* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn
* Power BI

### Statistical Analysis

* SciPy
* ANOVA
* Mann-Whitney U Test
* Kruskal-Wallis Test

### Version Control

* Git
* GitHub

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

* Missing value handling
* Feature engineering
* Outlier treatment
* Data standardization

### 2. Exploratory Data Analysis

* Purchase distribution analysis
* Demographic analysis
* Product category analysis
* Customer behavior analysis

### 3. Statistical Validation

* Gender-based spending comparison
* Age group analysis
* City category analysis
* Correlation analysis

### 4. Customer Segmentation

Customers were segmented into:

* High-Value Customers
* Low-Value Customers
* Repeat Customers

### 5. Dashboard Development

Interactive Power BI dashboards were created to support executive-level decision-making.

---

## Dashboard KPIs

| KPI                             | Value         |
| ------------------------------- | ------------- |
| Total Sales                     | ₹5.10 Billion |
| Total Customers                 | 6,000         |
| Average Purchase                | ₹865.02K      |
| Premium Segment Size            | 1,000         |
| High Value Revenue Contribution | 55%           |

---

## Key Insights

### Customer Insights

* High-value customers represent approximately 20% of the customer base.
* High-value customers contribute more than 55% of total revenue.
* Repeat customers are concentrated in the 26–45 age segment.

### Demographic Insights

* Customers aged 26–35 contribute the highest revenue.
* Customers aged 36–45 are the second-largest revenue contributors.
* Metro customers spend significantly more than non-metro customers.
* Male customers show higher average purchase values.

### Product Insights

* A small number of products contribute a majority of total revenue.
* Product Categories 18, 9, and 11 show strong premium customer penetration.
* Product performance follows the Pareto Principle, where a small subset drives most revenue.

---

## Power BI Dashboard Pages

### 1. Sales Performance Overview

* Total Sales
* Customer Count
* Revenue by Age Group
* Revenue by City Category
* Customer Type Analysis
<img width="1165" height="728" alt="image" src="https://github.com/user-attachments/assets/12ded292-e04a-4651-857b-82c0c0d64cf8" />

### 2. Customer Segmentation & Behavior

* High-Value vs Low-Value Customers
* Repeat Customer Analysis
* Revenue Contribution by Segment
<img width="1165" height="733" alt="image" src="https://github.com/user-attachments/assets/43a12b7a-f4f2-4978-bb00-b0a8098d1fee" />

### 3. Product & Category Intelligence

* Top Products by Revenue
* Category Performance
* Premium Product Analysis
<img width="1168" height="729" alt="image" src="https://github.com/user-attachments/assets/ace93dfe-30a2-49dc-9f49-7581c4dc2786" />

### 4. Strategy & Actionable Insights

* Customer Insights
* Product Insights
* Revenue Growth Recommendations
<img width="1210" height="724" alt="image" src="https://github.com/user-attachments/assets/2ab3301b-1250-41bf-ab0d-a9b551873aa9" />

---

## Statistical Analysis Performed

* Mann-Whitney U Test
* ANOVA
* Kruskal-Wallis Test
* Correlation Analysis

These methods were used to validate customer spending patterns and demographic influences on purchasing behavior.

---

## Business Recommendations

### Revenue Growth

* Focus marketing efforts on high-value customers.
* Expand premium product offerings.

### Customer Retention

* Introduce loyalty programs for repeat customers.
* Personalize offers for the 26–45 age group.

### Product Optimization

* Prioritize high-performing categories.
* Reduce investment in low-revenue products.

### Geographic Expansion

* Target metro customers with premium campaigns.
* Develop localized strategies for non-metro regions.

---

## Repository Structure

```text
Black-Friday-Sales-Data-Analytics/
│
├── data/
│   └── black_friday_sales_dataset.csv
│
├── notebooks/
│   └── Black_Friday_Analysis.ipynb
│
├── dashboard/
│   └── Black_Friday_Dashboard.pbix
│
├── reports/
│   ├── Black_Friday_Project_Report.pdf
│   ├── BFS_Python_Charts.pdf
│   └── BFS_PowerBI_Dashboards.pdf
│
├── images/
│   ├── dashboard_overview.png
│   ├── customer_segmentation.png
│   ├── product_intelligence.png
│   └── strategy_insights.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Future Scope

* Customer Lifetime Value (CLV) Analysis
* Customer Churn Prediction
* Recommendation Systems
* Advanced Customer Segmentation using Machine Learning
* Predictive Retail Analytics
* Real-Time Dashboard Integration

---

## Author

**Pawan Funde**

Data Analyst | Python | SQL | Power BI | Business Intelligence

---

## License

This project is intended for educational, analytical, and portfolio purposes.

⭐ If you found this project useful, consider giving it a star.
