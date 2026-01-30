# From Customer Segmentation to Predictive Modeling
Classifying Clustered Customers with Random Forest

## Overview

This project extends a customer segmentation task from clustering to **classification**.  
After generating customer segments using clustering, a supervised learning approach was applied to predict customer cluster membership.

The objective is to enable **scalable and real-time customer segmentation** for new data.

---

## Workflow

1. Data splitting (train-test)
2. Classification using Random Forest
3. Model evaluation (baseline)
4. Hyperparameter tuning
5. Evaluation of tuned model
6. Result analysis

---

## Model

- Algorithm: Random Forest Classifier
- Task: Multi-class classification (cluster labels)
- Evaluation metrics:
  - Accuracy
  - Precision
  - Recall
  - F1-Score

---

## Performance

**Before Tuning**
- Accuracy: 0.9509  
- F1-Score: 0.9505  

**After Tuning**
- Accuracy: 0.9598  
- F1-Score: 0.9595  

The tuned model shows consistent improvement with balanced precision and recall across all classes.

---

## Best Parameters

- n_estimators: 300  
- max_depth: None  
- min_samples_split: 2  
- min_samples_leaf: 1  

---

## Key Insight

Combining clustering and classification creates a production-ready pipeline for customer segmentation, enabling scalable personalization and data-driven marketing decision

## Medium

Read this project article on my [Medium](https://medium.com/@anarusdiati/from-customer-segmentation-to-predictive-modeling-6b20de5a3f15)

Let's connect
