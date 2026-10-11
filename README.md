# Olist E-Commerce Sales Analysis

End-to-end data analysis project using Python + MySQL + Pandas + Matplotlib
on the Olist Brazilian e-commerce dataset (100K+ orders).

## Overview

This project answers 5 business questions about a Brazilian e-commerce platform:

1. How did revenue evolve over time?
2. Which states generate the most revenue?
3. Which product categories perform best?
4. How long does delivery take?
5. What payment methods do customers prefer?

## Data

- Source: [Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Imported into MySQL (`olist` database)
- 100K+ orders, 9 tables

## Tech Stack

- **Python**: PyMySQL, Pandas, Matplotlib
- **MySQL 8.0**: data storage and aggregation

## Project Structure

    .
    ├── analysis.ipynb       # Main analysis notebook
    ├── requirements.txt     # Dependencies
    ├── charts/              # Generated visualizations
    └── README.md

## Key Findings

- Total revenue: R$ XX,XXX,XXX
- Top state: SP (São Paulo), contributing ~37% of revenue
- Top category: beleza_saude (health & beauty)
- Most used payment method: credit_card (~74%)
- Peak sales month: November 2017 (Black Friday)

## Sample Visualizations

![Monthly Revenue](charts/monthly_trend.png)

![Top 10 States](charts/state_revenue.png)

![Category Ranking](charts/category_revenue.png)

![Payment Methods](charts/payment_distribution.png)

## How to Run

1. Install dependencies:
