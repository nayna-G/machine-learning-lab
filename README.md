# Machine Learning Lab

Implementation and experimentation of fundamental machine learning techniques using Python, NumPy, Pandas, Matplotlib, and scikit-learn.

The repository covers regression, regularization, probabilistic parameter estimation, classification, and text classification across seven experiments.

## Experiments

| # | Experiment | Dataset | Key Techniques |
|---|---|---|---|
| 01 | [Linear Regression](./01_linear_regression.ipynb) | California Housing | Gradient Descent, Normal Equation, MSE, R² |
| 02 | [Polynomial Regression](./02_polynomial_regression.ipynb) | Auto MPG | Polynomial Features, Model Comparison, MSE, R² |
| 03 | [Ridge & Lasso Regression](./03_ridge_lasso_regression.ipynb) | Diabetes | L1/L2 Regularization, Cross-Validation, Hyperparameter Tuning |
| 04 | [Logistic Regression — MLE & MAP](./04_logistic_regression_mle_map.ipynb) | Breast Cancer Wisconsin | MLE, MAP, L1/L2 Regularization |
| 05 | [Multinomial MLE & MAP](./05_multinomial_mle_map.ipynb) | 20 Newsgroups | MLE, MAP, Dirichlet Priors |
| 06 | [Logistic Regression — Feature Scaling](./06_logistic_regression_scaling.ipynb) | Pima Indians Diabetes | Feature Scaling, Binary Classification |
| 07 | [Naïve Bayes Classification](./07_naive_bayes.ipynb) | 20 Newsgroups | Multinomial NB, Bernoulli NB, Text Classification |

## Concepts

### Regression

- Linear Regression
- Polynomial Regression
- Gradient Descent
- Normal Equation
- Ridge Regression
- Lasso Regression
- L1/L2 Regularization

### Probabilistic Modeling

- Maximum Likelihood Estimation (MLE)
- Maximum A Posteriori Estimation (MAP)
- Multinomial Distributions
- Dirichlet Priors

### Classification

- Logistic Regression
- Multinomial Naïve Bayes
- Bernoulli Naïve Bayes
- Binary Classification
- Text Classification

### Model Development

- Data Preprocessing
- Feature Transformation
- Feature Scaling
- Train/Test Splitting
- Cross-Validation
- Hyperparameter Tuning
- Model Comparison

### Evaluation

- Mean Squared Error (MSE)
- R²
- Accuracy
- Precision
- Recall
- F1-score

## Tech Stack

- Python
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Datasets

The experiments use the following datasets:

- California Housing
- Auto MPG
- Diabetes
- Breast Cancer Wisconsin
- Pima Indians Diabetes
- 20 Newsgroups

Datasets are loaded programmatically where possible and are not stored directly in the repository.

## Repository Structure

```text
machine-learning-lab/
├── 01_linear_regression.ipynb
├── 02_polynomial_regression.ipynb
├── 03_ridge_lasso_regression.ipynb
├── 04_logistic_regression_mle_map.ipynb
├── 05_multinomial_mle_map.ipynb
├── 06_logistic_regression_scaling.ipynb
├── 07_naive_bayes.ipynb
├── README.md
├── requirements.txt
