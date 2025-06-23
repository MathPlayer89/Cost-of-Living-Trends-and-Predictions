# Cost of Living Trends and Predictions

A data science project analyzing cost-of-living trends across U.S. counties using exploratory data analysis, regression modeling, and clustering segmentation. This comprehensive analysis is designed to uncover regional disparities, predict cost changes, and identify groups of counties (or households) with similar cost structures.

## Project Overview

This project investigates cost-of-living trends by carefully examining a rich dataset containing various expense categories and economic indicators. The workflow spans from initial data exploration and cleaning, to building predictive regression models, and finally to applying clustering techniques to segment the data. The insights obtained are valuable for understanding regional affordability, economic planning, and targeting policy or business interventions.

## Objectives

- **Exploratory Data Analysis (EDA):**  
  - Clean and preprocess the data (handling missing values, log transformations, categorical encoding, and feature scaling).  
  - Visualize key distributions and identify correlations among variables.

- **Regression Modeling:**  
  - Develop predictive models that estimate future cost shifts using economic indicators.  
  - Evaluate model performance using statistical and error metrics, and identify significant cost drivers (e.g., food, transportation, healthcare).

- **Clustering Analysis:**  
  - Apply both K-Means and Hierarchical clustering techniques to group counties (or households) with similar cost structures.  
  - Use dimension reduction (PCA) for visualization of cluster structures.  
  - Profile each cluster by analyzing both mean and median values of key variables, to capture nuances in cost patterns and demographic factors.

## Dataset

- **Source:** US Cost of Living Dataset (1877 Counties)  
- **Key Features:**  
  - Expense categories: housing, food, transportation, healthcare, childcare, and taxes  
  - Metro vs. non-metro classification (isMetro)  
  - Socioeconomic indicators: Median family income (with log-transformed values to normalize skewness)  
  - Other derived features used during preprocessing and analysis

## Methodology

### 1. Data Preprocessing & Exploratory Analysis
- **Data Cleaning:**  
  - Handling missing values, correcting inconsistencies, and removing redundant features.
- **Feature Engineering:**  
  - Log scaling for variables such as housing cost, taxes, and median family income.
  - Converting categorical data (e.g., metro status, region) into numerical features.
- **EDA:**  
  - Plotting distributions, examining correlations, and visualizing patterns across cost components.

### 2. Regression Modeling
- **Model Development:**  
  - Building regression models to predict cost-of-living adjustments across counties.
- **Evaluation:**  
  - Assessing model performance using metrics such as RMSE, R², and p-values.
- **Interpretation:**  
  - Identifying key cost drivers like food cost and transportation expenses that significantly impact overall costs.

### 3. Clustering Analysis
- **K-Means Clustering:**  
  - Segmenting the data into six clusters based on scaled features.
  - Using the Elbow Method and silhouette scores to validate the optimal number of clusters.
- **Hierarchical Clustering:**  
  - Building a dendrogram to explore the data’s nested structure.
  - Using Agglomerative Clustering to assign cluster labels (again using six clusters for consistency).
- **Visualization & Profiling:**  
  - Applying PCA to reduce dimensions and visualize clusters.
  - Profiling clusters using both mean and median statistics to understand key differences in spending patterns, household sizes, and demographic factors.

## Technologies Used

- **Programming Language:** Python  
- **Primary Libraries:**  
  - **pandas & numpy:** Data manipulation and numerical operations  
  - **scikit-learn:** Model building, clustering, PCA, and evaluation  
  - **matplotlib & seaborn:** Data visualization and plotting  
  - **statsmodels:** Regression analysis and statistical inference

## Conclusion

By combining rigorous preprocessing, regression modeling, and clustering techniques, this project provides a deep understanding of cost-of-living trends across U.S. counties. The clustering segments reveal distinct groups that differ not only in their expense profiles but also in socioeconomic characteristics. This layered analysis supports actionable insights for both public policy formation and targeted business strategies.



