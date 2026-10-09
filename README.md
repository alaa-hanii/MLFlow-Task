# MLflow Experiment Tracking – California Housing

## Project Overview
This project trains and compares three Gradient Boosting Regression models using the California Housing dataset. MLflow is used to track experiment parameters, evaluation metrics, and trained models.

## Dataset
The California Housing dataset is used to predict house values. The data is split into 80% training and 20% validation sets.

## Experiments
Three configurations are evaluated using different values of `max_depth` and `learning_rate`.

| Run | max_depth | learning_rate | RMSE | MAE | R² |
|---|---:|---:|---:|---:|---:|
| Run 1 | 3 | 0.1 | [value] | [value] | [value] |
| Run 2 | 5 | 0.05 | [value] | [value] | [value] |
| Run 3 | 7 | 0.01 | [value] | [value] | [value] |

## Best Model
The best run is **[Run name]**, selected based on the lowest validation RMSE of **[value]**.

## Tools
- Python
- NumPy
- scikit-learn
- MLflow

## How to Run
1. Install dependencies:
   `pip install -r requirements.txt`
2. Run experiments:
   `python train.py`
3. Launch the MLflow UI:
   `mlflow ui`

Open `http://127.0.0.1:5000` to view and compare experiment runs.
