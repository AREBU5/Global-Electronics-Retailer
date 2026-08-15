# Global Electronics Retailer Analysis

A comprehensive data analysis project for a fictitious global electronics retailer, featuring sales transactions, product information, customer demographics, store locations, and currency exchange rates.

## Project Overview

This project provides end-to-end analysis of a global electronics retail business, leveraging Databricks for data processing and visualization. The analysis covers sales performance, customer behavior, product trends, and geographical insights.

## Dataset Description

The project uses multiple interconnected datasets:

- **Transactions**: Sales transaction records including order details, quantities, and revenue
- **Products**: Product catalog with categories, subcategories, brands, and pricing
- **Customers**: Customer demographics including location, age, gender, and contact information
- **Stores**: Store information with geographical locations and operational details
- **Exchange Rates**: Currency conversion rates for multi-currency analysis

## Project Structure

```
Global-Electronics-Retailer/
├── README.md                          # Project documentation
├── LICENSE                            # License information
├── .gitignore                         # Git ignore rules
└── Global Electronics Analysis.ipynb  # Main analysis notebook
```

### Setup

1. Clone this repository to your Databricks workspace
2. Open the `Global Electronics Analysis.ipynb` notebook
3. Run the cells to perform the analysis

## Analysis Components

The analysis notebook includes:

1. **Data Loading & Exploration**
   - Import datasets from Unity Catalog
   - Data quality checks and profiling
   - Schema validation

2. **Sales Analysis**
   - Revenue trends over time
   - Sales performance by region
   - Product category performance
   - Top performing products

3. **Customer Analysis**
   - Customer segmentation
   - Demographic analysis
   - Purchase behavior patterns
   - Customer lifetime value

4. **Store Performance**
   - Store-level sales comparison
   - Geographical distribution
   - Regional performance metrics

5. **Product Insights**
   - Category and subcategory trends
   - Brand performance
   - Pricing analysis

## 🛠️ Technologies Used

- **Databricks**: Unified analytics platform
- **Apache Spark**: Distributed data processing
- **SQL**: Data querying and transformation

## Key Metrics

The analysis tracks:
- Total Revenue
- Average Order Value
- Customer Count
- Product Performance
- Regional Sales Distribution
- Time-based Trends
