# Parameter-Optimization-SVM
Name: Prarthana Samal 

Class: 3C25

Roll Number: 102383015

## Overview
This project focuses on optimizing Support Vector Machine (SVM) parameters using Bayesian Optimization on the [Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset) (UCI ML Repository ID: 468). The objective is to enhance multi-class classification performance through iterative hyperparameter tuning and model evaluation.

## Dataset Description
The Online Shoppers Purchasing Intention Dataset contains anonymized session-level data from an e-commerce website. It is designed to predict whether a user will complete a purchase based on their browsing behavior and session attributes.
- Features: 17
- Total Instances: 12,330

## Methodology 
1. **Data Loading:** Used the Online Shoppers Purchasing Intention Dataset from UCI.
2. **Preprocessing:** Encoded categorical features and split data into features and target.
3. **Sampling:** Created 10 random train-test splits (70% train, 30% test).
4. **Model:** Applied SVM using the NuSVC classifier.
5. **Optimization:** Tuned kernel, nu, and tol using Bayesian Optimization (100 iterations/sample).
6. **Evaluation:** Recorded best accuracy and parameters for each sample.
7. **Analysis:** Identified the highest-performing sample and visualized optimization progress.

## Result Table
![Screenshot 2025-04-19 120233](https://github.com/user-attachments/assets/d563708e-b13e-4751-b1b9-e52b177f00bb)

- Bayesian Optimization was used to tune SVM hyperparameters over 10 randomized data splits (70% train / 30% test) on the Online Shoppers Purchasing Intention Dataset.

- The highest accuracy was 0.894025, achieved on Sample 1.




## Result Graph
![graph](https://github.com/user-attachments/assets/ce5621ba-588e-4bda-847f-9344edb162ea)
