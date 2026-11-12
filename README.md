# Red Wine Quality Prediction

This project uses the Red Wine Quality dataset, which contains physicochemical test results for Portuguese red wine samples.
The aim is to predict the sensory quality score (`quality`) from 11 chemical and physical properties.
Two regression models are trained: Linear Regression and Random Forest Regressor.
The models are evaluated using MAE, RMSE and R-squared; run the notebook to generate the exact results for the test split.
The Random Forest feature-importance chart helps identify which measured properties were most useful to the model.
I learned how to clean a dataset, explore correlations, train regression models and compare their prediction errors.

## Files
- `Wine_Quality_Prediction.ipynb` — complete notebook.
- `winequality-red.csv` — download this dataset from Kaggle and upload it alongside the notebook.

## Dataset
Kaggle dataset page: https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

The notebook can also download the original public CSV from the UCI repository if the local CSV is not present:
https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-red.csv

The CSV is semicolon-separated; the notebook handles this automatically.

## How to run
1. Download `winequality-red.csv` from the Kaggle dataset page.
2. Open the notebook in Google Colab.
3. Upload the CSV to the Colab session (or keep it in the same folder in Jupyter).
4. Run **Runtime → Run all**.
5. Review the evaluation table and plots.
6. Download the executed notebook as `.ipynb`.
7. Upload the executed notebook, CSV and this README to your public GitHub repository.
