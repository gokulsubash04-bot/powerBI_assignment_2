# Power BI Data Analysis Dashboard

## Project Overview

This project uses Microsoft Power BI Desktop to analyse order placements, daily orders, employee layoffs, and key business statistics using Excel datasets.

## Datasets Used

- **Amazingcart.xlsx**: Country-wise order placement analysis.
- **Customer_Data.xlsx**: Customer orders, product quantities, prices, and order dates.
- **Employee_Layoffs.xlsx**: Employee layoffs by location.

## Report Pages

### 1. Orders by Country

A clustered column chart showing the countries with the highest number of order placements.

- **Chart Type:** Clustered Column Chart
- **X-axis:** Country
- **Y-axis:** Count of Order ID
- **Purpose:** Compare order placements across countries.

### 2. Daily Orders

A line chart showing the number of orders received over time.

- **Chart Type:** Line Chart
- **X-axis:** Date
- **Y-axis:** Count of Order ID
- **Purpose:** Identify changes in daily order volume.

### 3. Employee Layoffs

A pie chart showing the distribution of employee layoffs by location.

- **Chart Type:** Pie Chart
- **Legend:** Location
- **Values:** Sum of Total_Laid_Off
- **Purpose:** Compare the number of layoffs across locations.

### 4. DAX Measures

A separate report page displaying important business metrics using Card visuals.

The measures include:

- Total Quantity
- Total Sales
- Total Rows
- Valid Records
- Total Missing Values
- Minimum Quantity
- Maximum Quantity

## Calculated Column

A calculated column was created in the Customer Data table to replicate the existing Total Price column.

Example DAX formula:

```dax
Calculated Total Price Copy =
'Customer Data'[Total Price]
