# Orders and Details Dashboard

This Power BI dashboard presents a detailed analysis of sales orders and product details, helping users monitor key metrics such as total profit, total sales, order quantities, regional performance, and product category-wise breakdown. It is designed for businesses looking to track order data and extract actionable insights.

---

## Project Purpose

The goal of this project is to visualize transactional order data in a clear and dynamic way using Power BI. The dashboard allows users to filter by time (month), analyze product categories and sub-categories, examine payment modes, and explore state-wise performance.

---

## Key Features and Insights

### 1. Key Metrics (Top Cards)

- Total Profit  
- Total Sales  
- Total Quantity Ordered  

### 2. Filters and Slicers

- Filter by Month  
- Filter by Sub-Category  

### 3. Regional Order Overview

- Tree Map: Count of Order IDs by State  
- Donut Chart: Profit by State and Category  

### 4. Payment Method Analysis

- Bar Chart showing Sum of Amount by Payment Mode (COD, UPI, EMI, Credit Card, Debit Card)  
- Percentage of total payment method contribution  

### 5. Product Performance

- Sub-Category: Amount and Profit analysis by sub-category (Printers, Bookcases, Games, Accessories, etc.)  
- Category: Total amount by main product categories (Electronics, Furniture, Clothing)  
- Pie Chart: Profit percentage by sub-category  

---

## Project Structure

orders-details-dashboard/  
├── data/  
│   └── orders_data.csv (optional if included)  
├── OrdersDetailsDashboard.pbix (Power BI dashboard file)  
├── visuals/  
│   └── dashboard_preview.jpg  
└── README.md (project documentation)

---

## Tools Used

- Power BI Desktop  
- Power Query Editor for data transformation  
- DAX (Data Analysis Expressions)  
- Visuals: Bar Charts, Tree Maps, Pie Charts, Donut Charts, Card KPIs  
- Slicers and interactive filtering  

---

## How to Use

1. Download or clone this repository.  
2. Open the OrdersDetailsDashboard.pbix file in Power BI Desktop.  
3. If using your own dataset, replace or update the data source via Power Query.  
4. Use the slicers (Month and Sub-Category) to interactively filter the visuals.  
5. Explore trends, regional insights, payment behavior, and profit distribution.  

---

## Use Cases

- Business sales analysis  
- Data analytics portfolio project  
- Internal reporting tool for order and product management  
- Power BI dashboard practice for beginners and intermediates  

---

## License

This project is open-source under the MIT License. You are free to use, modify, or share for educational or professional purposes.

---

Developed as a practical Power BI project to visualize orders and product details effectively.
