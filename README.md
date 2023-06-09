# Parkinson's-Disease-Detection-using-ML-and-DL-in-R

In this research, we suggest using speech features as inputs to a machine learning model for non-invasive, low-cost screening for Parkinson's disease (PD). The nervous system and the organs it controls are at risk from PD, a degenerative neurological illness. Tremors, bradykinesia, tense muscles, altered posture, speech difficulties, and balance issues are all symptoms of Parkinson's disease (PD).

Our findings suggest that utilising PCA on the pre-processed data and the ANN algorithm is the optimal strategy for predicting Parkinson's disease using the provided dataset. We were able to increase the model's precision by using the principal component analysis (PCA) approach to reduce the dataset's dimensionality. In addition, the ANN algorithm outperformed all other machine learning algorithms in terms of accuracy.

## Requirements

1. R 
2. R studio 

## Dataset Used

Link: https://archive.ics.uci.edu/ml/datasets/parkinsons

## Required Packages

```bash
install.packages("ggplot2")
install.packages("dplyr")
install.packages("reshape2")
install.packages("caTools")
install.packages("ROCR")
install.packages("MLmetrics")
install.packages("randomForest")
install.packages("lightgbm")
install.packages("e1071")
install.packages("xgboost")
install.packages("readr")
install.packages("stringr")
install.packages("caret")
install.packages("neuralnet")
install.packages("moments")

```

## Performance Metrics

The Highest accuracy is recievced by ANN after Principal component analysis WHICH IS 97.6%.

## Results

![image](https://user-images.githubusercontent.com/84379934/232119764-cf36aae2-c479-4cf2-b50c-4f73925395c6.png)

