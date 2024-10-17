# Customer-Complaint-Dashboard

# Customer Complaint Dashboard in Tableau - README

## Project Overview

This project focuses on building a **Customer Complaint Dashboard** in Tableau, designed to visualize and analyze customer complaints by product type, request type, and time. Instead of using traditional filters, this dashboard utilizes **parameters** to provide dynamic and interactive insights. The dashboard connects to a CSV data source and includes Key Performance Indicators (KPIs), geographical complaint analysis, and percentage-based visualizations, offering stakeholders a clear view of complaint trends across different categories and time periods.

### Key Features

- **Parameter-Based Filtering:** 
  Parameters are used to filter and interact with the data, allowing users to switch between product types (e.g., credit cards, mortgages) and analyze complaint trends dynamically without using filters. This approach simplifies user interaction and enhances performance.

- **Dynamic KPIs:**
  Key Performance Indicators (KPIs) are designed to visualize important metrics such as total complaints, percentage breakdowns by product, and trend analysis over time. These KPIs provide a high-level summary for stakeholders.

- **Complaint Breakdown by Product and Request Type:** 
  Visualizations include bar charts, dual-axis line charts, and tiled maps that break down complaints by product type (e.g., loans, credit cards) and request type (e.g., dispute, service inquiry).

- **Geographical Analysis:**
  A tiled map chart visualizes complaints based on geographical distribution, allowing users to analyze data by state size and geographical differences.

- **Percentage Calculations:**
  Percentage calculations, such as the proportion of complaints per product, are integrated to give a clearer view of performance trends.

- **Dual-Axis Charts:**
  The dashboard includes dual-axis charts to better compare trends and relationships between different complaint types over time.

## Setup Instructions

### Prerequisites

- **Tableau Desktop** (Version 2020.1 or later)
- **CSV Data Source**: The dashboard is designed to connect to a CSV file containing customer complaint data. Ensure that the file is formatted correctly with necessary columns such as Product Type, Request Type, Date, and Complaint Count.

### Steps to Create the Dashboard

1. **Connecting to CSV Data Source:**
   - In Tableau, connect to your CSV data source that contains the customer complaints.
   - Ensure that all necessary columns (e.g., Product Type, Complaint Date, Request Type, Complaint Count) are available and correctly named.

2. **Setting Up Parameters:**
   - Create parameters to allow users to select different product categories, request types, and time periods for analysis. 
   - Utilize a `CASE` function to map the selected parameter values to corresponding fields in the dataset.
   - Parameters allow users to interact with the dashboard without affecting the underlying data source filters.

3. **Designing KPIs:**
   - Create calculated fields to aggregate total complaints, complaint percentages, and trends.
   - Design KPI cards to display key metrics such as total complaints, complaints by product type, and percentage changes over time.

4. **Visualizing Complaint Data:**
   - **Bar Chart for Complaint Percentages:**
     - Use calculated fields to show the percentage of complaints for each product category. 
     - Design a dual-axis bar chart for better comparison between product groups.
   - **Geographical Tiled Map Chart:**
     - Use a map visualization to display complaints by state size and geographical location.
     - This is crucial for understanding regional differences in complaint volumes.

5. **Dual-Axis Line Chart for Time-Based Trends:**
   - Create a dual-axis line chart to visualize trends in customer complaints over time.
   - Ensure axes are synchronized, and color-coding is used to distinguish between different products.

6. **Dynamic Dashboard Design:**
   - Combine the visualizations, KPIs, and parameter controls into a single dashboard.
   - Arrange the components to ensure easy interpretation and smooth navigation for users.

7. **Final Touches:**
   - Apply consistent formatting, label alignment, and color coding to ensure that the dashboard is visually appealing and easy to use.
   - Test all parameters and visualizations to ensure accurate data representation and functionality.
