# Jupyter Notebook Folder - Cost of Living Trends and Predictions

This folder contains all the Jupyter Notebooks associated with the project. Each notebook represents a distinct phase in our analysis: from data cleaning and exploratory analysis to feature preprocessing, regression modeling, and clustering.

---

## Notebook Breakdown

- **cost_of_living_cleaning.ipynb:**  
  - **Purpose:** Contains all data cleaning and preprocessing steps to prepare the dataset for Exploratory Data Analysis (EDA).  
  - **Details:**  
    - Handles missing values and corrects inconsistencies.
    - Renames columns and standardizes formats.
    - Outputs a cleaned dataset ready for in-depth analysis.

- **cost_of_living_EDA.ipynb:**  
  - **Purpose:** Focuses on uncovering trends, correlations, and key insights through statistical summaries and visualizations.  
  - **Details:**  
    - Generates histograms, box plots, scatter plots, and correlation matrices.
    - Explores distributional properties of cost components.
    - Identifies regional patterns and relationships among variables.

- **cost_of_living_preprocessing.ipynb:**  
  - **Purpose:** Prepares the dataset for modeling by handling feature engineering, scaling, and transformations.  
  - **Details:**  
    - Performs log transformations on skewed variables (e.g., housing cost, taxes, and median family income).
    - Encodes categorical variables and conducts feature scaling using methods such as MinMax scaling.
    - Drops redundant variables, renames columns, and standardizes formats.
    - Creates derived features that enhance the regression and clustering models.

- **cost_of_living_regression.ipynb:**  
  - **Purpose:** Implements regression models to understand how different cost factors impact affordability.  
  - **Details:**  
    - Builds one or multiple regression models.
    - Evaluates model performance using metrics such as R², RMSE, and statistical significance tests.
    - Identifies key cost drivers (e.g., food cost and transportation) that contribute to overall cost-of-living changes.

- **cost_of_living_clustering.ipynb:**  
  - **Purpose:** Applies clustering models to identify cost-based groupings and patterns among the counties/households.  
  - **Details:**  
    - Implements both K-Means and Hierarchical clustering (including visualizations like PCA projections and dendrograms).
    - Uses the Elbow Method and silhouette scores to determine the optimal number of clusters.
    - Profiles clusters by analyzing statistical summaries (mean, median, etc.) of spending categories, metro status, and income levels.

- **cost_of_living_master.ipynb:**  
  - **Purpose:** Consolidates all analysis steps into a single, streamlined notebook.  
  - **Details:**  
    - Integrates data cleaning, EDA, preprocessing, regression analyses, and clustering into one cohesive workflow.
    - Serves as a comprehensive, end-to-end reference for reproducing the full project.
    - Ideal for users who want to understand the complete process without navigating through multiple notebooks.
