# Sampling Techniques and Machine Learning Models  

This repository contains my implementation of various sampling techniques applied to a credit card dataset as part of the **Sampling Assignment**. The project explores the impact of different sampling techniques on machine learning model performance, with the goal of identifying the most effective method for improving accuracy.

## Project Overview  

The project involves:  
- **Balancing the Dataset**: Addressing class imbalance in the dataset.  
- **Sampling Methods**: Applying five sampling techniques:  
  1. Random Sampling  
  2. Stratified Sampling  
  3. Systematic Sampling  
  4. Cluster Sampling  
  5. Oversampling  
- **Model Evaluation**: Training and testing five machine learning models:  
  1. Logistic Regression  
  2. Decision Tree  
  3. Random Forest  
  4. Support Vector Machine (SVM)  
  5. K-Nearest Neighbors (KNN)  
- **Result Analysis**: Comparing model performance to determine the best sampling technique for each model.

## Results  

The table below summarizes the accuracy of each model for all sampling techniques:

| **Sampling Technique** | **Model**             | **Accuracy**     |  
|-------------------------|-----------------------|------------------|  
| Random Sampling         | Logistic Regression  | 0.9444           |  
| Random Sampling         | Decision Tree        | 0.9111           |  
| Random Sampling         | Random Forest        | 0.9444           |  
| Random Sampling         | SVM                  | 0.9444           |  
| Random Sampling         | KNN                  | 0.9444           |  
| Stratified Sampling     | Logistic Regression  | 0.9859           |  
| Stratified Sampling     | Decision Tree        | 0.9507           |  
| Stratified Sampling     | Random Forest        | 0.9929           |  
| Stratified Sampling     | SVM                  | 0.9929           |  
| Stratified Sampling     | KNN                  | 0.9929           |  
| Systematic Sampling     | Logistic Regression  | 1.0000           |  
| Systematic Sampling     | Decision Tree        | 1.0000           |  
| Systematic Sampling     | Random Forest        | 1.0000           |  
| Systematic Sampling     | SVM                  | 1.0000           |  
| Systematic Sampling     | KNN                  | 1.0000           |  
| Cluster Sampling        | Logistic Regression  | 1.0000           |  
| Cluster Sampling        | Decision Tree        | 1.0000           |  
| Cluster Sampling        | Random Forest        | 1.0000           |  
| Cluster Sampling        | SVM                  | 1.0000           |  
| Cluster Sampling        | KNN                  | 1.0000           |  
| Oversampling            | Logistic Regression  | 0.9083           |  
| Oversampling            | Decision Tree        | 0.9869           |  
| Oversampling            | Random Forest        | 1.0000           |  
| Oversampling            | SVM                  | 0.6856           |  
| Oversampling            | KNN                  | 0.9847           |  

### Key Insights:  
- **Systematic Sampling** and **Cluster Sampling** resulted in perfect accuracy (1.0000) across all models.  
- **Stratified Sampling** also performed exceptionally well, with high accuracy for all models.  
- **Oversampling** was effective for Decision Tree, Random Forest, and KNN but showed lower performance for SVM.  
- **Random Sampling** achieved consistent accuracy across all models, but it was lower compared to other methods.  


