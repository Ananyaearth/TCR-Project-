# Calorie Expenditure Modeling using XGBoost

## Overview

This project aims to model calorie expenditure using the XGBoost algorithm. The goal is to predict the number of calories burned during exercise based on various features such as user characteristics and exercise parameters. The dataset consists of two CSV files: `calories.csv`, containing user IDs and corresponding calorie counts, and `exercise.csv`, containing user information and exercise details.

## Files

1. **Xgboost_model.ipynb**: Jupyter Notebook containing the code for building and training the XGBoost model. This notebook includes data preprocessing, model training, evaluation, and prediction.

2. **calories.csv**: CSV file containing user IDs (`User_id`) and the corresponding calorie counts. Each row represents a record of calorie expenditure for a specific user.

3. **exercise.csv**: CSV file containing user information and exercise details. It includes columns such as `User_ID`, `Gender`, `Age`, `Height`, `Weight`, `Duration`, `Heart_Rate`, and `Body_Temp`. These features are used to predict calorie expenditure.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/Ananyaearth/TCR-Project-.git
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

## Usage

1. Open the `Xgboost_model.ipynb` notebook using Jupyter or any compatible environment.

2. Run the cells in the notebook sequentially to preprocess the data, train the XGBoost model, evaluate its performance, and make predictions.

3. Ensure that both `calories.csv` and `exercise.csv` are in the same directory as the notebook, or provide the correct file paths within the notebook.

## Dataset

- **calories.csv**: Contains records of calorie counts for different users.
- **exercise.csv**: Contains user information and exercise details used for modeling calorie expenditure.

## Model Evaluation

The performance of the XGBoost model is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score. These metrics provide insights into how well the model predicts calorie expenditure based on the given features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
