# ZillowDataImputation

## Intro

This project aims to evaluate the effectiveness four Machine Learning Models -- **Bayesian Ridge**, **K-Nearest Neighbor Regression**, **Random Forests Regression**, **Artificial Neural Network Regression** -- in applying MICE (Multivariate Imputation By Chained Equations) on large sparse data.


## Motivation

Machine learning is a data driven discipline which requires processing a high amount of data. High-quality datasets should be large enough, with relevant data and crucial features for accurate modeling. They must also be consistent, ensuring reliability and stability without significant errors or inconsistencies that could mislead. One challenge in real-world Machine Learning applications is dealing with missing data in datasets. A common strategy to address this is data imputation, which involves replacing missing values with substitute values to retain the majority of the data and information in the dataset. In this project, I explored multivariate imputation with four widely used Machine Learning models, i.e. **Bayesian Ridge**, **K-Nearest Neighbor Regression**, **Random Forests Regression**, **Artificial Neural Network Regression**, on sparse datasets and compare their performance using standardized metrics.

## Overview

![Image Alt text](/Image/Overview.png)

## EDA

Dataset: Zillow Housing 2016

![Image Alt text](/Image/Dataset.png)

Figure 1. Correlation Matrix

## Experimental Results

### Without Dropping Perfect Correlated Features

![Image Alt text](/Image/Result1.png)

### Dropping Perfect Correlated Features**

![Image Alt text](/Image/Result2.png)


### Performance(Running time)

![Image Alt text](/Image/Time.png)

## Conclusion

- MICE is a robust technique, while Single Imputation also yields sound results. The choice of imputation strategy depends on the dataset characteristics. There is no universally optimal approach for all datasets. 

- Data pre-processing and hyperparameter tuning are crucial not only for optimizing machine learning models but also for selecting an effective imputation strategy.

- Hyperparameter tuning for MICE can be time-consuming, particularly depending on the which imputation algorithm is selected.

- If there are highly correlated features with the target variable, faster imputation methods like Mean Imputation or Bayesian Imputation would be sufficient.

