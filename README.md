## Power BI & SQL Project [Pizza Sales Report]

#Overview
This project is a Power BI dashboard that provides a comprehensive analysis of pizza sales data. The report visualizes key metrics to help stakeholders understand sales performance, customer preferences, and overall business trends. It aims to deliver actionable insights for decision-making and to optimize sales strategies.

## Project Goals
- Provide a clear view of pizza sales trends over time.
- Identify top-selling pizzas and categories.
- Analyze sales performance by region, store, and day of the week.
- Highlight customer purchase patterns and seasonal trends.

## Requirements

### Software & Tools
- **MS SQL Server**: Used for data preprocessing and querying.
- **Power BI Desktop**: Used for creating the interactive report.
- **Git**: For version control and collaboration (optional).

### Data Requirements
- Transaction data with fields such as `OrderID`, `PizzaType`, `Quantity`, `Price`, and `Date`.
- Customer information including `CustomerID`, `Location`, and `Age`.
- Store and region details for geographic analysis.

### SQL Database Setup
1. Create an MS SQL database to store the raw data.
2. Import data into SQL tables using the provided `.csv` files (if applicable).
3. Use SQL queries to clean, transform, and aggregate data as needed. Sample steps might include:
   - Data normalization (e.g., breaking down complex columns into separate tables).
   - Calculating new metrics such as `TotalSales` and `Profit`.
   - Creating views for `TopSellingPizzas` and `RegionalSales` for easy integration into Power BI.

### Power BI Setup
1. Connect Power BI to the MS SQL database using the appropriate credentials.
2. Import the necessary tables and views into the Power BI environment.

## Output
The final Power BI report includes the following outputs:
![Pizza_Home](https://github.com/user-attachments/assets/2f03c38e-c4c9-454c-b3ad-b9d104f311ae)
![Pizza_Sellers](https://github.com/user-attachments/assets/98300dd1-0818-48d3-810e-5ca8cd498bb9)

## Features
- **Sales Performance Overview**: Key metrics such as Total Sales, Average Order Value, and Profit Margin.
- **Top-Selling Pizzas**: A breakdown of the most popular pizzas based on sales volume.
- **Sales by Category**: Analysis of pizza categories such as Veg, Non-Veg, Premium, and Standard.
- **Geographic Analysis**: Regional performance to identify high and low-performing areas.
- **Time Series Analysis**: Trends by year, month, and day to uncover seasonality and peak times.
- **Customer Insights**: Insights into repeat purchases and customer demographics.

## How to Use
1. Download the `.pbix` file and the SQL scripts from this repository.
2. Set up the MS SQL database and execute the provided SQL scripts to create the necessary tables and views.
3. Open the `.pbix` file using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
4. Update the Power BI data source to connect to your local SQL Server instance.
5. Explore the report using the different pages and interactive visualizations.
6. Use slicers and filters to drill down into specific categories and time periods.

## Project Structure
