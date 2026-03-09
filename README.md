# Data Analysis of a Small Dessert Business

This project analyses the economic performance of a small-scale dessert business launched as a one-month test activity.

The objective was to evaluate the real profitability of the business and understand how production constraints influence economic performance.

## Objectives

- Identify the most profitable products
- Measure profitability per product
- Evaluate production capacity
- Compare theoretical profitability with real operational results

## Methodology

Before launching the activity, a theoretical model was built using Python in order to estimate the profitability of each product.

The following variables were collected for each product:

- Cost of raw materials
- Selling price
- Preparation time

From these data, several indicators were calculated:

- Gross margin
- Margin per minute
- Margin per hour
- Production simulation over a fixed time period

These indicators allowed the prioritization of products based on hourly profitability rather than unit margin.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Key Insights

The project highlights the gap between theoretical profitability and real operational constraints.

Several factors affected the results:

- Production capacity limitations
- Preparation and cleaning time
- Demand fluctuations
- Product positioning and quality choices

The analysis showed that operational factors and product positioning can significantly influence real profitability.

## Project Files

- `python-business-analysis.ipynb` : Python notebook containing the data analysis
- `project-report.pdf` : detailed report explaining the project and results

## Future Work

The next step is to structure operational data using a relational database in order to monitor:

- sales by product
- stock levels
- product rotations
- supply needs

This will be implemented using SQL to improve decision-making and business monitoring.
