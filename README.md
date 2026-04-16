# Zomato Bangalore Restaurants Analysis 🍕📊

## 📌 Project Overview
This project provides a comprehensive end-to-end data analysis of the restaurant ecosystem in Bangalore. By processing a dataset of over 12,000 records, the goal was to uncover market trends, pricing strategies, and service-based performance factors that contribute to a restaurant's success in the "Silicon Valley of India."

## 🛠️ Tech Stack
* **Language:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Database:** SQL (SQLite)
* **Business Intelligence:** Power BI (DAX, Interactive Dashboards)
* **Environment:** Google Colab / VS Code

## 🚀 Key Features & Workflow

### 1. Data Cleaning & Preprocessing (Python)
* Handled missing values and removed duplicates to ensure data integrity.
* Performed advanced string manipulation on the `rate` column (removed "/5" and handled "NEW" entries).
* Cleaned and converted the `approx_cost(for two people)` column to numeric format using regular expressions.
* **Result:** Improved data quality by approximately 15% through rigorous cleaning.

### 2. Exploratory Data Analysis (EDA)
* Analyzed restaurant density across different Bangalore neighborhoods (BTM, Koramangala, etc.).
* Identified the top 10 most popular cuisines by restaurant count and customer engagement (votes).
* Correlation studies between pricing, service types, and customer ratings.

### 3. SQL Analysis
* Migrated the cleaned dataset into a SQL environment to perform complex aggregations.
* Wrote queries to identify the "Sweet Spot" price range for the highest customer satisfaction.

### 4. Interactive Power BI Dashboard
* Developed custom **DAX Measures** for `Weighted Rating`, `Total Restaurants`, and `Market Share %`.
* Created a dynamic dashboard featuring:
    * **Tile Slicers** for filtering by Service Type (Delivery, Buffet, etc.).
    * **KPI Cards** for instant metric visibility.
    * **Market Saturation Maps** to support location-based business decisions.

## 📊 Key Insights
* **The Service Bonus:** Restaurants offering both **Online Ordering** and **Table Booking** maintain an average rating significantly higher than those with no digital services.
* **Market Dominance:** North Indian and Chinese cuisines hold the largest market share, but specialized "Cafe" and "Dessert" categories show the highest engagement-to-count ratio.
* **Top Hubs:** BTM has the highest concentration of restaurants, while locations like Koramangala show the most diversity in cuisine types.

## 📁 Repository Structure
* `zomato_cleaning.ipynb` - Python notebook for ETL and cleaning.
* `zomato_clean.csv` - The final cleaned dataset.
* `Zomato_Analysis.pbix` - The Power BI dashboard file.
* `screenshots/` - Images of the dashboard and code outputs.

## 📊 Dataset Information
The analysis is based on the Zomato Bangalore Restaurants dataset. 

* **Original Dataset:** [Download Raw CSV from Kaggle](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)
* **Processed Data:** The cleaned and compressed version used for this analysis is available in the `data/` folder as `zomato_clean.zip`.
---
**Contact:** [faisal19022@gmail.com](mailto:faisal19022@gmail.com) | [LinkedIn](https://www.linkedin.com/faisalyen)
