# JC Penney Data Analysis & Consultancy

This project provides a comprehensive data exploration and consultancy-style analysis of JC Penney's product and customer review data. It focuses on cleaning, transforming, and interpreting multi-source retail datasets to derive actionable insights into product performance and user behavior.

## Project Overview
The analysis utilizes a combination of JSON and CSV files to evaluate product catalogs, user demographics, and customer reviews. The project demonstrates professional data engineering techniques, including:
* **Data Ingestion:** Loading and mapping disparate JSON and CSV formats into structured pandas DataFrames.
* **Data Transformation:** Standardizing date formats, normalizing identifiers, and merging multi-source datasets for cohesive analysis.
* **Data Validation:** Performing quality checks to address missing values and ensure data integrity.
* **Exploratory Data Analysis (EDA):** Utilizing statistical methods to identify trends in product ratings, pricing, and user interaction.

## Dataset Structure
This analysis integrates five key datasets:
* `jcpenney_reviewers.json`: User demographic and review history.
* `jcpenney_products.json`: Detailed product metadata (images, prices, categories).
* `products.csv`: Standardized product information.
* `reviews.csv`: Customer-provided review scores and text.
* `users.csv`: User profile and location data.

*Note: The product data is real-world data, while the customer data is synthetic.*

## Key Features & Techniques
* **Data Cleaning:** Robust handling of `NaN` values and data type standardization.
* **Image Handling:** Automated workflows to fetch, process, and display product imagery from URLs.
* **Statistical Insights:** Analysis of review score distributions and user behavior patterns using correlation and grouping.
* **Visualization:** High-quality visualizations using `Matplotlib`, `Seaborn`, and `Plotly` to uncover trends in product performance.

## Prerequisites
To run this project, ensure you have the following libraries installed:
```bash
pip install pandas numpy matplotlib seaborn plotly pillow requests opencv-python
