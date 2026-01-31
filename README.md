# Food Delivery Data Analysis – Hackathon Submission

## Overview
This repository contains my solution for a data analytics hackathon conducted as part of an internship evaluation.
The task involved combining datasets from multiple formats and performing analysis to answer MCQs and numerical questions.

## Datasets Used
- **orders.csv** – Transactional order-level data
- **users.json** – User master data with city and membership details
- **restaurants.sql** – Restaurant master data with cuisine and rating information

## Tools & Technologies
- Python
- Pandas
- SQLite
- Jupyter Notebook

## Data Processing Steps
1. Loaded datasets from CSV, JSON, and SQL formats
2. Cleaned and standardized column names
3. Converted date fields to datetime format
4. Performed LEFT JOINs to retain all order records
5. Created a unified final dataset for analysis

## Final Dataset
The final merged dataset includes:
- Order details
- User information
- Restaurant information

File location: output/final_food_delivery_dataset.csv


## Analysis Performed
- Order trends over time
- Membership impact (Gold vs Regular)
- City-wise revenue performance
- Cuisine-wise revenue and average order value
- Restaurant rating vs revenue analysis
- Top-performing restaurants
- Quarterly revenue analysis

## Key Insights
- Metro cities contribute the highest revenue
- Gold and Regular users place nearly equal number of orders
- Mexican cuisine has the highest average order value
- Restaurants with ratings above 4.5 generate the highest revenue
- Revenue peaks during Q3 of the year

## How to Run
1. Clone the repository
2. Open `notebooks/food_delivery_analysis.ipynb`
3. Run the notebook cells sequentially

## Author
Tejas Pendam
