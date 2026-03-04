#  Heart Disease Prediction

### Kaggle Competition \| AUC: **0.95524 (Private LB)** \| Rank: **604 / 4371**

------------------------------------------------------------------------

##  Competition Performance

  Metric                        Score
  ----------------------------- ----------------------------
  **Private Leaderboard AUC**   **0.95524**
  **Public Leaderboard AUC**    0.95377
  **Final Rank**                **604 / 4371** (Top \~14%)

This repository contains my structured experimentation pipeline
developed for the Kaggle competition:

**Playground Series - Season 6, Episode 2: Predicting Heart Disease**

The focus was on disciplined cross-validation, model evolution, and
competitive generalization performance.

------------------------------------------------------------------------

##  Project Objective

Predict the probability of heart disease using structured clinical
features by:

-   Exploring multiple model families
-   Applying deep learning techniques to tabular data
-   Performing hyperparameter optimization
-   Building a robust Out-of-Fold (OOF) validation pipeline
-   Maintaining leaderboard stability

The goal was not just leaderboard score --- but strong validation
methodology and reproducibility.

------------------------------------------------------------------------

##  Models Explored

###  Gradient Boosting

-   XGBoost
-   LightGBM
-   CatBoost

###  Neural Networks

-   Dense Neural Networks (TensorFlow / Keras)
-   Regularization tuning (Dropout, BatchNorm)
-   Depth/width exploration
-   Learning rate scheduling

### Transformers for Tabular Data

-   Representation learning experiments
-   Comparative performance vs GBDTs

------------------------------------------------------------------------

##  Technical Strategy

### 1️ Preprocessing

-   Missing value handling
-   Scaling & normalization
-   Encoding strategies
-   Distribution adjustments

### 2️ Feature Engineering

-   Interaction features
-   Statistical combinations
-   Iterative refinement
-   Feature selection experiments

### 3️ Optimization

-   Hyperparameter tuning with Optuna
-   Early stopping strategies
-   Cross-validation stability monitoring
-   Overfitting mitigation

------------------------------------------------------------------------

##  Validation Framework

To avoid leaderboard overfitting:

-   K-Fold Cross Validation
-   Out-of-Fold (OOF) prediction tracking
-   Consistent AUC comparison across folds
-   Submission pipeline from OOF-trained models

This ensured strong alignment between public and private leaderboard
scores.

------------------------------------------------------------------------

##  Project Structure

    Heart-Disease-Prediction/
    │
    ├── submision_outputs/
    ├── heart-disesase-prediction/
    ├── best_documented_iteration/
    ├── best_performing_iteration_and_submission/
    └── README.md

------------------------------------------------------------------------

##  Tech Stack

-   Python
-   TensorFlow / Keras
-   XGBoost
-   LightGBM
-   CatBoost
-   Optuna
-   Scikit-learn
-   Pandas / NumPy
-   Jupyter Notebook

------------------------------------------------------------------------

##  What This Project Demonstrates

✔ Competitive machine learning workflow
✔ Multi-model experimentation
✔ Deep learning applied to structured tabular data
✔ Strong cross-validation discipline
✔ Hyperparameter optimization pipelines
✔ Clean experiment iteration structure

------------------------------------------------------------------------

##  Competition Citation

Yao Yan, Walter Reade, Elizabeth Park.
*Predicting Heart Disease.*
https://kaggle.com/competitions/playground-series-s6e2, 2026. Kaggle.

------------------------------------------------------------------------

##  Future Improvements

-   Model ensembling (stacking / blending)
-   SHAP-based explainability
-   Feature importance stability analysis
-   Automated experiment tracking (MLflow)
-   Deployment-ready inference pipeline

------------------------------------------------------------------------

##  Author

**Adwait Tagalpalewar**
CSE Student | Machine Learning & AI Enthusiast
Interested in Competitive ML, Deep Learning & Optimization
