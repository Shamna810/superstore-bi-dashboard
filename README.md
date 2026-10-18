# Superstore Sales Dashboard (Tableau)

An interactive 3-tab Tableau dashboard analysing sales, profit and discounting across 9,994 retail orders from the Superstore sample dataset.

**[View the live dashboard on Tableau Public](https://public.tableau.com/app/profile/shamna.fathima/viz/SuperstoreDashboard_1_17922216133490/Overview)**

## Business questions
1. How are sales, profit and margin performing overall?
2. Which products, categories and regions drive or drain profit?
3. Which individual orders need attention?

## Dashboard tabs
| Tab | Purpose |
|---|---|
| Overview | KPIs (sales, profit, margin, average order value), monthly trend, sales by region |
| Deep Dive | Profit by sub-category, discount vs profit, profit by state, top 10 products |
| Loss-Making Orders | Order-level table of orders with negative profit |

## Screenshots
![Overview](screenshots/Overview.png)
![Deep Dive](screenshots/deep-dive.png)
![Loss-Making Orders](screenshots/loss-making-orders.png)

## Key insights
1. Total sales of 2,297,201 produced a profit of 286,397, an overall margin of 12.5%.
2. Copiers and Phones are the most profitable sub-categories (Phones: 44,516), while Tables lose about 17.7K.
3. Texas is the most loss-making state (about -25.7K), while California and New York are among the strongest.
4. The discount-vs-profit scatter plot has a downward trend line: higher average discounts go with lower profit.

## What I built
- Cleaned and connected the data in Tableau
- Calculated fields: Profit Margin, Average Order Value
- Interactive filters, a Top 10 filter, and a geographic profit map
- Dashboard layout with navigation between tabs

## Tools
Tableau Public

## Data source
Superstore sample dataset (Kaggle)

## About
Built as a practice project while moving from bioinformatics into business analytics.
