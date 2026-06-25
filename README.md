# Sales Dashboard - Product Analytics
This project is a comprehensive Excel-based Sales Performance Dashboard designed to analyze and provide actionable insights into geographical locations, retailer profiles, product variations, time elements, and distinct sales channels.
📊 Key Performance Indicators (KPIs)
At the top of the dashboard, high-level summary metrics provide an immediate snapshot of overall business health:
•	Total Sales: The sum of all revenue.
•	Total Quantity: The total volume of items sold.
•	Total Orders: The total count of distinct purchases.
•	Average Order Value (AOV): Calculated as Total Sales divided by Total Orders.
📈 Dashboard Visualizations
The dashboard utilizes hidden data worksheets and Pivot Tables to power several dynamic charts:
•	Sales Trend Over Time (Line Chart): Tracks seasonal trends, revenue spikes, and declines month by month.
•	Revenue by Retailer (Horizontal Bar Chart): Ranks top-performing accounts in descending order, highlighting major partners like West Gear, Foot Locker, Sports Direct, Kohl's, Walmart, and Amazon.
•	Region-wise Sales for Products (Clustered Bar Chart): Compares the sales performance of specific product lines (e.g., Adidas, Asics, New Balance, Nike, Puma, Salomon) broken down by region.
•	Product Performance Mix (Horizontal Bar Chart): Illustrates which specific product lines are driving the bulk of your revenue.
•	Sales Method Analysis (Donut Chart): Shows the performance breakdown of your sales channels, clearly displaying the revenue split between Online, Outlet, and In-Store purchases.
•	Sales Distribution by Region (Column Chart): Highlights geographical performance and market penetration across the Midwest, Northeast, South, Southeast, and West.
🎛️ Interactivity & Filtering
To make the dashboard fully interactive and scannable, it includes dynamic controls on the top and left-hand side:
•	Categorical Slicers: Users can filter the entire dashboard by Region (Midwest, Northeast, South, Southeast, West) and Sales Method (In-store, Online, Outlet).
•	Timeline Slicer: A native Excel date slicer allows users to easily filter the data by specific months, quarters, or years to observe dynamic changes in trends.
⚙️ Technical Structure
•	Frontend: A clean, grid-based layout prioritizing KPIs at the top, trends in the middle, and dimensional breakdowns along the bottom.
•	Backend: Powered by a hidden "Data Worksheet" consisting of summary Pivot Tables that map directly to each chart type (Time Series, Leaderboard, Geography, Channels, and Inventory/Volume).
