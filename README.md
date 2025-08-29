
# Competition DengAI: Predicting Disease Spread - ML Non Supervised Learning

## Problem Statement

The goal is to predict the total_cases label for each (city, year, weekofyear) in the test set. There are two cities, San Juan and Iquitos, with test data for each city spanning 5 and 3 years respectively. You will make one submission that contains predictions for both cities. The data for each city have been concatenated along with a city column indicating the source: sj for San Juan and iq for Iquitos. The test set is a pure future hold-out, meaning the test data are sequential and non-overlapping with any of the training data. Throughout, missing values have been filled as NaNs.

## Objectives

The general aim is predict the number of dengue cases reported each week in San Juan (Puerto Rico) and Iquitos (Peru) using environmental data collected by US Federal Government agencies.

The specific aim of this part of the project is to identify relevant patterns and features to improve the prediction of dengue cases using ML models.





## Data source

Raw Data provided by 
[DrivenData](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/)



## Tech stack

- **Google colab (Jupyter Notebook)**
- **Python**
- **Libraries**: Pandas, Numpy, io, Math, Matplotlib, Seaborn,  Scikit-learn & SciPy

## Experimentation Phases
This project explores various unsupervised machine learning methods to identify patterns and group similar objects within a dataset. The experimental process is structured into three key sections:

### Data Exploration
The objective of this phase is to familiarise oneself with the structure, quality and initial characteristics of the dataset. An exploratory data analysis (EDA) will be performed to familiarise us with the data, identify any missing or outlier values, and conduct an initial descriptive statistical analysis. This will serve as a basis for subsequent steps.

### Feature Preparation
The focus here is on cleaning and transforming the data to make it suitable for clustering algorithms. This involves addressing missing values and outliers that are identified during the exploratory phase. New and relevant variables are created through **feature engineering**, while **feature selection** eliminates those that do not add value, ensuring the data is optimised and clean for modelling.

### Clustering
This is the core of the project, in which various unsupervised clustering algorithms are employed to identify natural clusters within the prepared dataset. The results of four different techniques are then compared, primarily using the Silhouette metric and metrics unique to each model to inform the final decision.
- Agglomerative hierarchical clustering
- K-means
- DBSCAN
- GMM (Gaussian Mixture Model)

Finally, significant conclusions are drawn about the patterns and relationships found in the data, and recommendations are made for future work, based on the comparison of metrics and visualisation of the clusters identified for each model.

---

Thank you for visiting this repository! If you find this project useful, please feel free to leave a star ⭐️.




