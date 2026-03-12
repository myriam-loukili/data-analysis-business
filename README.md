# From Theoretical Profitability to Real Business Data
### Data Analysis of a Small Dessert Business

## Project Overview

This project analyzes the profitability of a small homemade dessert business operated over a one-month test period.

The objective is to understand how data analysis can support the transition from theoretical profitability estimates to real operational profitability when production capacity is limited.

The project combines two complementary approaches:

- a **predictive profitability model built with Python**, developed before launching the activity  
- an **analysis of real operational data using SQL**, once the activity started

The purpose is to compare theoretical assumptions with actual operational results and identify the gap between calculated indicators and real production conditions.

---

## Predictive Profitability Analysis (Python)

Before launching the activity, Python was used to model the profitability of different products.

The analysis relies on several key variables:

- selling price  
- ingredient costs  
- preparation time  

From these inputs, the following indicators were calculated:

- gross margin  
- margin rate  
- margin per minute  
- margin per hour  
- production simulations under time constraints

This analysis helps identify which products are theoretically the most profitable when production time is limited.

---

## Operational Data Analysis (SQL)

Once the activity started, real operational data was structured in a SQLite database.

The database includes several tables:

- products  
- sales  
- supplies  

SQL queries were used to analyze:

- revenue evolution over time  
- each product's contribution to total revenue  
- real margin levels by product  
- ingredient and supply expenses  

This structure enables a more rigorous monitoring of the activity and provides a clearer view of real operational performance.

---

## Key Insights

The analysis highlights several important findings:

- hourly margin is more relevant than unit margin when production capacity is limited  
- operational constraints can significantly impact product profitability  
- some products may be operationally more efficient despite lower theoretical margins  
- the gap between theoretical models and real-world results provides valuable insights for improving decision-making  
- business data must always be interpreted within its operational context

---

## Tools

- Python  
- Pandas  
- Matplotlib  
- SQL  
- SQLite  
- Jupyter Notebook
