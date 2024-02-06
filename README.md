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
