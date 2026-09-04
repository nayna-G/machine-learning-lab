# Machine Learning Lab

A practical collection of machine learning experiments implemented using Python, NumPy, Pandas, Matplotlib, scikit-learn, and Jupyter Notebook.

The repository covers fundamental machine learning techniques including regression, classification, regularization, parameter estimation using Maximum Likelihood Estimation (MLE) and Maximum A Posteriori (MAP), probabilistic modeling, and text classification across seven experiments.

---

## Course Objective

To gain practical experience with fundamental machine learning techniques by implementing, training, evaluating, and comparing different machine learning models using real-world datasets.

---

## Experiments

| # | Experiment | Dataset | Key Tasks & Concepts |
|---|---|---|---|
| **01** | [Linear Regression](./01_linear_regression.ipynb) | California Housing | Gradient Descent, Normal Equation, MSE, R², fitted-line visualization |
| **02** | [Polynomial Regression](./02_polynomial_regression.ipynb) | Auto MPG | Polynomial Features, varying degrees, Linear vs Polynomial Regression, MSE, R² |
| **03** | [Ridge & Lasso Regression](./03_ridge_lasso_regression.ipynb) | Diabetes | L1/L2 Regularization, Cross-Validation, Hyperparameter Tuning, model comparison |
| **04** | [Logistic Regression — MLE & MAP](./04_logistic_regression_mle_map.ipynb) | Breast Cancer Wisconsin | MLE, MAP, L1/L2 Regularization, parameter estimation and comparison |
| **05** | [Multinomial MLE & MAP](./05_multinomial_mle_map.ipynb) | 20 Newsgroups | Multinomial MLE, MAP, Dirichlet Priors, effect of different priors |
| **06** | [Logistic Regression — Feature Scaling](./06_logistic_regression_scaling.ipynb) | Pima Indians Diabetes | Binary Classification, Feature Scaling, Accuracy, Precision, Recall, F1-score |
| **07** | [Naïve Bayes Classification](./07_naive_bayes.ipynb) | 20 Newsgroups | Multinomial Naïve Bayes, Bernoulli Naïve Bayes, Text Classification, Accuracy, F1-score |

---

## Concepts Covered

### Regression

- Linear Regression
- Polynomial Regression
- Gradient Descent
- Normal Equation
- Ridge Regression
- Lasso Regression
- L1 Regularization
- L2 Regularization

### Probabilistic Modeling

- Maximum Likelihood Estimation (MLE)
- Maximum A Posteriori Estimation (MAP)
- Multinomial Distributions
- Dirichlet Priors
- Prior-based parameter estimation

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

### Model Evaluation

- Mean Squared Error (MSE)
- R-squared (R²)
- Accuracy
- Precision
- Recall
- F1-score

---

## Tech Stack

- **Language:** Python 3
- **Environment:** Jupyter Notebook / JupyterLab
- **Libraries:** NumPy, Pandas, Matplotlib, scikit-learn

---

## Dependencies

The required Python packages are listed in `requirements.txt`.

```text
numpy
pandas
matplotlib
scikit-learn
jupyter
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd machine-learning-lab
```

### 2. Create a Virtual Environment

Creating a virtual environment keeps the project dependencies isolated from other Python projects.

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

#### Windows — Command Prompt

```bash
python -m venv venv
venv\Scripts\activate
```

#### Windows — PowerShell

```bash
python -m venv venv
.\venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

Upgrade pip:

```bash
python -m pip install --upgrade pip
```

Install the required packages:

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter

To launch Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, JupyterLab can be launched using:

```bash
jupyter lab
```

Open any experiment notebook to view the implementation, results, visualizations, and analysis.

---

## Datasets

The experiments use the following standard machine learning datasets:

| Dataset | Experiment |
|---|---|
| **California Housing** | Linear Regression |
| **Auto MPG** | Polynomial Regression |
| **Diabetes** | Ridge & Lasso Regression |
| **Breast Cancer Wisconsin** | Logistic Regression using MLE & MAP |
| **20 Newsgroups** | Multinomial MLE/MAP and Naïve Bayes |
| **Pima Indians Diabetes** | Logistic Regression with Feature Scaling |

Datasets are loaded programmatically where possible and are not stored directly in the repository.

---

## Experiment Workflow

The notebooks generally follow a common machine learning workflow:

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Selection / Transformation
   ↓
Train-Test Split
   ↓
Feature Scaling (where applicable)
   ↓
Model Training
   ↓
Prediction
   ↓
Evaluation
   ↓
Model Comparison
   ↓
Analysis
```

Additional techniques such as cross-validation, hyperparameter tuning, and prior selection are applied where required by the experiment.

---

## Model Evaluation

Different evaluation metrics are used depending on the type of machine learning problem.

### Regression

- **Mean Squared Error (MSE)**
- **R-squared (R²)**

### Classification

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

---

## Repository Structure

```text
machine-learning-lab/
│
├── 01_linear_regression.ipynb
├── 02_polynomial_regression.ipynb
├── 03_ridge_lasso_regression.ipynb
├── 04_logistic_regression_mle_map.ipynb
├── 05_multinomial_mle_map.ipynb
├── 06_logistic_regression_scaling.ipynb
├── 07_naive_bayes.ipynb
│
├── README.md
├── requirements.txt

```

---

## Focus

The experiments focus on practical implementation and evaluation of machine learning techniques, including parameter estimation, regularization, preprocessing, model comparison, and performance analysis.

The notebooks emphasize understanding the underlying machine learning techniques rather than treating models purely as black-box APIs.
