#  Supply Chain Visibility & Optimization Dashboard

##  Project Overview

This project focuses on analyzing supply chain performance using Power BI. The dashboard provides insights into inventory management, delivery performance, and operational efficiency to help businesses make data-driven decisions.

---

 Objectives

- Monitor inventory performance.
- Identify fast-moving and slow-moving products.
- Evaluate delivery performance.
- Improve inventory planning and supply chain efficiency.
- Provide actionable business recommendations.

---

 Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Modeling
- Excel / CSV Dataset

---

 Dashboard Features

Inventory Analytics
- Total Inventory Value
- Total Inventory Quantity
- Inventory Turnover
- Dead Stock Analysis
- Fast-Moving Inventory
- Slow-Moving Inventory
- Stock Status Distribution

Delivery Performance
- Average Delivery Days
- On-Time Delivery Rate
- Delayed Deliveries
- Monthly Delivery Trends
- Regional Delivery Performance

---

 Inventory Turnover Calculation Approach

Formula:
Inventory Turnover = Cost of Goods Sold (COGS) ÷ Average Inventory Value

Dashboard Approach:
- Calculate the total inventory value.
- Determine the average inventory value during the analysis period.
- Compare inventory movement against available stock.
- Higher turnover indicates efficient inventory utilization.
- Lower turnover may indicate excess or obsolete inventory.

---

 Slow-Moving and Fast-Moving Inventory Identification Logic

Category Logic:
- Fast Moving: Sold recently (Low Days Since Last Sale)
- Slow Moving: Moderate Days Since Last Sale
- Dead Stock: No sales for more than 90 days

Business Logic:
If Stock Qty = 0 → Out of Stock
Else If Days Since Last Sale > 90 → Dead Stock
Else If Days Since Last Sale > 30 → Slow Moving
Else → Fast Moving

---

 Delivery Performance Analysis Methodology

Metrics Used:
- Average Delivery Time
- Delivery Delay
- On-Time Delivery Rate
- Regional Performance
- Monthly Delivery Trend

Analysis Steps:
1. Delivery Days = Shipping Date − Order Date
2. Measure average delivery time.
3. Compare delivery performance across regions, categories, and products.
4. Identify delayed shipments.
5. Analyze trends over time.

---

 Key Insights

- Fast-moving products contribute significantly to inventory turnover.
- Slow-moving and dead stock increase inventory holding costs.
- Delivery performance varies across regions.
- Inventory value is concentrated in a small number of high-value products.
- Monitoring inventory trends helps prevent stock shortages and overstock situations.

---

 Business Recommendations

- Replenish fast-moving products proactively to prevent stockouts.
- Reduce slow-moving inventory through promotions or optimized purchasing.
- Liquidate dead stock to free warehouse space and improve cash flow.
- Improve logistics in regions with frequent delivery delays.
- Continuously monitor inventory turnover as a key performance indicator.
- Use demand forecasting to optimize stock levels and improve operational efficiency.

---

 Dashboard Preview

Inventory Dashboard:
screenshots/Inventory_Analytics.png.png

Delivery Dashboard:
screenshots/Delivery_Performance.png.png

---

 Repository Structure

Milestone2_PowerBI.pbix.pbix
screenshots/
  Inventory_Analytics.png.png
  Delivery_Performance.png.png
README.md

---

 Conclusion

This dashboard enables businesses to monitor inventory health, improve delivery performance, and make informed supply chain decisions. By combining inventory analytics with logistics insights, organizations can reduce costs, enhance operational efficiency, and improve customer satisfaction.

 If you found this project useful, consider giving it a star!
