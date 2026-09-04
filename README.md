# Machine Learning Lab

Implementation and experimentation of fundamental machine learning techniques using Python, NumPy, Pandas, Matplotlib, and scikit-learn.

The repository covers regression, classification, regularization, MLE/MAP estimation, probabilistic modeling, and text classification across seven experiments.

## Experiments

| #  | Experiment                            | Dataset                 | Techniques                                           |
| -- | ------------------------------------- | ----------------------- | ---------------------------------------------------- |
| 01 | Linear Regression                     | California Housing      | Gradient Descent, Normal Equation                    |
| 02 | Polynomial Regression                 | Auto MPG                | Polynomial Features, Linear vs Polynomial Regression |
| 03 | Ridge & Lasso Regression              | Diabetes                | L1/L2 Regularization, Cross-Validation               |
| 04 | Logistic Regression — MLE & MAP       | Breast Cancer Wisconsin | MLE, MAP, L1/L2 Regularization                       |
| 05 | Multinomial MLE & MAP                 | 20 Newsgroups           | Multinomial Estimation, Dirichlet Priors             |
| 06 | Logistic Regression — Feature Scaling | Pima Indians Diabetes   | Scaling, Binary Classification                       |
| 07 | Naïve Bayes Classification            | 20 Newsgroups           | Multinomial NB, Bernoulli NB, Text Classification    |

## Concepts

### Regression

* Linear Regression
* Polynomial Regression
* Gradient Descent
* Normal Equation
* Ridge Regression
* Lasso Regression
* L1/L2 Regularization

### Probabilistic Modeling

* Maximum Likelihood Estimation (MLE)
* Maximum A Posteriori Estimation (MAP)
* Dirichlet Priors
* Multinomial Distributions

### Classification

* Logistic Regression
* Multinomial Naïve Bayes
* Bernoulli Naïve Bayes
* Binary Classification

### Model Development

* Data preprocessing
* Feature transformation
* Feature scaling
* Train/test splitting
* Cross-validation
* Hyperparameter tuning
* Model comparison

### Evaluation

* Mean Squared Error (MSE)
* R²
* Accuracy
* Precision
* Recall
* F1-score

## Repository Structure

```text
machine-learning-lab/
├── notebooks/
│   ├── 01_linear_regression.ipynb
│   ├── 02_polynomial_regression.ipynb
│   ├── 03_ridge_lasso.ipynb
│   ├── 04_logistic_mle_map.ipynb
│   ├── 05_multinomial_mle_map.ipynb
│   ├── 06_logistic_scaling.ipynb
│   └── 07_naive_bayes.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* scikit-learn
* Jupyter

## Running the Notebooks

Install the dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

Open any notebook under `notebooks/` and run the cells.

## Datasets

The experiments use standard machine learning datasets including:

* California Housing
* Auto MPG
* Diabetes
* Breast Cancer Wisconsin
* Pima Indians Diabetes
* 20 Newsgroups

Datasets are loaded programmatically where practical and are not committed to the repository.

## Purpose

This repository documents practical implementation and evaluation of core machine learning methods, with emphasis on understanding the underlying techniques rather than treating models as black-box APIs.
