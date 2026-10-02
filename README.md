# Telecom Customer Churn Analysis

Explore customer retention patterns and train a logistic regression classifier to predict telecom churn. The notebook examines customer demographics, service subscriptions, tenure, and contract types before building a baseline model.

**Stack:** Python · pandas · NumPy · scikit-learn · Matplotlib · Seaborn

## Workflow

- Explore customer and subscription distributions with plots.
- Prepare features and normalize numerical inputs.
- Split data into training and test sets (70/30, `random_state=101`).
- Fit logistic regression and report test accuracy.

## Run locally

```bash
git clone https://github.com/abiy8/codeclause_task1.git
cd codeclause_task1
python -m venv .venv
# Activate .venv for your operating system.
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
jupyter notebook
```

Open `churn telecom.ipynb` and run cells in order. The notebook reads the included `churn.csv.csv`.

## Project context and limitations

This repository is a CodeClause task / learning project. Accuracy is an initial baseline; precision, recall, class balance, and a confusion matrix should also be reviewed before making retention decisions. Preprocessing should be fitted on training data only for a rigorous evaluation. Some plotting calls use older Seaborn APIs and may require adjustment with current versions.
