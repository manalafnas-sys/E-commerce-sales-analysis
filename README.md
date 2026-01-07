# E-commerce-sales-analysis
## 1. Project Overview
This project focuses on analyzing an e-commerce sales dataset to understand sales performance, customer purchasing behavior, and product trends. The goal is to clean the raw data, perform exploratory data analysis (EDA), and extract meaningful insights that can support business decision making such as revenue growth and customer retention.

## 2. Tools & Technologies Used
* **Pandas & numpy**: Data cleaning, manipulation, and feature engineering.
* **Matplotlib**: Basic data visualization.
* **Seaborn**: Advanced statistical visualizations (KDE, Heatmaps, Regression plots).
* **Jupyter Notebook**: Environment for coding and documentation.

## 3. Dataset Information
* **Source:** Google Dataset (E-commerce Sales)
* **Total Records:** 1001 rows
* **Total Attributes:** 18 columns
* **Key Columns:**
* Product ID
* Category
* Price
* Review Score
* Review Count
* Monthly Sales (Month 1-12)

## 4. Key Steps Performed
1.  **Data Pre-processing**: Handled missing values, removed duplicates, and renamed columns for better readability.
2.  **Feature Engineering**: Created new metrics like `Total_Revenue`, `Total_Sales`, `Price_Range`, and `Sales_Growth_Pct`.
3.  **Exploratory Data Analysis (EDA)**: 
    * Conducted Univariate, Bivariate, and Multivariate analysis.
    * Generated 10 distinct visualizations including Histograms, Box plots, Scatter plots, and Heatmaps.
4.  **Statistical Summary**: Used `groupby` and `pivot_table` to validate visual findings with hard numbers.

## 5. Key Insights
* **Revenue Drivers**: "Books" and "Sports" are the highest-performing categories.
* **Pricing Strategy**: High-priced products ($250+) maintain strong sales volume, indicating a premium-tier customer base.
* **Customer Trust**: A 0.95 correlation exists between Price and Revenue, but Review Scores show a more subtle impact on volume.
* **Stability**: Monthly sales trends remain remarkably consistent throughout the year, with no significant seasonal crashes.

## 6. Visualizations
The project includes the following key plots:
**Histogram (KDE):** To see the "spread" of pricing and identify our target market tier.
**Box Plots:** To find "Outliers" (superstar products) and check the consistency of customer ratings.
**Heatmaps:** To calculate the correlation between price and revenue (finding what actually drives profit).
**Scatter Plots:** To see if high prices stop people from buying (Price vs. Sales).
**Regression Plot:** To see the trend of how customer satisfaction impacts total earnings.

## 7. How to Use
1.  Ensure you have Python installed.
2.  Install required libraries: `pip install pandas matplotlib seaborn`
3.  Open the `02_data_preprocessing.ipynb` file in Jupyter Notebook.
4.  Run all cells to view the analysis and generated charts.

## 8. Conclusion & Recommendations
The analysis suggests that the business should expand its premium product selection and focus marketing efforts on the Books category. Improving the average review score from 3.2 to 4.0 represents the biggest opportunity for organic revenue growth.
