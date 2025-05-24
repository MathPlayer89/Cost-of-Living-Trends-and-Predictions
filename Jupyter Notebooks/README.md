### **Notebook Breakdown**
**cost_of_living_cleaning.ipynb:** Contains all data cleaning and preprocessing steps to prepare the dataset for **Exploratory Data Analysis (EDA)**.  
**cost_of_living_EDA.ipynb:** Focuses on uncovering trends, correlations, and key insights through **statistical summaries & visualizations**.  
**cost_of_living_preprocessing.ipynb:** Prepares the dataset for **modeling**, handling feature engineering, scaling, and transformations.  
**cost_of_living_regression.ipynb** Implements **regression models** to understand how different cost factors impact affordability.  
**cost_of_living_clustering.ipynb** Applies **clustering models** to identify cost-based groupings and patterns.  

Additionally, a **master notebook** consolidates **all steps into a single streamlined notebook** for easy reference:  
**cost_of_living_master.ipynb:** Holds **all code & analyses** from the project in one place.

---

## Requirements
### **Tools & Libraries**
Ensure the following Python libraries are installed before running the notebooks:
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import re
from scipy.stats.mstats import winsorize
