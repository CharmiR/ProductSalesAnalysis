# ProductSalesAnalysis
Performed comprehensive analysis on 12 months of transactional sales data from a retail company to uncover actionable business insights, improve decision-making, and identify revenue opportunities using Python.


# Retail Sales Analysis – Real-World Business Intelligence Project (Python, Pandas, Matplotlib)
Objective:
Performed comprehensive analysis on 12 months of transactional sales data from a retail company to uncover actionable business insights, improve decision-making, and identify revenue opportunities using Python.

## Key Tasks & Achievements:
📊 Data Preparation:

-->Consolidated 12 individual Excel datasets using os, pandas.read_excel(), and pd.concat() into a single master DataFrame (~186,000 records).

-->Cleaned and standardized data by removing null rows, parsing datetime formats using pd.to_datetime(), and converting strings into structured values (e.g., city, time, product combos).

## 📅 Sales Trend Analysis:

-Created a "Sales" feature (Quantity Ordered * Price Each) to calculate revenue.

-Used groupby() and aggregations to find the best-performing month (December) and most profitable cities (San Francisco, Los Angeles).

## 🕐 Customer Behavior Insights:

-Extracted time-of-day from timestamps using .dt.strftime() and custom labeling functions to categorize orders into time blocks.

-Identified afternoons (12 PM – 4 PM) as the best window for ad placements based on peak sales volume.

## 🏙️ Geographic Sales Breakdown:

-Parsed purchase addresses to extract and analyze city-level sales trends.

-Ranked cities by revenue and total products sold using groupby() and value_counts().

## 🛍️ Market Basket Analysis:

-Identified frequently bought together products using duplicate Order IDs and .transform(lambda x: ', '.join(x)).

-Discovered top combinations like iPhone + Lightning Cable and Google Phone + USB-C Cable, aiding bundling strategies.

## 📈 Visualization & Reporting:

Visualized insights using Matplotlib bar and line charts to present:

Monthly sales performance

City-wise revenue

Time-of-day purchasing behavior

Top product bundles
