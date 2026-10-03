# REAL-WORLD DATA PROJECT
## Retail Sales Analysis

### 1. Objective
The objective of this project is to apply data-science skills to a domain-specific retail dataset and produce practical business insights using end-to-end data analysis.

### 2. Dataset
No dataset was supplied for the Thiranex task, so a realistic synthetic retail dataset containing **800 original orders** was created.

The dataset contains:
- Order ID
- Order Date
- Product Category
- Product
- Quantity
- Unit Price
- Discount
- City
- Sales Channel
- Payment Method
- Customer Age
- Customer Rating
- Revenue

### 3. Data Cleaning
The following steps were performed:
1. Removed duplicate records.
2. Converted dates to datetime format.
3. Filled missing city values using the mode.
4. Filled missing ratings using the median.
5. Detected extreme Quantity and Unit Price values using the IQR method.
6. Capped extreme values at reasonable IQR boundaries.
7. Recalculated revenue after cleaning.

### 4. Key Business KPIs
- **Total Revenue:** ₹6,322,563.14
- **Average Order Value:** ₹7,903.20
- **Average Customer Rating:** 3.99/5
- **Online Order Share:** 60.75%

### 5. Major Findings
**Top Category:** Electronics

The category with the highest total revenue is Electronics.

**Top City:** Chennai

The city with the highest total revenue is Chennai.

**Top Product:** Wireless Earbuds

The product with the highest revenue contribution is Wireless Earbuds.

**Sales Channel:** Online

The Online channel generated the highest revenue in this generated dataset.

### 6. Analysis Performed
- Category-wise revenue analysis
- City-wise revenue analysis
- Monthly revenue trend
- Sales-channel comparison
- Payment-method distribution
- Product performance
- Quantity vs revenue relationship
- Customer age and rating analysis

### 7. Visualizations
The project contains:
1. Revenue by Product Category
2. Revenue by City
3. Monthly Revenue Trend
4. Revenue by Sales Channel
5. Payment Method Distribution
6. Quantity vs Revenue
7. Customer Age vs Rating

### 8. Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

### 9. Business Insights
1. Category analysis helps identify which product groups contribute more revenue.
2. City analysis helps identify stronger geographic markets.
3. Monthly analysis helps identify changes in revenue over time.
4. Sales-channel analysis compares online and store performance.
5. Payment-method analysis helps understand customer payment preferences.
6. Product-level analysis can support inventory and marketing decisions.
7. Quantity and revenue analysis helps understand order-size behavior.

### 10. Conclusion
This project demonstrates how data science can be applied to a real-world retail business problem. The complete workflow moves from raw data and cleaning to KPI calculation, visualization and actionable business interpretation.

The project can be extended by adding customer segmentation, sales forecasting, recommendation systems, or machine-learning prediction.
