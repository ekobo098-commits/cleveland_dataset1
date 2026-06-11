# cleveland_dataset1
# Bayesian Optimization-Based Benchmarking of Classical Machine Learning Models for Heart Disease Prediction

## Overview

This project presents a comparative benchmarking framework for heart disease prediction using classical machine learning algorithms combined with Bayesian hyperparameter optimization. The objective is to evaluate the impact of efficient hyperparameter tuning on predictive performance using the Cleveland Heart Disease Dataset.

## Features

* Exploratory Data Analysis (EDA)
* Data preprocessing and feature engineering
* Bayesian hyperparameter optimization
* Multiple machine learning models:

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * XGBoost
* Performance evaluation using:

  * Accuracy
  * Sensitivity
  * Specificity
  * F1-Score
  * AUC-ROC
* ROC curve visualization
* Confusion matrix analysis
* Comparative benchmarking

## Dataset

This project uses the **Cleveland Heart Disease Dataset** available from the UCI Machine Learning Repository.

Dataset:
https://archive.ics.uci.edu/ml/datasets/heart+disease

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Scikit-Optimize
* Matplotlib

## Project Structure

```
heart-disease-prediction/
│
├── heart_disease_prediction.ipynb
├── requirements.txt
├── README.md
├── images/
└── data/
```

## Results

| Model                   | Accuracy             |
| ----------------------- | -------------------- |
| Logistic Regression     | 88.52%               |
| Decision Tree           | 77.05%               |
| Random Forest           | 88.52%               |
| XGBoost                 | 86.89%               |
| Optimized Random Forest | **90.16%**           |
| Optimized XGBoost       | Best AUC: **95.53%** |

Bayesian hyperparameter optimization improved the predictive performance of most models, with the optimized Random Forest classifier achieving the highest overall accuracy.

## Reproducibility

1. Clone the repository.
2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Open and run:

```
heart_disease_prediction.ipynb
```

## Research

This repository accompanies the research paper:

**Bayesian Optimization-Based Benchmarking of Classical Machine Learning Models for Heart Disease Prediction**

## License

This project is released under the MIT License.

## Author

**Sarthak P. Salve**

Contributions, suggestions, and feedback are welcome.
