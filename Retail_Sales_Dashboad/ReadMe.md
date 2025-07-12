# Retail Sales Power BI Dashboard

This project is a comprehensive **Retail Sales Dashboard** built using Power BI. It integrates multiple data sources to provide insights on sales performance, customer demographics, product categories, and store operations.

---

## Data Sources and Tables

- **Customer Table:**  
  Contains demographic and mapping information about customers.  
  Key columns:  
  - `Gender`  
  - `Age`  
  - `Kids`  
  - `Marital Status`  
  - `Education`  
  - `Name`  
  - `Store Mapping`

- **Sales Table:**  
  Stores transactional sales data.  
  Key columns:  
  - `Total Amount`  
  - `Quantity`  
  - `Customer ID (cust_id)`  
  - `Date`  
  - `Discount Code`  
  - `Product ID`  
  - `Store ID`

- **Product Table:**  
  Contains product details.  
  Key columns:  
  - `Category`  
  - `Product Name`  
  - `Product ID`  
  - `SKU Size`

- **Store Table:**  
  Details about store attributes and locations.  
  Key columns:  
  - `City`  
  - `Self Checkout`  
  - `Parking`  
  - `Store ID`  
  - `Cash Accepted`

---

## Calculated Measures

- **Total Amount**  
- **Total Orders**  
- **Total Customers**  
- **2017 Total Amount (Jan-May)**  
- **2018 Total Amount (Jan-May)**  
- **Trend and Variance** between 2017 and 2018 (Jan-May)

---

## Dashboard Pages Overview

### 1. Overview Page  
- Title and introductory visuals  
- Buttons (Gender, Year, Parking) for filtering applied globally  
- Slicers for Month  
- Q&A visual for natural language queries  
- Decomposition Tree analyzing Amount by:  
  - Gender  
  - Marital Status  
  - Category  
  - Product  
  - Age  
  - Education  

### 2. KPI Summary Page  
- KPI Cards for:  
  - Total Amount  
  - Total Orders  
  - Total Customers  
  - Total Quantity  
- Same buttons and slicers as Overview  
- Key Influencers visual analyzing Amount by Category and Product Name  

### 3. Sales Analysis Page  
- Map visual showing sales by City  
- Bar chart of Sales Amount by Product Name and Category with drill up/down enabled on Education  
- Buttons and KPI Cards displaying trend, variance, and period-wise sales (2017 & 2018 Jan-May)  

### 4. Customer & Store Insights Page  
- Same slicers and buttons as previous pages  
- Tree map showing Top 5 Stores by Sales Amount  
- Bar chart analyzing Sales Amount by Age Group  

---

## Features

- Interactive slicers and buttons for cross-page filtering (Gender, Year, Parking, Month)  
- Drill down/up capabilities for deep data exploration  
- Use of decomposition tree and key influencers for detailed root cause and impact analysis  
- Geographic sales analysis with map visuals  
- Trend and variance calculations for business performance comparison over time  

---

## How to Use

1. Use the buttons and slicers on each page to filter data dynamically.  
2. Explore sales trends by year and demographic segments.  
3. Use the decomposition tree and key influencers to identify key drivers behind sales performance.  
4. Navigate through product categories and store locations for detailed insights.

---

## Technologies Used

- Power BI Desktop  
- DAX for calculated measures and KPIs  
- Built-in Power BI visuals (Map, Tree Map, Bar Charts, KPI Cards, Decomposition Tree, Key Influencers)  

---

## Future Enhancements

- Add customer segmentation based on purchase behavior  
- Integrate more granular time series analysis (weekly/daily sales)  
- Incorporate forecast models for sales prediction  
- Enable drill-through pages for detailed transaction views  

---

## Author

Gongati Harshitha  
[gongti.harshitha@gmail.com] | [https://www.linkedin.com/in/harshitha-gongati/] | [https://github.com/Harshitha52947]

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
