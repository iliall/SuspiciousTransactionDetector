# Suspicious-Transactions-Detector

## File Contents

| File                             | Content |
|----------------------------------|---------|
| `historical_transaction.csv`     | This file includes transaction data where each transaction is characterized by 100 variables. It also includes a target variable `y` that indicates whether a transaction is suspicious. This file will be used as the training dataset to develop the model that identifies suspicious transactions. |
| `current_transaction.csv`        | Contains transaction data in the same format as `historical_transaction.csv`, but lacks the `y` column. The objective is to apply the trained model to this dataset to predict whether each transaction is suspicious. |
| `predict.ipynb`                  | A notebook that details the methodologies employed for model development including data preprocessing, model training, evaluation, and prediction. |
| `current_transaction_predictions.csv` | This file contains the model's predictions for the `y` values (indicating suspicious or not) for each transaction in `current_transaction.csv`. |
