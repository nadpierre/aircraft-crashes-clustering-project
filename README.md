# Aircraft Crashes Clustering Project

## Description

This project analyzes and clusters aircraft accidents from 1918 to the present to uncover patterns and trends. By leveraging clustering techniques, the goal is to identify common factors contributing to accidents, such as location, time period and aircraft type. Understanding these patterns can provide insights into aviation safety and help mitigate future risks.

## Dataset

- [Bureau of Aircraft Accidents Archives (BAAA)](https://www.baaa-acro.com/)
- [Skybrary](https://skybrary.aero/)

## Libraries used

- beautifulsoup4
- pandas
- requests
- thefuzz

## Methods & Models

- Data collected through web scraping
- Aircraft details joined with approximate string matching
- Data Modeling
  - K-Means
  - Hierarchical clustering

## Results

## Future Improvements

The circumstances, probable causes and reports were not collected in the dataset, as there are long texts and can't be preprocessed easily for modeling. It would be interesting to find a way to summarize those into categories (ex: Mechanical failure, human error, bad weather, etc.) to gain valuable insights.

## Featured Notebooks

- [Data Collection and Cleaning](data_collection_and_cleaning.ipynb)
- [Data Analysis](data_analysis.ipynb)
- [Data Modeling](data_modeling.ipynb)
