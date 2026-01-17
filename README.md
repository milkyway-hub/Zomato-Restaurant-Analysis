# Zomato Restaurant Analysis

## Project Overview
This project is a comprehensive analysis of a multi-table Zomato-style dataset to understand customer behavior, restaurant performance, and food preferences. The goal is to generate actionable business insights for restaurants and food delivery platforms.

## Dataset Description
The dataset contains 5 CSV files:

- **orders.csv** – Customer orders with quantity, amount, date, and user info.
- **users.csv** – Customer demographic information including age, gender, monthly income.
- **menu.csv** – Menu items with price, restaurant ID, and cuisine.
- **food.csv** – Food details including vegetarian or non-vegetarian classification.
- **restaurant.csv** – Restaurant information including city, rating, and cost.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Analysis
- Merged multiple datasets to create a unified dataframe
- Top-selling food items and cuisine analysis
- Veg vs Non-Veg demand trend
- Revenue analysis by restaurant and city
- Monthly revenue trend analysis
- Customer age vs spending patterns
- Rating vs revenue correlation

## Key Insights
- Majority of orders are Veg, showing strong vegetarian preference
- Restaurants with higher ratings (>4.0) have higher average revenue
- Top cities contribute most to total sales, indicating metro-city concentration
- Top 10 restaurants generate a significant portion of total revenue
- Age groups 25-35 are the highest spenders on food delivery

## Future Work
- Customer segmentation based on order behavior
- Predictive analytics for restaurant demand forecasting
- Interactive dashboards with Power BI or Tableau

## Project Structure
zomato-restaurant-analysis/
│
├── data/
│ ├── orders.csv
│ ├── users.csv
│ ├── food.csv
│ ├── menu.csv
│ └── restaurant.csv
│
├── zomato_analysis.ipynb
├── README.md
