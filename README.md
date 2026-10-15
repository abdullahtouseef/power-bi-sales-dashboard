# Power BI Sales Performance Dashboard

## Project Overview
This project presents an interactive sales dashboard built with Microsoft Power BI using 1,000 sales records. The data was cleaned and transformed using Azure Databricks, Delta Lake, and dbt before being imported into Power BI.

## Dashboard Preview

![Power BI Sales Dashboard](sales-dashboard.png)

## Key Performance Indicators
- **Total Revenue:** Total sales revenue generated.
- **Total Orders:** Number of orders in the dataset.
- **Total Quantity Sold:** Total units sold.

## Dashboard Visualizations
- **Sales by City:** Compares sales across Lahore, Karachi, Islamabad, Multan, and Faisalabad.
- **Sales by Product:** Compares revenue across different products.
- **Sales Trend Over Time:** Shows how sales change across order dates.
- **City Filter:** Allows users to explore sales for a selected city.

## Tools and Technologies
- Microsoft Power BI Desktop
- Azure Databricks
- Delta Lake
- dbt Core
- SQL
- Git and GitHub

## Data Source
The dashboard uses a cleaned sales dataset exported from the `my_first_dbt_model` dbt model in Azure Databricks.

The dataset includes:
- `order_id`
- `city`
- `product`
- `price`
- `quantity`
- `total_sales`
- `order_date`

## Project Workflow
1. Generate and store raw sales records in a Delta table.
2. Clean and transform the data using dbt.
3. Calculate total sales using price multiplied by quantity.
4. Export the cleaned data to CSV.
5. Import the CSV into Power BI Desktop.
6. Create KPI cards, charts, and an interactive city filter.

## Files
- `Sales_Performance_Dashboard.pbix` — Power BI dashboard file.
- `sales-dashboard.png` — Dashboard screenshot.

## Learning Outcomes
- Building interactive Power BI dashboards.
- Creating KPI cards and sales visualizations.
- Using slicers to filter data.
- Connecting data engineering outputs to business reporting.

**Author:** Abdullah Tauseef
