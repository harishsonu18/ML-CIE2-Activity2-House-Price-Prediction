# Simple House Price Prediction

**Machine Learning CIE 2 – Activity 2**  
**Unit II – Supervised Learning: Regression**

## Objective
Build a Linear Regression model to predict a continuous numerical house price using property area.

## Dataset
- Dataset: Housing Prices Dataset
- Source: https://www.kaggle.com/datasets/yasserh/housing-prices-dataset
- Description: The dataset contains housing/property information, including area and price.
- Download `Housing.csv` from the source and upload it when running the notebook.

## Selected variables
- Input feature (X): `area`
- Target (y): `price`

Area is selected because property size may be related to its price. An ID column is not used as a predictive feature.

## Method
1. Load and inspect the dataset.
2. Check data types, summary statistics, missing values and duplicate rows.
3. Remove duplicate rows and records with missing/invalid area or price.
4. Visualise area against actual price.
5. Split the data into 80% training and 20% testing sets.
6. Train a Linear Regression model.
7. Predict prices for test observations.
8. Evaluate using MAE, MSE, RMSE and R².
9. Plot actual versus predicted prices.
10. Predict the price for a new example.

## Files
- `House_Price_Prediction.ipynb` – notebook containing the practical steps and Python code.
- `README.md` – project information and instructions.
- `requirements.txt` – required Python libraries.

## How to run
1. Open https://colab.research.google.com/
2. Upload and open `House_Price_Prediction.ipynb`.
3. Download `Housing.csv` from the Kaggle dataset source.
4. Run the notebook cells in order and upload the CSV when prompted.
5. Keep the actual executed outputs, plots and metric values in the notebook before submission.

## Results
Run the notebook to generate the actual coefficient, intercept, test predictions, evaluation metrics and new example prediction. Do not enter estimated or invented results.

## Faculty reference and acknowledgement
[Princy2129 – GitHub](https://github.com/Princy2129)

This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: https://github.com/Princy2129
