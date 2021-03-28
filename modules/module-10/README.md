# Module 10: SKLearn Foundations

In this collection, we have a lot of notebooks that go together! It's a good thing to look at them in order, to get more context, however, each notebook is still a good source on its own!

***Note:*** Since the version of SKlearn and Python you have may result in dissimilar results, I will provide Docker images to ensure compatibility. If you want to get close and not worry about Docker, I'm building the notebooks on Anaconda Python 3.8, with SKLearn version 0.23.1.

## Machine Learning Fundamentals

### Introductory Materials

- Regression vs. Classification
- Supervised vs. Unsupervised Models
- Training, Testing, Validation
- Overfitting / Underfitting
- Statistical Properties of Underlying Functions

### Preprocessing Data

**Categorical Encoding:**
 - One-Hot Encoding
 - Binary Encoding
 - "Dropping" Categories & Colinearity
 - Handling Errors vs. Colinearity


**Numerical Encoding:**
 - Logarithmic Transformations
 - Polynomial Relationships
 - Standard Scaling
 - Normalization

## Regression Algorithms & Topics

### Notebook Series: Expanding Upon Linear Regression
- Linear Regression *(mod10-regression-linear-regression.ipynb)*
- Linear Regression with Transformed (Logarithmic) Target *(mod10-regression-linear-regresssion-transformed-target.ipynb)*
- Ridge Regression with Standardized Inputs *(mod10-regression-ridge-regression-standardized-inputs.ipynb)*
- Ridge and LASSO Regression with Polynomial Features *(mod10-regression-ridge-lasso-polynomial-features.ipynb)*
- Ridge and LASSO with Log-Log Transformations *(mod10-regression-ridge-lasso-log-log-models.ipynb)*

### Notebook Series: Regression Trees, Extensions, and Stumps
- Regression Trees
- Random Forest Regression
- Extremely Randomized (ExtRa) Trees
- AdaBoost Regression
- XGBoost Regression

### Notebook Series: Stacking Regression Models
- Stacking Regression Models

## Classification Algorithms & Topics

- Logistic Regression
- Decision Trees
- Random Forest
- K Nearest Neighbors
- K Means
