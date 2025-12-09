Adventure works Dashboard

1. Project Title / Headline
🚴 Adventure Works: Executive Sales, Customer & Product Insights Dashboard An advanced, multi-page business intelligence solution built with Power BI to analyze the full sales lifecycle—from global regional performance to individual product profitability and customer demographics.

2. Short Description / Purpose
This report serves as a central analytics platform for the Adventure Works cycling brand, transforming raw transactional data from Kaggle into actionable insights. It features a hierarchical navigation flow: users start at a high-level Executive Dashboard to monitor KPIs, and can perform deep-dive analyses via Drillthrough actions to investigate specific product performance or customer trends. The tool allows stakeholders to identify profitable regions, simulate pricing scenarios, and optimize inventory based on return rates.

3. Tech Stack
The report utilizes advanced Power BI features to deliver a highly interactive experience:

⚙️ Advanced Modeling: Implements a Snowflake Schema, enabling complex filtering across Product Categories, Subcategories, and SKUs.

🖱️ Drillthrough Navigation: A seamless UX feature where users right-click a product on the main dashboard to jump specifically to the "Product Detail" page, carrying over the filter context.

🎛️ What-If Analysis: Features a "Price Adjustment (%)" parameter on the Product Detail page, allowing managers to forecast how price changes affect Total Profit in real-time.

🧠 Dynamic DAX Measures: Utilizes time-intelligence (Year-over-Year growth), dynamic titles, and disconnected tables for metric selection (switching between Orders, Revenue, and Profit visuals on the fly).

🔖 Bookmarks & Page Navigation: Custom buttons (e.g., "Total Customers" vs. "Revenue per Customer") to toggle between different views without cluttering the report.

🗺️ Geospatial Visualization: Bing Maps integration for analyzing sales distribution across continents.

4. Data Source
Source: Kaggle (Adventure Works Dataset). The dataset consists of raw CSV/Excel files processed into a structured model:

Fact Tables: Sales Data and Returns Data containing transactional history.

Dimension Tables: Customer, Product, Territory, and Calendar lookups.

Normalization: Product data is normalized into three tables (Category > Subcategory > Product) to handle the hierarchy efficiently.

5. Features / Highlights
• Executive Dashboard (Home Page)

High-Level KPIs: Instant view of Revenue ($24.9M), Profit, Orders, and Return Rates.

Return Analysis: A focus on quality control, highlighting that "Shorts" are the most returned product type.

Top Products Matrix: The entry point for analysis—users can identify a top-selling item here and drill through for more details.

• Product Detail Page (Drillthrough Destination)

Goal: To analyze the performance of a single selected product (e.g., "Water Bottle - 30 oz").

Scenario Planning: Includes a "Price Adjustment" slider that lets users simulate a price increase/decrease (e.g., +10%) and visually compare "Total Profit" vs. "Adjusted Profit" on a line chart.

Performance vs. Targets: Gauge charts show how the product is performing against monthly targets for Orders, Revenue, and Profit.

• Customer Detail Page

Customer Segmentation: Donut charts break down sales by Income Level (High vs. Average vs. Low) and Occupation (Professional, Management, etc.), helping marketing teams target the right audience.

Top Customer Analysis: A dynamic card highlights the top customer (Mr. Maurice Shan) and their specific contribution ($12.4K Revenue), enabling VIP customer tracking.

Growth Tracking: A line chart visualizes "Revenue per Customer" over time to track engagement trends.

• Map Page

Geospatial Insights: A dark-mode map visualizing sales volume by location.

Regional Slicers: Custom buttons at the top allow users to quickly filter the view by specific markets: Europe, North America, or Pacific.

• Business Impact

Pricing Strategy: The "What-If" tool empowers sales managers to find the "sweet spot" for pricing without risking real-world revenue.

Targeted Marketing: By seeing that "Professionals" and "Average Income" earners drive the most orders, marketing spend can be optimized for these demographics.

Operational Efficiency: The ability to see exactly where (Map) and what (Product Drillthrough) is selling allows for better inventory distribution.
