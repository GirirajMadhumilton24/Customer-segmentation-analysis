# Customer Segmentation

This project performs customer segmentation using K-means and Hierarchical Clustering. The analysis is based on customer data including annual income and spending score.

## Dataset

The dataset contains 2000 customer records with the following features:
- **CustomerID**: Unique customer ID
- **Gender**: Customer's gender
- **Age**: Customer's age
- **Annual Income ($)**: Customer's annual income
- **Spending Score (1-100)**: Customer's spending score
- **Profession**: Customer's profession
- **Work Experience**: Years of work experience
- **Family Size**: Size of the customer's family

## Steps

1. **Data Loading and Preprocessing**: 
   - Load the data, handle missing values, and scale it for clustering.

2. **Clustering**:
   - Apply **K-means** clustering to segment customers.
   - Use **Hierarchical Clustering** to find relationships in the data.

3. **Visualizations**:
   - Visualize the customer clusters and relationships using plots.

## Libraries Used

- `pandas`, `numpy` for data manipulation
- `matplotlib`, `seaborn` for visualizations
- `scikit-learn` for clustering algorithms
- `scipy` for hierarchical clustering
