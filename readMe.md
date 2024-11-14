# Zomato Customer Order Pattern Analysis

## Project Overview
This project analyzes Zomato's customer order patterns to uncover key trends in online vs. offline ordering, preferred restaurant types, and peak ordering times. By deriving actionable insights, we aim to help Zomato optimize its marketing strategies and improve customer engagement through targeted offers.

## Problem Statement
> "Analyze Zomato's customer order patterns to identify key trends in online vs. offline ordering, preferred restaurant types, and peak ordering times. The goal is to provide actionable insights for Zomato to optimize marketing strategies and improve customer engagement through targeted offers."

## Objective
To use data analysis to help Zomato make data-driven decisions about where to focus its promotional efforts, particularly in boosting offline orders.

## Analysis Steps

1. **Data Loading and Library Importing**: 
   - Importing essential libraries such as `pandas`, `numpy`, `seaborn`, and `matplotlib` for data manipulation, analysis, and visualization.
   - Loading the Zomato dataset and creating a DataFrame to view the initial structure of the data.

2. **Data Cleaning and Transformation**:
   - Handling missing values, duplicates, and outliers.
   - Defining a function to process and convert rating values from strings to floats for easier analysis.

3. **Exploratory Data Analysis (EDA)**:
   - **Restaurant Types**: Analyzing the types of restaurants customers primarily order from.
   - **Vote Analysis by Restaurant Type**: Grouping by restaurant type to assess the total votes each type has received.
   - **Rating Distribution**: Visualizing the rating distribution to understand the common rating range for restaurants.
   - **Order Costs for Couples**: Examining the average spending range of couples who frequently order online.
   - **Online vs. Offline Ratings**: Comparing ratings received by online and offline orders.
   - **Restaurant Types for Offline Orders**: Using a heatmap to visualize which restaurant types receive more offline orders to identify where to target offline promotions.

4. **Insights and Recommendations**:
   - Based on the analysis, summarizing customer preferences in terms of restaurant types, spending patterns, and ordering modes.
   - Providing actionable insights for Zomato to focus promotional efforts on offline orders, especially for casual dining, and recommending targeted offers to improve customer engagement.

## Tech Stack
- **Python**: Data analysis and visualization.
- **Pandas** and **NumPy**: For data manipulation.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Jupyter Notebook**: For documentation and analysis.

