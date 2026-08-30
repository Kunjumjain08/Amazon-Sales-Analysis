# Amazon-Sales-Analysis

### A Beginner Exploratory Data Analysis Project

**Author:** Kunjum Jain

## About the Dataset
This dataset contains product details from Amazon, including actual price, discounted price, discount percentage, ratings, and number of ratings.

## Project Objective
The main goal of this project is to perform Exploratory Data Analysis (EDA) on Amazon sales data to find meaningful insights such as:
- How discounts are distributed across products
- Relationship between discount and customer ratings
- Which price range of products gets better ratings
- Overall pricing and discount trends

## Key Findings
- Discounted price and actual price show an extremely strong positive correlation (r = 0.96)
- Price shows almost no correlation with rating (0.12) or rating count (-0.03) — price does not meaningfully predict customer satisfaction
- Ratings remain fairly consistent (3.8-4.3) across all top product categories
- Electronics is the most expensive category by a wide margin, yet its rating is not higher than cheaper categories
- Pricing is heavily right-skewed — most products fall under ₹10,000-20,000, with a few high-value outliers

## Tools Used
- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## Files
- `Amazon Sales Data Analysis.ipynb` — Full analysis notebook with code, visualizations, and insights

## About the Dataset
This dataset contains product details from Amazon, including actual price, discounted price, discount percentage, ratings, and number of ratings.

**Source:** [Amazon Sales Dataset on Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)
