# Mall Customer Segmentation and Customer Analytics

## Overview

This project performs customer segmentation using Exploratory Data Analysis (EDA) and K-Means Clustering to identify distinct customer groups based on demographic and spending behavior. The analysis provides valuable business insights that can support personalized marketing strategies and customer targeting.

---

## Objectives

- Explore customer demographic and spending behavior.
- Perform exploratory data analysis (EDA).
- Visualize customer distributions and relationships.
- Apply K-Means clustering for customer segmentation.
- Determine the optimal number of clusters using the Elbow Method.
- Generate business insights from the identified customer segments.

---

## Dataset

The dataset contains customer information collected from a shopping mall, including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration

- Loaded the dataset.
- Inspected data structure.
- Checked feature distributions.
- Reviewed data types.

---

### 2. Exploratory Data Analysis

Performed both univariate and bivariate analysis.

#### Univariate Analysis

- Distribution of Age
- Distribution of Annual Income
- Distribution of Spending Score

#### Gender Analysis

Compared customer distributions by gender using:

- KDE Plots
- Box Plots
- Distribution Plots

---

### 3. Correlation Analysis

- Pair Plot
- Correlation Matrix
- Heatmap
- Grouped statistical summaries

---

### 4. Customer Segmentation

Implemented K-Means clustering using three different approaches:

#### Income Clustering

Segmented customers based on Annual Income.

#### Income & Spending Clustering

Clustered customers using:

- Annual Income
- Spending Score

Identified five meaningful customer groups.

#### Multivariate Clustering

Applied clustering using:

- Age
- Annual Income
- Spending Score
- Gender

Data was standardized using StandardScaler before clustering.

---

### 5. Model Evaluation

Used the Elbow Method to determine the optimal number of clusters by analyzing inertia values.

---

### 6. Data Visualization

Created visualizations including:

- Distribution Plots
- KDE Plots
- Box Plots
- Scatter Plots
- Pair Plots
- Heatmap
- Cluster Visualization
- Cluster Centers

---

## Business Insights

- Identified high-income, high-spending customers.
- Distinguished high-income customers with low spending behavior.
- Recognized low-income customers with high spending tendencies.
- Segmented average customers for targeted marketing.
- Enabled customer profiling to support business decision-making.

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Customer Analytics
- Customer Segmentation
- Unsupervised Machine Learning
- K-Means Clustering
- Data Visualization
- Feature Analysis
- Correlation Analysis
- StandardScaler
- Business Intelligence

---

## Future Improvements

- Compare K-Means with Hierarchical Clustering and DBSCAN.
- Evaluate cluster quality using Silhouette Score.
- Build an interactive dashboard using Plotly or Streamlit.
- Deploy the project as a web application.

---

## Author

Salma Emad

Machine Learning Engineer | Data Scientist
