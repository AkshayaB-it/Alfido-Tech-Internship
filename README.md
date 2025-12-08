# Alfido Tech Internship - Task 1: Zomato Dataset Analysis

## Overview
This repository contains **Task 1** of my **Data Science Internship at Alfido Tech**.  
The goal was to analyze the **Zomato restaurant dataset** and generate meaningful insights using **Python, Pandas, and data visualization libraries**.

## Dataset
The dataset includes information about restaurants, such as:

- Restaurant types
- Cuisines
- Locations
- Cost for two
- Ratings
- Online delivery availability

## Steps Performed
1. **Data Cleaning**
   - Removed duplicate rows
   - Cleaned the `rate` column
   - Cleaned the `approx_cost(for two people)` column
   - Filled missing values

2. **Exploratory Data Analysis (EDA)**
   - Top 10 restaurant types
   - Online delivery vs rating
   - Most popular cuisines
   - Top locations
   - Cost distribution
   - Rating distribution
   - Votes vs rating

3. **Visualizations**
   - Bar charts
   - Histograms
   - Boxplots
   - Scatter plots

## Key Insights
- Casual Dining and Quick Bites are the most common restaurant types.
- Restaurants offering online delivery generally have slightly higher ratings.
- Popular cuisines include North Indian, Chinese, and Fast Food.
- Areas like BTM Layout, Indiranagar, and Koramangala have the highest number of restaurants.
- Most customers spend between ₹200 – ₹600 for two people.
- Most restaurants have ratings between 3.5 and 4.5.

## Files in this Repository
- `Zomato_Dataset_Analysis.ipynb` → Complete notebook with code and visualizations  
- `zomato_cleaned.csv` → Cleaned dataset (optional)

## Tools Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Google Colab
