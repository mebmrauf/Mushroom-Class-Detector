# Mushroom Class Detector

## Overview
Mushroom classification is crucial in mycology and food safety, as misidentifying toxic mushrooms can have severe consequences. This project uses machine learning to classify mushrooms as **edible** or **poisonous** based on 22 features (e.g., cap shape, surface, odor, habitat). 

The project processes the dataset from the [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/mushroom-classification) and evaluates various models to achieve optimal performance.

## Features
- Dataset Preprocessing: Cleaning and encoding categorical data.
- Feature Scaling: Normalization using MinMaxScaler.
- Dataset Splitting: Stratified random sampling for unbiased evaluation.
- Model Training: Evaluation of Decision Tree, Random Forest, and K-Nearest Neighbors classifiers.
- Metrics: Accuracy, precision, recall, and confusion matrix analysis.

## Dataset
The dataset contains:
- **22 features**, all categorical, converted to numerical values using LabelEncoder.
- **8,124 samples** corresponding to 23 species of gilled mushrooms.
- Target variable: **Edible (0) vs. Poisonous (1)**.
- Balanced classes for unbiased classification.

Source: [UCI Mushroom Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/mushroom-classification).

## Models and Performance
Three machine learning models were trained and tested:
1. **Decision Tree**
2. **Random Forest**
3. **K-Nearest Neighbors (KNN)**

### Results:
- All models achieved **100% accuracy** on the test set.
- Detailed analysis was performed using precision, recall, and confusion matrices.
