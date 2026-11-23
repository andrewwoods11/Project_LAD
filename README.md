# Project X - Course Y
Write an overview of this repo and your project here.

# Predicting Concrete Compressive Strength: Data Analytics & Data Mining (Group LAD)

**Research question:** *How accurately can concrete compressive strength be predicted from mixture composition and curing age?*

We treat this as a supervised **regression** problem on the UCI Concrete Compressive Strength dataset (1,030 samples, 8 predictors, target in MPa). We compare a linear baseline against nonlinear models, evaluated with MAE, RMSE and R² on unseen data.

## Repository structure

```
data/         raw data (see data/README.md) + cleaned CSV
notebooks/
  01_data_cleaning_eda.ipynb   cleaning steps, descriptive stats, correlations, plots
  02_modelling.ipynb           baseline vs models, CV, tuning, test set, residuals, feature importance
results/      metrics tables (.csv), summary.txt, figures/
slides/       presentation
```

## How to run

```bash
pip install -r requirements.txt
jupyter notebook
```