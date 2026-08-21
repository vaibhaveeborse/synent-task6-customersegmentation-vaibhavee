# Task 6: Customer Segmentation

## Objective

The objective of this project is to segment customers based on their annual income and spending behavior using the K-Means clustering algorithm.

## Problem Statement

The goal of this project is to analyze customer data and identify groups of customers with similar characteristics based on their income and spending score. Customer segmentation can help businesses understand their customers and develop more targeted marketing strategies.

## Dataset

The project uses the **Mall Customer Dataset**.

The dataset contains **200 customer records** and the following attributes:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

The `CustomerID` column is used only as an identifier and was not used for clustering.

## Tools and Technologies

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Approach

The project was completed using the following steps:

1. Imported the required Python libraries.
2. Loaded the Mall Customer dataset using Pandas.
3. Explored the structure and statistical information of the dataset.
4. Checked for missing values.
5. Checked for duplicate records.
6. Examined the data types of the columns.
7. Selected Annual Income and Spending Score as the main features for customer segmentation.
8. Visualized the initial distribution of customers.
9. Used the Elbow Method to determine the appropriate number of clusters.
10. Applied the K-Means clustering algorithm.
11. Divided customers into five clusters.
12. Visualized the resulting customer segments.
13. Calculated cluster profiles using average age, income, spending score, and customer count.
14. Created visualizations to compare the customer segments.
15. Identified key customer segmentation insights.

## Data Preprocessing

The dataset was checked for missing values and duplicate records.

- Missing values: None
- Duplicate records: None

The following features were selected for clustering:

- Annual Income (k$)
- Spending Score (1-100)

CustomerID was excluded because it is an identifier and does not represent customer behavior.

## K-Means Clustering

The **K-Means clustering algorithm** was used to group customers with similar income and spending behavior.

The **Elbow Method** was used to determine the optimal number of clusters.

Based on the Elbow Method, **5 clusters** were selected for the final K-Means model.

## Visualizations

### 1. Customer Distribution

A scatter plot was used to visualize customers based on Annual Income and Spending Score before clustering.

### 2. Elbow Method

The Elbow Method was used to evaluate different values of K and identify the appropriate number of customer clusters.

### 3. Customer Segmentation

A scatter plot was created to visualize the five customer segments generated using K-Means clustering.

### 4. Customer Segment Size

A bar chart was used to show the number of customers belonging to each cluster.

### 5. Cluster Profile

Average age, annual income, and spending score were calculated for each customer segment.

### 6. Heatmap

A heatmap was created to compare the characteristics of the different customer segments.

## Key Insights

- Customers can be divided into five distinct groups based on their annual income and spending behavior.
- Customers with higher income and higher spending scores can represent valuable customers for businesses.
- Customers with higher income but lower spending scores may represent potential customers who could be targeted with personalized offers.
- Customers with lower income and higher spending scores show strong purchasing interest despite having lower income.
- Customers with lower income and lower spending scores represent customers with relatively low purchasing activity.
- The clustering results can help businesses understand differences in customer behavior and develop targeted marketing strategies.

## Conclusion

Customer segmentation was successfully performed using the K-Means clustering algorithm on the Mall Customer dataset.

Annual Income and Spending Score were selected as the primary features for identifying customer groups. The Elbow Method was used to determine the appropriate number of clusters, and five customer segments were created.

The resulting clusters were visualized and analyzed using customer characteristics such as age, income, spending score, and customer count.

This project demonstrates how machine learning clustering techniques can be used to understand customer behavior and support targeted marketing and business decision-making.

## Files in this Repository

- `Task6_Customer_Segmentation.ipynb` - Google Colab/Jupyter Notebook containing the complete analysis.
- `Mall_Customers.csv` - Dataset used for customer segmentation.
- `README.md` - Project documentation.

## Author

**Vaibhavee Borse**
