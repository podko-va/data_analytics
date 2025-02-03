# Data Analytics with Pandas and Visualization in Google Colab
## Ссылки

[File Untitled6.ipynb](https://github.com/podko-va/data_analytics/blob/main/Untitled6.ipynb)

## Overview
This project is a **Google Colab notebook** that demonstrates **data analytics and visualization** using the California housing dataset (`california_housing_train.csv`). The notebook utilizes `pandas`, `matplotlib`, and `seaborn` to explore dependencies, trends, and correlations in the dataset.

## Features
- **Data Loading & Preprocessing:** Reads the dataset into a Pandas DataFrame and performs basic cleaning.
- **Descriptive Statistics:** Computes statistical summaries such as mean, median, standard deviation, and correlations.
- **Data Visualization:** Uses various visualization techniques to understand data relationships, trends, and distributions.
- **Exploratory Data Analysis (EDA):** Includes scatter plots, boxplots, heatmaps, and histogram analysis.
- **Regression & Correlation Analysis:** Investigates dependencies between features using scatter plots and regression lines.
- **Geospatial Analysis:** Visualizes housing data based on longitude and latitude.

## Requirements
Ensure the following libraries are installed in your Colab environment:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Usage
1. Open Google Colab and upload `california_housing_train.csv` (if not present in `sample_data/`).
2. Run the notebook cells to analyze the dataset.
3. Customize the plots and analysis according to your requirements.

## Key Visualizations
- **Histogram:** Distribution of numerical features.
- **Heatmap:** Correlation between different attributes.
- **Scatter Plot:** Relationship between `median_income` and `median_house_value`.
- **Box Plot:** Identifies outliers and spread in numerical features.
- **Hexbin Plot:** Density visualization for large datasets.

## Example: Correlation Matrix
```python
plt.figure(figsize=(10, 6))
sns.heatmap(df.corr(), annot=True, cmap="coolwarm", fmt=".2f", linewidths=1)
plt.title("Correlation Matrix")
plt.show()
```

## Conclusion
This Colab notebook provides a foundation for **data analysis and visualization** in Python using `pandas`, `matplotlib`, and `seaborn`. It helps identify trends, patterns, and relationships in the dataset, which can be useful for **predictive modeling** and further machine learning applications.

## License
This project is open-source and available under the MIT License.

