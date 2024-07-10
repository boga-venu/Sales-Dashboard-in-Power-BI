# Sales-Dashboard-in-Power-BI

This repository contains a dynamic Power BI sales dashboard designed to provide comprehensive insights into sales data. The dashboard leverages interactive visualizations and drill-through capabilities to enable users to explore and analyze data in depth. It aims to present all necessary information clearly and concisely, facilitating data-driven decision-making.

## Dashboard

![Power BI Dashboard](https://github.com/boga-venu/Sales-Dashboard-in-Power-BI/assets/174999641/20308c7d-329c-49da-8486-456e504b8cbe)


## Objective

The main objective of this dashboard is to offer a dynamic and interactive platform for users to gain the best insights into sales data. By using Power BI’s powerful features, this dashboard allows users to easily navigate through various sales metrics, perform detailed analyses, and uncover valuable information from the data.

## Files
- `Sales Data.csv`: The main data source file
- `Sales Data.xlsx`: Data source excel file
- `Sales Dashboard.pbix`: The Power BI file containg the Dashboard
- `Power BI Dashboard.png`: Screenshot of the Dashboard
- `Drill Through Electronics.png`: Screenshot of Drill-Through page for Electronics Category

## Features
- Total Revenue and Sales: Displays overall revenue and total sales figures prominently at the top for quick reference.
- Category Insights: Highlights the most valuable and most sold categories, providing a snapshot of product performance.
- Regional Analysis: Breaks down sales and revenue by region, offering a geographical perspective on sales distribution.
- Sales Trends: Visualizes sales vs. revenue and total sales by month, helping to identify trends over time.
- Payment Methods: Shows the distribution of sales by different payment methods, offering insights into customer preferences.
- Average Unit Price: Displays the average unit price for each category, giving a quick view of pricing dynamics.
- Drill-Through Page: Provides detailed insights for each category through drill-through page, allowing for deeper analysis and understanding.

## How to Use
1. Download Files: Download all the files provided in the repository
2. Open Power BI: Open the Power BI Desktop application.
3. Load the Data: Load the provided data file into Power BI.
4. Explore the Dashboard: Interact with the various visual elements, using filters and slicers to explore different aspects of the sales data.
5. Use Drill-Through: Right-click on a category in the main dashboard and select "Drill Through" to view detailed information for that category.

## Detailed Information
- As Power BI Dashboard is Dynamic in nature all the charts are connected and can be used as filters to other charts
- As shown below, Month "March" selected in the `Total sales chart` acts as filter and affect all other charts, Giving the information(performance) in March.
  
  ![March select](https://github.com/boga-venu/Sales-Dashboard-in-Power-BI/assets/174999641/c512b0d4-1f70-4991-9f97-7ddd2834c04f)
  
- Similarly we can use any metric in any chart for filtering along with the provided slicers for `Month` and `Category`.

- If we right click on any category from any chart, a menu appears with option `Drill through` as shown below

  ![Drill through option](https://github.com/boga-venu/Sales-Dashboard-in-Power-BI/assets/174999641/abede77e-3563-48e7-84b7-122146a26472)

- when we click on it, it shows "Category Info". if we click on it, it takes to the `Category Info` page.
- the screenshots provided below are the Drill through pages for the categories `Clothing` and `Electronics` Respectively

  ![Drill Through Clothing](https://github.com/boga-venu/Sales-Dashboard-in-Power-BI/assets/174999641/bb439ea0-e281-47e0-a984-023e0e9b762f)

  ![Drill Through Electronics](https://github.com/boga-venu/Sales-Dashboard-in-Power-BI/assets/174999641/e03ca675-db75-448e-a002-e958cd78738a)

- This page will provide detailed information regarding the category which help in furthur analysis and gain usable insites

## Insights

### Overall Insites from Dashboard

1. Key Metrics Displayed:

    -  Total Revenue: 80.57K
    -  Total Sales: 518
    -  Most Valuable Category: Electronics
    -  Category Needing Attention: Beauty Products

2. Sales vs Revenue by Category:

   - Top Performing Categories:
       - Electronics: 35K revenue from around 40 units sold.
       - Home Appliances: 19K revenue.
       - Sports: 14K revenue.

3. Sales by Month:

   - Peak sales months are January and March.
   - There is a decline in sales from May onwards.

4. Sales by Region:

   - Asia: Highest sales and revenue (233 sales, 36.84K revenue).
   - North America and Europe also perform well but lag behind Asia.

5. Payment Methods:

   - Majority of transactions are done via Debit Card (63.51%).
   - Credit Card and PayPal make up the rest.

6. Average Unit Price:

   - Highest: Electronics (692)
   - Lowest: Books (16)
  
### Categorical Insights

1. Electronics:

    - Highest revenue generator
    - Relatively low unit sales compared to revenue, indicating high-value items
    - Highest average unit price ($692)
    - Popular products: Apple watch, Cannon Camera, Macbook Pro
    - Most sales occur in North America

2. Home Appliances:

    - Second-highest revenue generator
    - Medium to high-value items
    - Average unit price of $320
    - Popular products: LG TV, Blueair classic, Roomba
    - Steady sales, with possible increase in summer months
    - Most sales occur in Europe

3. Sports:

    - Third in revenue
    - High unit sales, indicating popularity and accessibility
    - Standout product: Peloton Bike (high-value item)
    - Moderate sales, possible increase in Spring months
    - Most sales occur in Asia

4. Clothing:

    - Highest unit sales but lower revenue
    - Low average unit price ($68)
    - Popular products: Nike Air Force, North face Jacket
    - Sales appear consistent, with potential seasonal variations
    - Most sales occur in Asia

5. Beauty Products:
   
    - Low revenue and unit sales
    - Average unit price of $62
    - Popular items: Dyson Hair dryer, Cera Ve CLeanser
    - Moderate but consistent sales throughout the period
    - Most sales in Europe

6. Books:

    - Lowest revenue category
    - High unit sales, indicating popularity but low price point
    - Lowest average unit price ($16)
    - Consistent sales throughout the period
    - Most sales in North America

### Key Observations:

  - Electronics and Home Appliances drive the most revenue due to higher price points.
  - Clothing and Books have the highest sales volume but lower revenue due to lower price points.
  - There appears to be some regional preference in categories (e.g., Beauty Products in Europe).
  - Seasonal trends are subtle but present, especially in Clothing and Sports categories.

## Conclusion

This dynamic Power BI dashboard is designed to be an effective tool for visualizing and understanding sales data. By consolidating key metrics and presenting them in an interactive manner, along with the drill-through feature for detailed category insights, it helps users make informed decisions and identify important trends.
