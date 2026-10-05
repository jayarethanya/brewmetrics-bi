\# BrewMetrics Coffee Co. – Sales Performance Dashboard



A version-controlled Power BI analytics solution for BrewMetrics Coffee Co. to analyze sales performance, product trends, seasonal patterns, and city-level performance.



\## Project Overview



BrewMetrics Coffee Co. operates Flagship, Kiosk, and Drive-Thru stores across four cities. This project develops a Power BI dashboard using a version-controlled workflow with GitHub.



The dashboard helps management understand:

\- Overall sales performance

\- City-level sales performance

\- Monthly sales trends

\- Cold Brew seasonal sales patterns

\- Product category performance

\- Store-format performance through drill-down



\## Data Model



The original sales data was transformed into a star schema.



\### Fact Table

\- Fact\_Sales



\### Dimension Tables

\- Dim\_Date

\- Dim\_City

\- Dim\_Product



The dimension tables are connected to Fact\_Sales using one-to-many relationships.



\## Dashboard



The dashboard contains:

\- Sales by City

\- Cold Brew Sales – Seasonal Trend

\- Monthly Sales Trend

\- Sales by Product Category

\- City slicer

\- City → Store Format drill-down



\## Key Insights



1\. Bengaluru has the highest overall sales among the four cities in the dataset.



2\. Cold Brew shows stronger sales during April and May, indicating a seasonal demand pattern.



3\. City-level analysis and store-format drill-down help identify differences in sales performance across locations and formats.



\## DAX Measures



The project includes measures for:

\- Total Sales

\- Month-over-Month Growth %

\- Running Total Sales

\- City Sales Rank

\- Cold Brew Sales



\## Tools Used



\- Power BI Desktop

\- Power Query

\- DAX

\- GitHub

\- GitHub Desktop

\- GitHub Copilot



\## Version Control



The Power BI project and documentation are maintained in GitHub using separate commits for major development steps such as schema creation, DAX measures, dashboard development, and documentation.

