# ESG Data Analysis and Clustering Project

## Overview

This project entails a comprehensive data analysis, focusing initially on clustering methodologies to uncover inherent groupings within the ESG dataset. After an extensive initial analysis, I decided to revisit and overhaul the entire analysis process to enhance the insights and outcomes derived from the data.

## Updates

The project is currently undergoing updates to refine the analysis further and incorporate additional data processing techniques. This iterative process is aimed at improving the accuracy and relevance of the clustering results, ensuring the findings are robust and actionable.

## Initial Clustering

Firstly, I restructured the data to aggregate the ESG goals of each company, then applied some NLP methods such as removing stopwords and Tfidf vectorization. Then I applied PCA for dimensionality reduction, and clustered based on the obtained PCA results. Afterwards, the goal is to make a prediction of what cluster a company would belong to, only given the characteristics of the company. I used Optuna for hyperparameter tuning, and classifier algorithms such as Random Forest, Gaussian NB, k-NN, J48 Decision Tree, Multilayer Perceptron, and SVM. Since the dataset was small and unbalanced, I tried oversampling techniques such as SMOTE and random oversampling before performing the classification. So far, the highest accuracy was with Random Forest. However, I will check again after obtaining more data. Currently working on the visualisations.

## Refined Analysis

Recognizing the potential for deeper insights, I have embarked on a comprehensive reevaluation of the dataset and prediction techniques. For this I have used optuna for hyperparameter tuning and various classification algorithms (to predict which cluster a company with certain characteristics would belong to). 

