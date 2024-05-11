# Abalone Rings Prediction

<img src = 'https://crystal-shop.co/wp-content/uploads/2022/10/abalone-meaning-abalone-shell-fossil-rock-spiritual-meaning-mineral-crystal-stone-abalone.jpg' />

This repository contains code for the Abalone Rings Prediction Kaggle competition from the Playground Series. The goal of this competition is to predict the age of abalone from various physical measurements.

---

## Competition Overview
* Competition Link: https://www.kaggle.com/competitions/playground-series-s4e4/overview
* Evaluation Metric: Root Mean Squared Logarithmic Error

## Dataset
The dataset for this competition includes both training and test data, which were generated from a deep learning model trained on the Abalone dataset. While feature distributions are close to the original, they are not exactly the same. The dataset is already split into train and test sets. The train set is used to create and train the model, while the test set is used for making predictions and submission.

## Analysis and Feature Engineering
Data analysis and feature engineering have been performed on the dataset.

## Model
Several algorithms have been utilized in the model, including:

* LightGBM
* XGBoost
* CatBoost
* Voting Ensemble Model

Hyperparameters were optimized using the Optuna optimizer.

## Kaggle Submission
The submission has been made on Kaggle, and the score achieved is in the top 15% of all submissions.

## Files Included
* 'train.csv': Training dataset
* 'test.csv': Test dataset
* 'Abalone_Rings_Prediction.ipynb': Jupyter notebook containing the code for data analysis, feature engineering, model building, and evaluation.
* Submissions file for Kaggle competition.

## Contributors
Endrit Mustafa

---

Feel free to contribute by creating issues or pull requests.
