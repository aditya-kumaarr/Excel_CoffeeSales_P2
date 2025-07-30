# Coffee Sales Dashboard (Excel Interactive Dashboard)

## Project Objective
The objective of this Coffee Sales Dashboard project is to analyze coffee sales data from multiple sources and present comprehensive insights using Microsoft Excel. This includes examining sales trends over time, customer behavior patterns, product performance by roast type and size, geographical distribution of sales, and loyalty program effectiveness. The dashboard provides a unified visual summary to support strategic business decisions for coffee retail operations.

## Dataset used
- <a href="https://github.com/aditya-kumaarr/Excel_CoffeeSales_P2/blob/main/assets/raw_coffeeOrdersData.xlsx">Dataset</a>

## Questions (KPIs)
- Total Sales Trends Over Time:
Analyze monthly and yearly sales performance to identify peak seasons and growth patterns.
- Top 5 Customer Analysis:
Identify highest-value customers and their purchasing behavior.
- Sales by Country:
Understand geographical distribution of sales and market penetration.
- Product Performance by Roast Type:
Compare sales across Light, Medium, and Dark roast preferences.
- Size Preference Analysis:
Evaluate customer preferences for different coffee package sizes.
- Loyalty Card Impact:
Assess the effectiveness of the loyalty program on customer purchases.

- Dashboard Interaction <a href="https://github.com/aditya-kumaarr/Excel_CoffeeSales_P2/blob/main/coffeeOrdersData.xlsx">View Dashboard</a>

## Process
- Created a backup copy of the raw file to ensure data recovery options in case of issues.
- Integrated multiple data sources using XLOOKUP and INDEX.MATCH functions to consolidate information from separate sheets.
- Used XLOOKUP to retrieve customer details (Customer Name, Email, and Country) from the Customers table.
- Applied INDEX.MATCH as dynamic arrays to extract product information (Coffee Type, Roast Type, Size, Unit Price, and Sales) from the Products table.
- Calculated sales amount by creating a new column multiplying Quantity and Unit Price.
- Enhanced data readability by adding Coffee Type Name column using IF functions to convert codes to full descriptive names.
- Improved roast type clarity by creating Roast Type Name column using IF functions to convert abbreviations to full names.
- Formatted size column by adding "KG" suffix for better understanding.
- Applied currency formatting to Price and Sales columns for professional presentation.
- Added Loyalty Card column using XLOOKUP to link customer loyalty status.
- Converted data range to Excel table for better data management and automatic range expansion.
- Created pivot tables for dynamic data analysis and chart generation.
- Built interactive visualizations including line graphs for sales trends, bar charts for top customers and country analysis.
- Implemented dynamic filtering using timeline (Order Date) and slicers (Roast Type, Loyalty Card, Size).
- Established chart connections to ensure all visualizations respond to slicer and timeline selections.
- Designed unified dashboard by copying all charts to a single sheet with professional formatting and header.

## Dashboard Features
- Dynamic Time-Based Analysis:
Interactive timeline allowing users to filter data by specific date ranges.
- Multi-Dimensional Filtering:
Three synchronized slicers for Roast Type, Loyalty Card status, and Size preferences.
- Customer Intelligence:
Top 5 customer rankings with visual representation of purchase values.
- Geographic Insights:
Country-wise sales distribution for market analysis.
- Trend Visualization:
Clear line chart showing sales performance over time periods.
- Professional Layout:
Clean, color-coded design optimized for stakeholder presentations.

## Dashboard

![Screenshot (495)](https://github.com/aditya-kumaarr/Excel_CoffeeSales_P2/blob/main/assets/Coffee%20Sales%20Dashboard%20Image.png)

## Project Insight
- Women customers contribute 64% of total sales, indicating higher purchase behavior compared to men.
- March is the peak sales month, suggesting seasonal or promotional opportunities.
- Top-performing states include Maharashtra, Karnataka, and Uttar Pradesh, which collectively drive significant revenue.
- Most orders are placed by adults, but teenagers and seniors still represent valuable market segments.
- Delivery success rate is high, but there is a notable percentage of returns and cancellations that need to be addressed.
- Sales Performance:
The dashboard reveals seasonal trends and peak performance periods, enabling better inventory planning and promotional timing.
- Customer Concentration:
Top 5 customers represent a significant portion of total sales, indicating the importance of customer retention strategies for high-value clients.
- Geographic Distribution:
Sales by country analysis shows market penetration levels and identifies opportunities for expansion in underperforming regions.
- Product Preferences:
Roast type analysis provides insights into customer taste preferences, informing product development and marketing strategies.
- Loyalty Program Effectiveness:
The loyalty card slicer enables analysis of program impact on customer purchase behavior and retention.
- Size Preferences:
Package size analysis helps optimize inventory management and pricing strategies for different market segments.

## Final Conclusion:
- This Coffee Sales Dashboard demonstrates the power of Excel's advanced data manipulation and visualization capabilities in transforming raw, multi-source data into actionable business insights. By utilizing XLOOKUP, INDEX.MATCH, and dynamic array formulas, the project successfully integrates customer, product, and sales data into a cohesive analytical framework.
- The interactive dashboard empowers stakeholders to explore data from multiple dimensions - temporal, geographical, and product-based—through synchronized slicers and timeline controls. The top customer analysis reveals concentration risk and retention opportunities, while country-wise sales distribution identifies market expansion potential. Product performance metrics by roast type and size provide crucial insights for inventory optimization and targeted marketing campaigns.
- The systematic approach from data integration through final dashboard presentation showcases proficiency in Excel's advanced features while delivering a professional, stakeholder-ready analytical tool. This project exemplifies how traditional spreadsheet tools can be leveraged to create sophisticated business intelligence solutions that support data-driven decision making in retail coffee operations.

## If you'd like to connect or collaborate on data projects, feel free to reach out on: 
- **LinkedIn**: www.linkedin.com/in/aditya-kumar-2852c
- **Email**: adityaakumaarr@gmail.com

