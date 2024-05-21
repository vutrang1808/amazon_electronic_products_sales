# Project: Amazon Electronics Products Sales

This notebook demonstrates a comprehensive sales analysis of an Amazon electronics products dataset with dimensions 1.3M x 10. The solution is implemented in `Python`, leveraging `Pandas` for data manipulation and `Matplotlib` for visualization.

The analysis aims to address the following questions:
1. What are the categories of electronic products?
2. Find the Top-10 users that bought the most in each category.
3. Analyze sales in a certain year, grouped by categories.
4. Given a brand, identify the categories in which it has products.
5. Determine the categories with the highest market competition.

## **Approach**

A logical and systematic approach is followed throughout the analysis, with each step accompanied by insights into the dataset. Key observations include:
- **Timestamp Accuracy:** Inconsistencies between the `timestamp` and `year` columns are observed, and thus decided to use the `timestamp` as the time reference for each purchase.
- **Data Completeness:** A significant proportion of rows (97%) contain NaN values in either the `brand` or `user_attr` columns, leading to the exclusion of these columns from some analyses due to their limited utility.

## **Dataset Details**

The dataset encompasses Amazon electronics sales data spanning from 1999 to 2018. It is available on [Kaggle](https://www.kaggle.com/datasets/edusanketdk/electronics/data).

## **Gained Insights**

1. **Categories of Electronic Products:**
        Identified the unique categories of products available in the dataset.

2. **Top-10 Users per Category:**
        Determined the top 10 users who purchased the most in each category.

3. **Yearly Sales Grouped by Categories:**
        Analyzed and visualized sales data for specific years, grouped by product categories.

4. **Brand-wise Product Categories:**
        For each brand, identified the categories in which its products are listed.

5. **Market Competition Analysis:**
        Determined which categories have the highest market competition based on the number of unique brands.

![Sales.png](./plots/Sales.png)

![PieChart_exploded.png](./plots/PieChart_exploded.png)
