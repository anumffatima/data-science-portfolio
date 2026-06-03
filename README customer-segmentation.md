# Customer Segmentation Using K-Means Clustering

## Project Overview

This project uses K-Means Clustering, an unsupervised machine learning algorithm, to segment mall customers into different groups based on their purchasing behavior.

Customer segmentation helps businesses better understand their customers and create targeted marketing strategies for different customer groups.

The project was implemented using Python in Google Colab and uses the Mall Customers dataset from Kaggle.

---

## Dataset Information

The dataset contains information about 200 mall customers.

### Features

| Feature | Description |
|----------|------------|
| CustomerID | Unique customer identifier |
| Genre | Customer gender |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousands of dollars |
| Spending Score (1-100) | Customer spending score assigned by the mall |

---

## Project Objectives

- Perform customer segmentation using machine learning.
- Identify groups of customers with similar characteristics.
- Apply K-Means Clustering.
- Determine the optimal number of clusters using the Elbow Method.
- Visualize customer segments.
- Generate business insights from the identified clusters.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the dataset.
2. Removed the CustomerID column because it does not contribute to clustering.
3. Converted Gender values into numerical format.
4. Selected relevant features for clustering.
5. Prepared the data for the K-Means algorithm.

---

## Methodology

### Step 1: Exploratory Data Analysis

The dataset was explored to understand customer characteristics and verify data quality.

### Step 2: Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

The graph showed that 5 clusters provided the best balance between simplicity and accuracy.

### Step 3: K-Means Clustering

The K-Means algorithm was trained with:
python

KMeans(n_clusters=5, random_state=42)

Each customer was assigned to one of five clusters based on similarities in age, income, and spending behavior.

---

## Results

The model successfully divided customers into five distinct groups.

### Cluster 1
High Income – High Spending

### Cluster 2
High Income – Low Spending

### Cluster 3
Low Income – High Spending

### Cluster 4
Low Income – Low Spending

### Cluster 5
Average Income – Average Spending

---

## Business Insights

- High Income – High Spending customers are premium customers and should be targeted with exclusive offers.
- High Income – Low Spending customers represent an opportunity for increased engagement.
- Low Income – High Spending customers may respond well to promotions and discounts.
- Low Income – Low Spending customers are less valuable from a marketing perspective.
- Average customers form the largest stable customer group.

---

## Project Structure

customer-segmentation-kmeans/
│
├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
├── README.md

---

## Author

Anum Fatima Awan

Data Science & Machine Learning Portfolio Project

