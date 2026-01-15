# Online Retail Sales Analysis (Python & Pandas)

## Project Overview
This project analyzes online retail transaction data to uncover sales trends, customer behavior, and revenue drivers using Python and Pandas.

## Dataset
- Source: Online Retail Transactions Dataset (UCI / Kaggle)
- Description: Transaction-level data including invoices, products, quantities, prices, customers, and countries.

## Objectives
- Analyze revenue trends over time
- Identify top-performing countries, customers, and products
- Calculate key business metrics such as Average Order Value (AOV)

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analysis Process
1. Cleaned raw transactional data:
   - Handled missing customer IDs
   - Removed invalid quantity and price values
   - Converted date and numeric fields
2. Created derived features:
   - Total price per line item
   - Year and month from invoice dates
3. Performed exploratory data analysis:
   - Monthly revenue trends
   - Revenue by country
   - Customer lifetime value
   - Product revenue analysis

## Key Insights
- Monthly revenue shows clear seasonality with strong performance toward year-end.
- The United Kingdom dominates total revenue, contributing the majority of sales.
- Average Order Value (AOV) is approximately 480.87, indicating high-value transactions.
- Some countries (e.g., Netherlands, EIRE) exhibit higher AOV despite lower total revenue.
- Revenue is highly concentrated among a small group of customers and products.

## Project Structure

```text
online-retail-pandas-analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_exploratory_analysis.ipynb
├── outputs/
│   └── figures/
├── requirements.txt




## How to Run
1. Install dependencies:
2. pip install -r requirements.txt

2. Run notebooks in order:
- `01_data_cleaning.ipynb`
- `02_exploratory_analysis.ipynb`

## Next Steps
- Perform customer cohort or RFM analysis
- Build an interactive Power BI dashboard using the cleaned dataset
