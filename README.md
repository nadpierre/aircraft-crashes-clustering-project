# Aircraft Crashes Clustering Project

![Image of the crash of the flight JL123 in August 12th 1985](https://www.baaa-acro.com/sites/default/files/crash/images/JA8119-9.jpg)

## Description

This project analyzes and clusters aircraft accidents from 1970 to the present to uncover patterns and trends. By leveraging clustering techniques, the goal is to identify common factors contributing to accidents, such as location, time period and aircraft type. Understanding these patterns can provide insights into aviation safety and help mitigate future risks.

## Dataset

The data comes from the [Bureau of Aircraft Accidents Archives (BAAA)](https://www.baaa-acro.com/) and the [Aviation Safety Network](https://asn.flightsafety.org/).

## Libraries used

- BeautifulSoup
- geopy
- matplotlib
- pandas
- requests
- scipy
- seaborn
- sklearn
- yellowbrick

## Methods & Models

To analyze and cluster aircraft accidents, this project follows these steps:

1. **Data collection:**

   Collected through web scraping from the BAAA and ASN website.

2. **Data Preparation:**

   Cleaned and formatted the dataset by handling missing values and inconsistencies.

3. **Exploratory Data Analysis (EDA):**

   Visualized accident trends over time using time-series plots, barplots and pie plots.

4. **Data Preprocessing:**

   Encoded string variables using Ordinal Encoding and One Hot Encoding, and standardized data.

5. **Feature Engineering:**

   - Collapsed the unique values of string columns to reduce cardinality.
   - Applied Pricipal Component Analysis (PCA) to reduce dimensionality and improve clustering accuracy.

6. **Clustering Models:**

   - Implemented K-Means to group accidents based on similarities.
   - Tested DBSCAN for density-based clustering to detect anomalies and unusual accident clusters.
   - Evaluated different cluster numbers using elbow method and silhouette score.

7. **Insights & Interpretation:**

   Analyzed the characteristics of each cluster to uncover accident trends and contributing factors.

## Results

## Featured Notebooks

- [Data Collection and Cleaning](data_collection_and_cleaning.ipynb)
- [Data Analysis And Visualization](data_analysis.ipynb)
- [Data Preprocessing and Modeling](data_modeling.ipynb)
