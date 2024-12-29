# Awesome Sales Analytics

## Problem Statement
Sales analytics for a chocolate business presents several challenges: tracking sales performance, monitoring costs, analyzing profits, evaluating the performance of salespersons and products, and addressing inefficiencies in low-box shipments. The goal is to create a comprehensive solution to visualize and address these challenges.

---

## Project Overview
This project aims to design a Power BI dashboard that provides actionable insights into the sales data of a chocolate business. By leveraging data visualization and advanced calculations, the dashboard enables stakeholders to make data-driven decisions. The report focuses on:
- Sales performance analysis
- Cost and profit analysis
- Evaluation of individual salesperson and product performance
- Low-box shipment analysis

The dashboard integrates dynamic filtering, time intelligence calculations, and user-friendly features for an enhanced experience.

---

## Key Features and Implementations

### 1. How to Design a Dashboard in Power BI
- **Planning the Layout**: Identified key metrics like sales, profits, and shipment performance to prioritize relevant visualizations.
- **Color Scheme and Formatting**: Applied a balanced and consistent design to make the dashboard visually appealing.
- **Logical Visual Placement**: Ensured proper placement of visuals to facilitate intuitive navigation.
- **Interactive Slicer Panels**: Added slicers for region, product, and time-based filtering to enhance user control.

### 2. Data Modeling with Power BI and Star Schema Development
- **Data Import and Cleaning**: Imported raw data from CSV file and ensured data consistency.
- **Relationship Setup**: Created relationships between fact tables (e.g., shipment data) and dimension tables (e.g., calendar and product data).
- **Star Schema**: Designed a star schema to simplify the reporting structure and improve query efficiency.

![Screenshot 2024-12-28 131513](https://github.com/user-attachments/assets/eed399e3-d86f-40c1-ba18-0eb86eaa897d)


### 3. Identifying Measures and KPIs for Sales Analytics
- **Key Performance Indicators (KPIs)**:
  - Total Sales
  - Total Boxes
  - Total shipment
  - Total Cost
  - Total Profit
  - Profit Percentage
  - Low Box Shipment (LBS) Percentage
  ![image](https://github.com/user-attachments/assets/fa83bb42-c025-4628-a785-a84eedd40f46)

  ![image](https://github.com/user-attachments/assets/d6c4231f-5010-453a-a60f-56bd85c8afa7)

- **Advanced Metrics**: Developed Month-over-Month (MoM) change metrics and profit targets for deeper insights.
![image](https://github.com/user-attachments/assets/be8ea0d6-12b5-4503-8b1c-45e9a28b1737)



### 4. Creating Measures and Setting up a Dedicated Measure Table
- **Centralized Measures**: Used DAX to calculate metrics like Total Boxes, Sales, Costs, and Profits.
- **Measure Table**: Organized all measures into a dedicated table to streamline development and maintenance.
![image](https://github.com/user-attachments/assets/88e167e3-94a4-46ab-b4cf-b9e5e92a5978)

### 5. Time Intelligence Calculations in Power BI - MoM Changes

- **Performance Tracking**: Implemented DAX-based time intelligence to monitor changes in sales, profits, and shipments over time.

- **Trend Analysis**: Enabled stakeholders to track performance trends effectively
![image](https://github.com/user-attachments/assets/1bae1059-f917-47fa-a8a6-11b3523380a6)

### 6. Using the "New" Card Visual and Reference Labels
- **Key Metric Highlighting**: Employed card visuals to emphasize crucial metrics like Profit Percentage and Sales.
- **Reference Labels**: Added labels for targets to enhance readability and context.


### 7. Using Field Parameters to Create a Dynamic Trend Chart
- **Dynamic Charting**: Enabled users to switch between metrics (e.g., Sales, Profit, Cost) dynamically in trend charts.
- **Flexibility**: Improved flexibility for analyzing different aspects of the business.

### 8. "Group" Feature of Power BI to Make Histograms
- **Data Binning**: Grouped shipment data into bins for better visualization.
- **Distribution Analysis**: Created histograms to identify patterns in low-box shipments.

### 9. Working with Zoom Slider
- **Enhanced Focus**: Added zoom sliders to visualizations, enabling users to focus on specific data ranges.
- **Better Interaction**: Improved interactivity and usability.

### 10. Gauge Chart to See Profit and LBS %
- **Profit Visualization**: Designed gauge charts to illustrate Profit Percentage.
- **Performance Monitoring**: Visualized Low Box Shipment Percentage against targets.

### 11. Table Design in Power BI
- **Detailed Metrics**: Created tables displaying salesperson- and product-level performance.
- **Visual Enhancements**: Added icons and sparklines for trend visualization.

### 12. Conditional Formatting for Tables
- **Color Scales**: Highlighted high and low performance using conditional formatting.
- **Trend Indicators**: Used data bars and icons to emphasize key trends and targets.

### 13. Bookmarks
- **Dynamic Navigation**: Set up bookmarks for switching between dashboard views.
- **Seamless Transitions**: Improved user experience with intuitive navigation.
![image](https://github.com/user-attachments/assets/e3b96e2a-05fb-4f51-bc3f-70e85b2bbc18)


### 14. Fixing Problems with Bookmarks - Data/Filter Preservation
- **Filter Retention**: Ensured that selected slicers and filters persisted when navigating between bookmarks.
- **Consistency**: Avoided unexpected resets to maintain a smooth user experience.
![image](https://github.com/user-attachments/assets/abef8e31-6548-4ea1-a665-be4d659b0bde)

![image](https://github.com/user-attachments/assets/664f56d1-5892-4ba6-85bd-8801ab84c222)


### 15. Setting up Tooltips for Country Breakdown
- **Regional Insights**: Configured tooltips to display country-level data breakdown for selected metrics.
- **Contextual Information**: Enhanced user interaction by providing detailed, on-hover insights.
![image](https://github.com/user-attachments/assets/50730cd4-42a2-4d66-bfc4-cc5e4725070c)


### 16. Slicer Panel Setup in Power BI
- **Collapsible Panels**: Designed slicer panels to filter data by region, product, and time range.
- **Improved User Experience**: Made the dashboard more interactive and user-friendly.

---

## Dashboard for Sales Analytics
![image](https://github.com/user-attachments/assets/a3b304e3-dd50-4c1e-b2a7-ac2eedbfaa08)

![image](https://github.com/user-attachments/assets/7c66d1b4-6c0d-4f6b-8da1-7fccfe7dc18a)

## Dashboard Video
https://github.com/user-attachments/assets/6d169afc-b2e7-48f2-a36b-b7914eef1ab3

## Sales Insights
- Sales trended up between Monday, May 1, 2023 and Monday, January 1, 2024 with a rise of $36,045.
- Boxes trended down between Monday, May 1, 2023 and Wednesday, November 1, 2023 with a drop of 27,922.
- Shipment trended up between Thursday, June 1, 2023 and Monday, January 1, 2024 with a rise of 62.
- Profit trended up between Friday, September 1, 2023 and Thursday, February 1, 2024 with a rise of $59,718.
- Cost trended up between Monday, May 1, 2023 and Monday, January 1, 2024 with a rise of $33,686.

## Technologies Used
- **Power BI**: Visualization, data modeling, and reporting.
- **DAX**: Advanced calculations and custom measures.

---

## Acknowledgments
This project is a part of efforts to enhance decision-making through advanced sales analytics. 


