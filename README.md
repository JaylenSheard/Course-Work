# Customer Segmentation Project

## Description

This project focuses on segmenting customers based on their purchasing behavior and demographic attributes using the K-Means clustering algorithm. The dataset used in this project includes information about mall customers, such as their age, annual income, and spending score.

Customer segmentation is a crucial aspect of marketing as it helps businesses understand their customer base and target them more effectively. By grouping customers into different clusters, businesses can tailor their marketing strategies to better meet the needs of each segment.

## Project Structure

The project is organized into several key sections:

1. **Data Loading and Exploration**:
    - The dataset is loaded and basic exploratory data analysis (EDA) is performed to understand the distribution of features such as age, income, and spending score.
    - Visualizations include distribution plots, KDE plots, and box plots to analyze the relationships between different features.

2. **Bivariate and Multivariate Analysis**:
    - Scatter plots and pair plots are used to visualize the relationships between pairs of features.
    - Correlation analysis is conducted to understand the linear relationships between variables.

3. **Clustering Analysis**:
    - K-Means clustering is applied to group customers into clusters based on their annual income and spending score.
    - The optimal number of clusters is determined by analyzing the inertia scores across different cluster sizes.
    - The resulting clusters are visualized to interpret the segmentation.

## Installation

To run this project locally, you'll need to have Python installed along with the following libraries:

```bash
pip install pandas seaborn matplotlib scikit-learn
```

## Usage

You can run the Jupyter notebook file `Customer-Segmentation.ipynb` to reproduce the analysis and visualizations. The notebook guides you through the steps of loading the dataset, performing exploratory data analysis, and applying K-Means clustering.

## Dataset

The dataset used in this project is the **Mall Customers** dataset, which contains the following columns:

- **CustomerID**: Unique ID assigned to the customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Annual Income (k$)**: Annual income of the customer in thousands of dollars
- **Spending Score (1-100)**: Score assigned by the mall based on customer behavior and spending nature

## Results

The clustering analysis identified five distinct segments of customers based on their income and spending patterns:

### Clusters Overview

- **Cluster 0 (Blue)**: High annual income, high spending score.
- **Cluster 1 (Orange)**: Low annual income, low spending score.
- **Cluster 2 (Green)**: High annual income, low spending score.
- **Cluster 3 (Red)**: Low annual income, high spending score.
- **Cluster 4 (Purple)**: Average annual income, average spending score.

### Most Receptive Clusters

1. **Cluster 3 (Red)**:
   - **Characteristics**: Low annual income but high spending score.
   - **Marketing Potential**: Highly engaged despite lower income. Target with affordable luxury or aspirational products.

2. **Cluster 0 (Blue)**:
   - **Characteristics**: High annual income and high spending score.
   - **Marketing Potential**: Ideal for high-end or premium products. Focus on quality, exclusivity, or status.

### Least Receptive Clusters

1. **Cluster 2 (Green)**:
   - **Characteristics**: High annual income but low spending score.
   - **Marketing Potential**: More conservative spenders. Emphasize value, practicality, or long-term benefits.

2. **Cluster 1 (Orange)**:
   - **Characteristics**: Low annual income and low spending score.
   - **Marketing Potential**: Least likely to respond to marketing efforts. Consider budget-friendly products if targeting this segment.

### Marketing Strategies

1. **For Cluster 3 (Red)**:
   - Maintain engagement with aspirational yet affordable products.
   - Emphasize value and experience.
   - Implement loyalty programs and targeted promotions.

2. **For Cluster 0 (Blue)**:
   - Introduce exclusive or limited-edition products.
   - Focus on luxury experiences and status.
   - Offer high-touch services like personalized marketing or concierge services.

3. **For Cluster 2 (Green)**:
   - Highlight cost-effectiveness, quality, and long-term benefits.
   - Introduce warranties, trials, or satisfaction guarantees to reduce perceived risk.

4. **For Cluster 1 (Orange)**:
   - If targeting, offer lower-cost products, discounts, or payment plans.
   - Communicate how products can improve quality of life without large financial outlay.

By tailoring marketing strategies to the specific characteristics and needs of each cluster, businesses can improve engagement and increase the effectiveness of their campaigns.
 
