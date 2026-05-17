# Machine Learning 101

Hands-on machine learning notebooks covering core supervised learning concepts, from NumPy basics through linear regression, logistic regression, and introductory neural networks.

## Repository Structure

```text
machine-learning-101/
+-- notebooks/
|   +-- 01_linear_regression/
|   +-- 02_logistic_regression/
|   +-- 03_neural_networks/
+-- requirements.txt
+-- README.md
```

## Notebook Index

### 01 Linear Regression

| Notebook | Topic |
| --- | --- |
| [01_numpy_cheat_sheet.ipynb](notebooks/01_linear_regression/01_numpy_cheat_sheet.ipynb) | NumPy fundamentals used in ML workflows |
| [02_linear_regression_lab.ipynb](notebooks/01_linear_regression/02_linear_regression_lab.ipynb) | Linear regression basics |
| [03_multivariate_linear_regression.ipynb](notebooks/01_linear_regression/03_multivariate_linear_regression.ipynb) | Multiple features and vectorized regression |
| [04_feature_engineering_polynomial_regression.ipynb](notebooks/01_linear_regression/04_feature_engineering_polynomial_regression.ipynb) | Feature engineering and polynomial regression |

### 02 Logistic Regression

| Notebook | Topic |
| --- | --- |
| [01_sigmoid_logistic_regression.ipynb](notebooks/02_logistic_regression/01_sigmoid_logistic_regression.ipynb) | Sigmoid function and logistic regression intuition |
| [02_gradient_descent_logistic_regression.ipynb](notebooks/02_logistic_regression/02_gradient_descent_logistic_regression.ipynb) | Gradient descent for logistic regression |
| [03_logistic_regression_scikit_learn.ipynb](notebooks/02_logistic_regression/03_logistic_regression_scikit_learn.ipynb) | Logistic regression with scikit-learn |

### 03 Neural Networks

| Notebook | Topic |
| --- | --- |
| [01_coffee_roasting_neural_network.ipynb](notebooks/03_neural_networks/01_coffee_roasting_neural_network.ipynb) | Binary classification with a small neural network |
| [02_softmax_function.ipynb](notebooks/03_neural_networks/02_softmax_function.ipynb) | Softmax and multiclass classification |

## Setup

Create and activate a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Start Jupyter:

```bash
jupyter notebook
```

## Notes

- Notebook outputs are intentionally cleared before commit to keep diffs readable.
- Local folders such as `.venv/`, `venv/`, `.idea/`, and notebook checkpoints are ignored by Git.
- The notebooks are organized in learning order, so start with `notebooks/01_linear_regression`.
