# Customer Segmentation Using Machine Learning

## Project Overview

This project aims to perform customer segmentation using machine learning techniques. By understanding customer behaviors and demographics, businesses can tailor their marketing strategies and enhance customer experience.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Collection](#data-collection)
- [Data Preparation](#data-preparation)
- [Data Visualization](#data-visualization)
- [Clustering Techniques](#clustering-techniques)
- [Results and Insights](#results-and-insights)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Data Collection

The dataset used in this project is the 'Mall_Customers.csv' file, which contains information about customers such as:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Data Preparation

The data preparation steps included:

- Loading the data into a Pandas DataFrame.
- Performing exploratory data analysis (EDA) to understand the data distribution.
- Checking for and handling any missing values.
- Normalizing the data for clustering.

## Data Visualization

To gain insights into the customer data, several visualizations were created:

- Distribution of Gender
- Distribution of Age
- Distribution of Annual Income
- Distribution of Spending Score
- Income Distribution by Gender

## Clustering Techniques

Two main clustering techniques were applied:

1. **K-Means Clustering**:
   - Optimal number of clusters was determined using the Elbow Method.
   - Clusters were visualized to interpret the segmentation.

2. **Hierarchical Clustering**:
   - Agglomerative Clustering was performed.
   - Dendrogram was used to visualize the cluster hierarchy.

## Results and Insights

The clustering analysis revealed distinct customer segments based on spending behavior and income levels. These insights can be used for targeted marketing and improving customer engagement.

## Dependencies

The project requires the following Python libraries:

- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn

Install the dependencies using:
```bash
pip install -r requirements.txt
