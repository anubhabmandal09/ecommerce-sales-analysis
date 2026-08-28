# E-Commerce Sales & Profitability Analysis

A beginner-friendly data analysis project using Python, Pandas, NumPy, and Matplotlib.

## Project goal

I wanted to understand where the business is making money, where it is losing money, and whether there are useful patterns across products, customers, regions, and payment methods.

## Dataset

The project uses `global_ecommerce_sales.csv`.

The dataset contains 2,000 e-commerce orders covering order dates, customers, customer segments, countries, regions, products, quantities, prices, discounts, sales, shipping costs, profit, and payment methods.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Main questions

- How are sales changing over time?
- Which products and categories perform best?
- How common are loss-making orders?
- Which products are responsible for losses?
- Which regions and countries perform best?
- Which customer segment is most valuable?
- How do discounts compare across customer segments?
- How do payment methods compare?

## Key findings

- Total sales were about $484K and total profit was $158,872.32.
- 272 of 2,000 orders were loss-making (13.6%).
- Office Supplies accounted for 224 of the 272 loss-making orders (82.4%).
- Paper Clips Box 500pc had an 80% loss order rate and was net unprofitable overall.
- Europe generated the highest regional sales.
- North America had the highest regional profit margin.
- Consumer customers were the strongest customer segment across sales, profit, AOV, and margin.
- Corporate customers received higher average discounts than Consumer customers.

## Repository structure

```text
ecommerce-sales-analysis/
├── data/
│   └── global_ecommerce_sales.csv
├── notebooks/
│   └── ecommerce_sales_analysis_final.ipynb
├── images/
├── requirements.txt
└── README.md
```

## How to run

Install the dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebook in Jupyter or VS Code and run the cells from top to bottom.
