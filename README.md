# Supply Chain Dashboard

## Introduction
The **Supply Chain Dashboard** is an interactive visualization created using Power BI. It provides insights into key metrics such as sales, order management, customer feedback, and shipping methods. This dashboard utilizes data from a comprehensive dataset representing supply chain activities, making it a powerful tool for optimizing operations and enhancing performance.

---

## Features
### Page 1: Home
- Overview of key metrics:
  - Total sales.
  - Total orders.
  - Customer demographics and geographical distribution.

### Page 2: Sales
- Detailed analysis of sales performance:
  - Breakdown by regions (state and city).
  - Top car models with quantities sold.
  - Year-wise and brand-specific sales trends.

### Page 3: Orders
- Insights into orders:
  - Shipping modes and their usage (e.g., Air, Truck, Standard Class).
  - Quantity trends across time periods (year, quarter, and month).

### Page 4: Customer View
- Analysis of customer feedback:
  - Sales grouped by feedback ratings (e.g., "Good", "Bad").
  - Correlation between customer satisfaction and revenue.

---

## Dataset Overview
### General Information
- **Rows**: 1,000
- **Columns**: 33
- **No Missing Values**

### Key Columns
- **CarMaker, CarModel, CarModelYear**: Car details, including brand and manufacturing year.
- **City, State, Country**: Geographical data for shipping and customer locations.
- **OrderID, OrderDate, ShipDate, ShipMode**: Order and shipping details.
- **Sales, Quantity, Discount**: Transactional data with sales figures and applied discounts.
- **CustomerFeedback**: Ratings provided by customers.

### Example Records
| CarMaker  | CarModel       | Sales      | ShipMode       | CustomerFeedback |
|-----------|----------------|------------|----------------|------------------|
| Dodge     | Ram 2500       | $744,796.41 | Standard Class | Bad              |
| Toyota    | Tundra         | $794,773.17 | Standard Class | Good             |
| GMC       | Savana 1500    | $968,244.90 | Second Class   | Okay             |
| Volkswagen| Cabriolet      | $942,213.82 | First Class    | Very Bad         |

---

## Key Metrics
- **Total Sales**: $853.1M.
- **Total Orders**: 1,512.
- **Top States**: Texas, California, Florida.
- **Top Shipping Modes**: Air, Truck.

---

## Usage Instructions
1. Open the Power BI file in **Power BI Desktop**.
2. Navigate through the pages:
   - **Home** for an overview.
   - **Sales**, **Orders**, and **Customer View** for specific insights.
3. Apply filters on each page to customize your analysis:
   - **Time-based filters**: Year, Month, Quarter.
   - **Category filters**: Shipping mode, Customer feedback, Car brand.

---

## Screenshots

### Page 1: Home
![Page 1 Home](images/page1_home.png)

### Page 2: Sales
![Page 2 Sales](images/page2_sales.png)

### Page 3: Orders
![Page 3 Orders](images/page3_orders.png)

### Page 4: Customer View
![Page 4 Customer View](images/page4_customer_view.png)

---

## Slideshow

```html
<img src="images/page1_home.png" alt="Page 1 Home" width="800">
<img src="images/page2_sales.png" alt="Page 2 Sales" width="800">
<img src="images/page3_orders.png" alt="Page 3 Orders" width="800">
<img src="images/page4_customer_view.png" alt="Page 4 Customer View" width="800">
