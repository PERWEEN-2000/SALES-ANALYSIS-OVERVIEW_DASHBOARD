
📊 Dashboard Insights
The dashboard provides a clear overview of sales performance. Here are some key insights you can glean from the visuals:

Overall Sales: The "Total Sales 'All Time'" card shows a total of $2.30 million. This metric remains constant regardless of the year selected on the slicer.
Customer & Order Count: The dashboard shows a total of 793 customers and 5009 total orders. These numbers likely change based on the year selected, as the problem statement indicates these should be based on slicer selections.
Regional Performance: The tree map visualizes sales and profit by region. The 
West region appears to have the highest sales at 725K, followed by the East at 679K. * 
Customer Sales: The matrix chart shows the top 5 customers by sales for each product category. For example, 
Adrian Barton has high total sales of $14,473.57 across all categories. The chart allows for a comparison of sales across different product categories (Furniture, Office Supplies, and Technology) for these top customers.
Year-over-Year (YOY) Trends: The line and clustered column chart compares current and previous year sales, with a trend line for the YOY%. The bars represent sales for each year (2014-2017) , with the line showing the percentage change. For instance, there's a significant positive change in YOY% from 2016 to 2017. The color-coding on the YOY% card will turn green for positive growth and red for negative.

Here's what I focused on:✅ 
Creating a Dynamic Slicer: A year slicer to allow for interactive exploration of sales data.
✅ DAX Measures: I created several DAX measures to calculate key metrics, including:
Total Sales: An 'All Time' measure that isn't affected by the year slicer.
Current & Previous Year Sales: Dynamically calculated based on the year selected.
YOY%: A custom measure to show year-over-year growth, with conditional formatting to show positive change in green and negative in red 🟢🔴.
Total Customers & Orders: Counts that update with the slicer selection.
✅ Visualizations: I used a mix of visuals to tell a complete story:
A Tree Map to visualize regional sales and profit.
A Matrix Chart to showcase top 5 customers by sales for each category.
A **Line & Clustered Column** Chart to trend current vs. previous year sales and YOY%.

This dashboard provides actionable insights, helping to quickly identify top-performing regions and customers, and understand sales trends over time.
