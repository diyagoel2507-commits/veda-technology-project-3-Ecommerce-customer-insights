# E-Commerce Customer Segmentation | RFM Analysis

### Customer Analytics • K-Means Clustering • Power BI Dashboard

## Project Overview

This project analyzes e-commerce transaction data to understand customer purchasing behavior, identify valuable customer segments, and support data-driven marketing decisions.

The project uses Recency, Frequency, and Monetary (RFM) analysis, K-Means clustering, and an interactive Microsoft Power BI dashboard to turn transactional data into actionable business insights.

## Project Objectives

- Clean and prepare e-commerce transaction data.
- Calculate customer-level RFM metrics.
- Assign RFM scores and identify meaningful customer segments.
- Explore customer groups using K-Means clustering.
- Visualize customer distribution and revenue patterns in Power BI.
- Recommend targeted marketing strategies for customer retention and re-engagement.

## Dataset

**Dataset:** Online Retail

**Source:** UCI Machine Learning Repository  
https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains transactions from a UK-based online retail business.

| Dataset Information | Details |
|---|---|
| Original records | 541,909 |
| Original columns | 8 |
| Cleaned transaction records | 397,884 |
| Unique customers | 4,338 |
| Calculated revenue | Quantity × UnitPrice |

The cleaned dataset was prepared for customer-level analysis by handling missing customer information and excluding unsuitable transaction records.

## Tools and Technologies

- **Python:** Data processing and analysis
- **Pandas:** Data cleaning and manipulation
- **Scikit-learn:** K-Means clustering
- **Microsoft Power BI:** Interactive dashboard and visualization
- **Microsoft Excel:** Supporting workbook and data review
- **GitHub:** Project documentation and version control

## Methodology

### 1. Data Cleaning and Preparation

- Loaded the original transaction dataset.
- Examined missing values.
- Prepared customer identifiers and transaction dates.
- Removed records unsuitable for customer-level analysis.
- Created a Revenue field using Quantity × UnitPrice.

### 2. RFM Analysis

RFM analysis evaluates customers using three metrics:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer purchased.
- **Monetary:** How much a customer spent.

These metrics were used to score customers and support meaningful segmentation.

### 3. Customer Segmentation

The analysis identifies customer groups such as:

- Champions
- Loyal Customers
- At Risk
- Lost Customers
- Recent Customers
- Potential / Others

These groups help explain differences in purchasing behavior and provide a foundation for targeted marketing recommendations.

### 4. K-Means Clustering

K-Means clustering was used to explore patterns among customers. Cluster distribution is displayed in the Power BI dashboard.

Cluster numbers represent model-generated groups. Their business interpretation should be based on the characteristics of customers within each cluster.

### 5. Power BI Dashboard

The interactive dashboard includes:

- Total Customers KPI
- Total Revenue KPI
- Average Customer Spend KPI
- Customer Segment Distribution
- Revenue by Customer Segment
- Customer Distribution by K-Means Cluster
- Customer Segment Filter
- Key Business Insights and marketing recommendations

## Key Findings

- The cleaned dataset contains **4,338 unique customers**.
- Total transaction revenue is approximately **8.91 million** in the dataset's currency.
- The Champions segment has the highest revenue in the current dashboard.
- The Lost Customers segment represents a potential opportunity for customer reactivation.
- RFM segmentation helps distinguish high-value, loyal, at-risk, and inactive customers.

## Business Recommendations

| Customer Segment | Recommended Strategy |
|---|---|
| Champions | Offer loyalty rewards and exclusive benefits. |
| Loyal Customers | Encourage repeat purchases through relevant offers. |
| At Risk | Test personalized win-back campaigns. |
| Lost Customers | Test reactivation offers and monitor responses. |
| Recent Customers | Encourage a second purchase and continued engagement. |
| Potential / Others | Use relevant promotions to build customer loyalty. |

These recommendations are proposed actions. Their effectiveness should be evaluated through actual campaign results.

## Repository Structure

```text
veda-technology-project-3-ecommerce-customer-segmentation-rfm/
├── README.md
├── Ecommerce_Customer_Segmentation.xlsx
├── Ecommerce_Customer_Segmentation_Dashboard.pbix
├── Ecommerce_Customer_Segmentation_RFM.ipynb
└── Ecommerce-customer-segmentation.png
```

## How to Explore the Project

1. Review the Jupyter Notebook to understand the analysis workflow.
2. Open the Excel workbook to review the supporting work.
3. Open the Power BI report in Power BI Desktop.
4. Use the customer segment filter to explore customer groups.
5. Review the charts and recommendations to understand the business implications.

## Limitations

- Historical purchases may not predict future customer behavior.
- K-Means results depend on feature selection, scaling, and model configuration.
- Marketing recommendations require validation through campaign performance data.

## Author

**Diya Goel**

## Project Purpose

Developed as a data analytics portfolio project to practice data cleaning, RFM analysis, customer segmentation, clustering, dashboard design, and business storytelling.
