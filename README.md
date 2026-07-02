# Machine_Learning

A curated collection of hands-on Jupyter notebooks covering core machine learning concepts, preprocessing techniques, model workflows, and practical examples. This repository is designed for learning, experimentation, and teaching — each notebook focuses on a specific topic with runnable code and visualizations.

## What You'll Find

- **Exploratory Data Analysis (EDA):** Univariate, bivariate, and multivariate EDA notebooks with visualizations and pandas profiling examples.
- **Feature Engineering & Encoding:** Feature construction, scaling, standardization, normalization, ordinal and nominal encoding, and handling mixed data types.
- **Missing Data Imputation:** SimpleImputer, KNN imputation, iterative imputation, and categorical/numerical imputation strategies.
- **Outlier Detection:** Z-score, IQR, and percentile-based outlier detection methods.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) and the curse of dimensionality.
- **Regression & Classification:** Linear regression, multiple regression, polynomial regression, gradient descent, regularization (Ridge, LASSO, ElasticNet), logistic regression, Naive Bayes, KNN, SVM, decision trees, ensembles, and classification metrics.
- **Pipelines & Transformers:** Scikit-learn pipelines, `FunctionTransformer`, and practical preprocessing-model workflows.
- **Clustering:** K-means, hierarchical clustering, and DBSCAN.

## Notebook Overview

- `013-placement_model.ipynb` — example placement/prediction model
- `019-022` — EDA, data understanding, and pandas profiling
- `023` — feature engineering fundamentals
- `024-027` — standardization, normalization, ordinal encoding, and one-hot encoding
- `029-035` — pipelines, `FunctionTransformer`, numeric encoding, mixed-data handling, datetime handling, and missing-values case analysis
- `036-040` — missing value imputation with SimpleImputer, categorical imputation, KNN, and iterative methods
- `041-045` — outlier detection methods and feature construction
- `046` — curse of dimensionality discussion
- `047` — Principal Component Analysis (PCA)
- `048-057` — regression algorithms, gradient descent, polynomial regression, bias-variance tradeoff, and regularization techniques
- `058-060` — logistic regression, classification metrics, and multiclass logistic regression
- `061-068` — Naive Bayes, K-nearest neighbors, support vector machines, decision trees, random forest, adaptive boosting, gradient boosting, and XGBoost
- `069-071` — clustering methods: K-means, hierarchical clustering, and DBSCAN

## Getting Started

1. Clone the repository and open the folder in VS Code, Jupyter Lab, or Jupyter Notebook.
2. (Recommended) Create a Python virtual environment and install dependencies:

```bash
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install jupyterlab numpy pandas scikit-learn matplotlib seaborn pandas-profiling
```

3. Launch Jupyter Lab or Notebook:

```bash
jupyter lab
```

4. Open a notebook and run cells sequentially. Each notebook includes explanations, code, and plots.

## Suggested Workflow

- Start with the EDA notebooks to explore data distributions and relationships.
- Continue with feature engineering, encoding, and missing-value notebooks to prepare datasets.
- Use pipeline and transformer notebooks to build reproducible preprocessing workflows.
- Explore regression, classification, and ensemble notebooks to compare algorithms and metrics.
- Finish with clustering notebooks to learn unsupervised learning methods.

## Contributing

Contributions, suggestions, and improvements are welcome. Please open an issue or submit a pull request with a clear description of your changes.

## License

This repository does not specify a license. If you plan to share or reuse the content publicly, consider adding an open-source license such as MIT.