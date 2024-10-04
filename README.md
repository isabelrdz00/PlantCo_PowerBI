# PowerBI ✏️
### PlantCo Performance Report 🪴
#### Project Overview
This project involves creating a dynamic and interactive PlantCo Performance Report using Power BI. The report provides valuable insights into the company's sales, gross profit, and account profitability. It is designed to highlight key metrics, trends, and performance comparisons year-over-year, enabling data-driven decision-making for stakeholders.
The report includes various features such as slicers, dynamic titles, and advanced DAX calculations to facilitate an intuitive and comprehensive user experience. The use of switch measures and conditional formatting further enhances the visual appeal and analytical capabilities of the report.
### Dataset
The project is based on a fictional plant company dataset comprising three key tables:
- **Sales Fact Table:** Contains order details like Product ID, Sales Quantity, Price, Cost of Goods, Invoice Date, and Account ID.
  
- **Account Table:** Provides details on customer accounts including Account Master ID, Country Code, Latitude, and Longitude.
  
- **Product Hierarchy Table:** Includes the Product Family, Product Group, Product Name, Product Size, and Product Type details, allowing for drill-down capabilities.

### Key Features and Techniques
**Data Modeling:**
- Imported data from Excel using Power Query and performed data cleansing operations such as removing duplicates and adjusting data types.
- Created additional calculated columns for performance tracking and analysis, including a date dimension table for time-based calculations.

**Advanced DAX Measures:**
- Developed key metrics such as Year-to-Date Sales, Gross Profit, Prior Year-to-Date, and Year-over-Year Change.
- Utilized SWITCH and SELECTEDVALUE functions to create dynamic measures that respond to user slicer selections, enabling easy comparison across different metrics like sales, quantity, and gross profit.

**Visualizations:**
- _**Waterfall Chart:**_ Illustrates the change in sales or profit over time, highlighting key contributors to growth or decline.
  
- _**Line and Stacked Column Chart**:_ Displays sales trends across time, allowing for drill-down by quarter or month to identify peak performance periods
  
- _**Scatter Plot**:_ Segments accounts based on profitability and sales volume, helping identify underperforming or highly profitable segments
  
- **_Dynamic Titles and Conditional Formatting_:** Implemented dynamic report and visual titles that update based on the selected values.Applied conditional formatting to visually differentiate performance metrics and highlight variances.

### Project Insights
**Sales Trends:**
- The report shows significant variations in sales across different regions and product categories. Sales trends can be analyzed month-over-month or year-over-year to identify seasonal patterns or emerging trends.
- February 2023 was a standout month, exceeding prior year sales, making it worthwhile to investigate what strategies were effective during this period.

**Profitability Analysis:**
- The scatter plot visualization allows easy segmentation of accounts based on profitability (gross profit percentage) and sales volume, revealing which accounts are the most profitable and where there might be opportunities for growth.

**Country-Level Performance:**
- The bottom 10 countries for sales performance were identified, indicating regions that might require strategic adjustments or targeted campaigns to improve performance.

### Technical Skills Demonstrated
- **Data Preparation:** Imported and transformed data using Power Query.

- **Data Modeling:** Created relationships, calculated columns, and virtual tables using DAX.
  <img width="556" alt="relationships PowerBI" src="https://github.com/user-attachments/assets/dad654fd-1e82-4219-88ea-04fe793bf0a6">


- **Visual Design:** Designed an interactive and user-friendly report layout using Power BI’s built-in visualizations and formatting options.

- **Advanced Analysis:** Developed measures to compare current and prior year performance, and created profitability analysis visualizations.
<img width="632" alt="PowerBI Dashboard" src="https://github.com/user-attachments/assets/3d179892-da05-40ba-8511-c6da68d8460c">


