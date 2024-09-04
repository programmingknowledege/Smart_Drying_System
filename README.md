# Smart_Drying_System


# Moisture Content Prediction

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Libraries Used](#libraries-used)
- [Versioning](#versioning)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Project Overview
This project is part of a dissertation focused on predicting moisture content using various machine learning models.

## Data
The datasets used in this project are as follows:
- `smart_drying_dataset.csv`

These files are included in the repository.

## Installation
To run the code in this repository, you need to have Python installed along with the necessary libraries. You can install all the required libraries using the following command:

```bash
pip install -r requirements.txt
```

(Note: You can generate a `requirements.txt` file using `pip freeze > requirements.txt` to capture all the installed libraries with their versions.)

## Usage
To use the code provided in this repository:

1. Clone the repository:

   ```bash
   https://github.com/programmingknowledege/Smart_Drying_System.git
   ```

2. Navigate to the directory:

   ```bash
   cd Smart_Drying_System
   ```

3. The project is carried out in three method. 1. Baseline model Training 2. Feature Optimized Training 3. Smote with Feature Optimized Training
   Baseline Model Training: The model was trained on original dataset.  Open the Jupyter Notebook `Smart_Drying_System.ipynb` to explore the analysis, model building, and evaluation steps.
   Feature Optimized Training: The model was trained on after applying RFE on the original dataset to select relevant features. The model was trained on original dataset.  Open the Jupyter Notebook `Smart_drying_problem_RFE.ipynb` to explore the analysis, model building, and evaluation steps.
   Smote with Feature Optimized Training: The model was trained after applying data augmentation using SMOTE and then applying RFE on the original dataset to select relevant features. To explore the analysis, model building, and evaluation steps, open the Jupyter Notebook Smart_drying_problem_Smote_with_RFE.ipynb.


## Results
The key results of this project are the predictive performance metrics for the various models used, including Mean Absolute Error (MAE), R-squared (R²), Root Mean Square Error(RMSE) and Mean Squared Error (MSE). These metrics help in understanding the effectiveness of the models in predicting mositure content.

## Libraries Used
The project uses the following libraries:

- Python: 3.8
- numpy
- pandas
- seaborn
- matplotlib
- scikeras 
- scikit-learn
  -  GridSearchCV
  - RFE
  - StandardScaler
  - XGBoost Regressor, AdaBoostRegressor, VotingRegressor, DecisionTreeRegressor, RandomForest, SVR, RandomForestRegressor, GradientBoostingRegressor
  - mean_absolute_error, r2_score, mean_squared_error, root_mean_square_error
    
- xgboost
- catboost
- shap
- lime

## Versioning
For the versions of the libraries used in this project, refer to the `requirements.txt` file. Below are the versions of a few key libraries:

- numpy: 1.21.2
- pandas: 1.3.3
- seaborn: 0.11.2
- matplotlib: 3.4.3
- scikit-learn: 0.24.2
- xgboost: 1.4.2
- catboost: 0.26.1
- shap: 0.39.0
- lime: 0.2.0.1
- scikeras: 0.12.0

## Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure that your changes are well-documented and tested.



## Acknowledgements
Thank you to the University of Nottingham for the guidance and resources provided during this project. Special thanks to my supervisor for their support and mentorship.
