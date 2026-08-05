# AdventureWorks Sales Analysis
This project presents an end to end sales analysis of the AdventureWorks sample dataset using tools such as SQL, Python Pandas & Plotly for visualization. The objective is to identify revenue drivers, evaluate product performance and generate business insights that can support pricing, inventory and product decisions.

## Project Overview
End-to-end sales performance analysis aiming to answer key business questions such as :
How is revenue distributed across products and categories?
How do profit margins vary across different products?
How is sales volume is affected by pricing and other factors?
How is revenue distributed among products?
How can these insights help management? 

## Dataset
|Attribute | Value |
|-------|--------|
|Dataset |AdventureWorks sample database|
|Sales Orders |32 sales orders|
|Products with sales |142 products with recorded sales|

## Tools
|Tools | Purpose |
|-----|------|
|SQL | Data Extraction and querying | 
|SQLite | Database Management |
|Python | Data Analysis Work Flow |
|Pandas | Data manipulation and transformation |
|Plotly | Interactive data visualization |

## Repository Structure
images/
data/
notebook
requirements.txt


## Visualizations

### Revenue Distribution
This visualization shows how revenue is distributed across different product sub-categories and what limited products make up 80% of all revenue generated.

![Revenue Distribution](images/revenue-pareto-chart.png)

### Product Performance
This visualization evaluates the relationship between revenue, sales volume and profit margin across products.

![Product Performance](images//salesvolume-price-profit-rev.png)

### Order Analysis
This visualization provides a distribution trend across different cities in an effort to highlight strong market areas.

![Order Value By Location](images/order-value-by-location.png)

## Key Findings
Bike products are primary contributors to company revenue.
Revenue is concentrated among a relatively small number of premium products.
Profit margin alone does not explain product demand.
High sales volume does not necessarily translate into high revenue.
The dataset is limited in customer and temporal scope; therefore, findings should be interpreted within those constraints.

## Limitations
The dataset contains data for only 2 countries hence geographical analysis was limited to those markets.
All sales order are within 06-2008; therefore analysis of seasonality is limited.
Only 32 sales orders are available therefore finding should interpreted as exploratory.

## Future Work
Expand the analysis with larger dataset.
Analyzing discount impacts on sales performance.
Analyze the relationship of  freight amount and tax amount on sales performance 
Create an interactive Power BI Dashboard to monitor sales and product performance

