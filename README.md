# Machine_Learning

A curated collection of hands-on Jupyter notebooks covering core machine learning concepts, preprocessing techniques, and model-building workflows. This repository is designed for learning, experimentation, and teaching — each notebook focuses on a specific topic with runnable examples and visualizations.

## What You'll Find

- **Exploratory Data Analysis (EDA):** Univariate, bivariate and multivariate EDA notebooks with visualizations and pandas profiling examples.
- **Feature Engineering & Encoding:** Feature construction, scaling, standardization, normalization, ordinal and nominal encoding, and handling mixed data types.
- **Missing Data Imputation:** SimpleImputer, KNN imputation, iterative imputation, and strategies for categorical and numerical data.
- **Outlier Detection:** Z-score, IQR and percentile-based methods with practical examples.
- **Dimensionality Reduction:** Principal Component Analysis (PCA) and discussions of the curse of dimensionality.
- **Regression & Classification:** Linear regression variants, gradient descent implementations, regularization (Ridge, LASSO, ElasticNet), logistic regression and classification metrics.
- **Pipelines & Transformers:** Scikit-learn pipelines, `FunctionTransformer`, and practical examples of combining preprocessing with modeling.

## Notebooks (high level)

- 013-placement_model.ipynb — example placement/prediction model
- 019-026 series — EDA, pandas profiling and feature engineering
- 029-035 series — Pipelines, transformers, and handling mixed / datetime data
- 036-040 series — Imputation approaches (SimpleImputer, KNN, Iterative)
- 041-045 series — Outlier detection and feature construction
- 047-057 series — PCA, regression (simple, multiple, polynomial) and optimization techniques
- 058-060 series — Logistic regression, classification metrics and multiclass approaches

## Getting Started

1. Clone the repo and open the folder in VS Code or Jupyter Lab/Notebook.

2. (Recommended) Create a Python virtual environment and install common dependencies:

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

4. Open any notebook and run cells sequentially. Each notebook contains explanatory text, code, and plots.

## Suggested Workflow

- Start with the EDA notebooks to understand data distributions and relationships.
- Move to feature engineering and imputation notebooks to prepare data for modeling.
- Use the pipeline examples to combine preprocessing and modeling reproducibly.
- Experiment with regression and classification notebooks to compare metrics and regularization effects.

## Contributing

Contributions, suggestions, and improvements are welcome. Open an issue or submit a pull request with a clear description of changes.

## License

This repository does not specify a license. If you plan to share or reuse the content publicly, consider adding an open-source license (for example, MIT).

---

If you'd like, I can also add a `requirements.txt`, a short example notebook runner, or reorganize notebooks into subfolders — tell me which and I'll do it.