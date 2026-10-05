# Olist E-commerce Analytics

## Project Overview

An end-to-end e-commerce analytics project built using the Brazilian Olist marketplace dataset.

The project focuses on turning raw transactional data into business-ready insights across revenue, customers, RFM segments, delivery operations, products, categories, and sellers.

## Tools & Technologies

- SQL Server / SSMS — data cleaning, validation, joins, aggregation, and analysis
- Power BI — data modeling, DAX measures, interactive dashboards, and visualization
- Excel / Advanced Excel — supporting data preparation and analytical workflow
- Generative AI — analytical assistance for query development, debugging, formula support, and insight interpretation

## Dashboard Structure

### 1. Executive Overview
High-level business performance including:
- Revenue and order KPIs
- Average order value
- Customer and order counts
- Late delivery and low-rating indicators
- Order status distribution
- Payment-method performance
- Monthly revenue trend
- Category revenue performance

### 2. Customer & RFM Analysis
Customer segmentation and behavioral analysis using:
- Customer segments
- RFM scores
- Frequency
- Monetary value
- Customer-level comparisons

### 3. Delivery & Operations Analysis
Operational performance analysis covering:
- Average delivery days
- On-time delivery percentage
- Late-delivery trend
- Delay severity
- Delivery-time buckets
- Order status
- Category and seller delivery performance

### 4. Product & Category Analysis
Product and category performance covering:
- Category orders
- Category revenue
- Revenue per order
- Product-level performance
- Average product price
- Low-rating percentage by category

### 5. Seller Performance & Business Insights
Seller-level analysis covering:
- Total sellers
- Seller revenue
- Seller orders
- Seller revenue per order
- Seller average rating
- Seller late-delivery percentage
- Seller performance summary

## Analytical Workflow

```text
Raw Olist Data
      ↓
Data Quality Checks
      ↓
SQL Analysis & Data Preparation
      ↓
Power BI Data Model + DAX
      ↓
Interactive Dashboard
      ↓
Business Insights & Recommendations
```

## Key Business Questions

- Which categories generate the most revenue and orders?
- Which customer segments have the highest monetary value?
- How efficient is the delivery operation?
- Where are late deliveries concentrated?
- Which product categories have higher low-rating rates?
- Which sellers generate the most revenue and orders?
- Which sellers combine strong revenue with strong customer ratings and delivery performance?

## Repository Contents

```text
Olist-Ecommerce-Analytics/
│
├── Olist_Ecommerce_Analytics.pbix
├── README.md
│
├── sql/
│   └── SQL analysis scripts
│
└── screenshots/
    ├── page-1-executive-overview.png
    ├── page-2-customer-rfm.png
    ├── page-3-delivery-operations.png
    ├── page-4-product-category.png
    └── page-5-seller-business.png
```

## Power BI Report

The `.pbix` file contains the Power BI report, semantic model, DAX calculations, and dashboard visuals.

GitHub does not render `.pbix` reports interactively in the browser, so dashboard screenshots are included for quick portfolio review.

## Notes

This project was developed as a practical data-analytics portfolio project with emphasis on data validation, analytical reasoning, dashboard design, and business interpretation.
