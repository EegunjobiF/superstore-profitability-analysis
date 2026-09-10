# Superstore Profitability Analysis

A retail profitability analysis using Python and Power BI to identify the factors affecting profit performance, with a particular focus on discounting, customer losses, regional performance, and coupon activity.

## Business Problem

Strong sales do not always translate into strong profitability. This project investigates the financial performance of the Superstore business and identifies where profitability is being reduced or losses are being generated.

The analysis examines transaction data from 2021–2025 across:

* Sales and profit performance
* Time and seasonal trends
* Customer segments and customer types
* Regional profitability
* Discount levels and their impact on profit
* Loss-making transactions
* Marketing channels
* Coupon performance

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Power BI
* SQL

## Key Findings

* Generated **$177.13M in net sales** and **$76.15M in profit**, resulting in an overall **42.99% profit margin**.
* Profitability declines consistently as discount levels increase.
* Transactions receiving **31%+ discounts account for 100% of identified loss-making transactions**.
* The **31%+ discount band** has a profit margin of only **22.96%**, compared with **52.59%** for transactions with no discount.
* **Loyal customers account for 93.49% of identified losses**, making them the largest customer group associated with loss-making transactions.
* The **South, Central, and East regions account for 77.25% of identified losses**.
* Coupon usage alone has little difference in overall profitability, while higher average coupon discounts are moderately associated with lower profit margins (**r = -0.489**).

## Business Recommendation

The business should adopt a profitability-focused discount strategy rather than relying on aggressive promotions to drive sales.

Discounts above 30% should receive particular scrutiny, with promotional offers targeted according to customer value, region, and expected profitability. Coupon campaigns should also focus on controlling discount size rather than simply increasing coupon usage.

The objective is to maximize **profitable sales**, not sales volume alone.

## Project Structure

```text
superstore-profitability-analysis/
├── data/
│   └── README.md
├── notebooks/
│   ├── README.md
│   ├── 01_data_cleaning.ipynb
│   └── 02_profitability_analysis.ipynb
└── README.md
```

## Data

The full cleaned dataset is not included in this repository because of its size. The data preparation and validation process is documented in the data cleaning notebook.

## Analysis Workflow

1. Data cleaning and validation
2. Exploratory profitability analysis
3. Discount and loss analysis
4. Customer and regional analysis
5. Coupon performance analysis
6. Business recommendations

## Project Objective

The objective of this project is to demonstrate how data analysis can be used to move beyond sales reporting and identify the operational factors that influence profitability and business performance.
