# Superstore Price Optimization

This project analyzes the **Superstore dataset** to estimate the relationship between product price and demand, and determine the revenue-maximizing price point.

## Project Workflow
1. Data Cleaning & Preparation (Superstore dataset)
2. Exploratory Data Analysis (Revenue distribution, Price vs Demand)
3. Regression Model (Linear relationship between price and units sold)
4. Price Optimization (Overall + Category-level)
5. Export results to Excel

## Key Insights
- Optimal overall price ≈ $519.86 (Max Revenue ≈  $1,916.37 )
- Category-level differences:
  - Furniture → Opt Price: $490.69  | Max Rev: $1,929.40
  - Office Supplies → Opt Price:  $518.31  | Max Rev:  $1,894.95  
  - Technology → Opt Price:  $519.86  | Max Rev:  $1,860.85   

## Tools
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)
- Excel (via openpyxl)
- Jupyter Notebook

## Outputs
- `superstore_price_optimization_overall.xlsx`  
- `superstore_price_optimization_by_category.xlsx`  

## Next Steps
- Try non-linear models (log-log regression, polynomial)
- Extend analysis by region or customer segment
- Deploy as an interactive Streamlit dashboard
