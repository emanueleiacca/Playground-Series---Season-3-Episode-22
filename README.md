# Horse Health Classification

This repository contains code and data for a machine learning project that classifies the health status of horses based on various features. The project uses the LightGBM classifier and involves data preprocessing, missing value imputation, and label encoding.

## Dataset

The dataset used in this project is available in the following files:
- `train_data.csv`: Contains the training data.
- `test_data.csv`: Contains the test data.

The dataset includes the following columns:
- `surgery`: Indicates whether the horse underwent surgery (categorical: 'yes' or 'no').
- `age`: Indicates the age of the horse (categorical: 'adult' or 'young').
- `hospital_number`: The hospital number associated with the horse (numeric).
- `rectal_temp`: The rectal temperature of the horse (numeric).
- `pulse`: The pulse rate of the horse (numeric).
- `respiratory_rate`: The respiratory rate of the horse (numeric).
- `temp_of_extremities`: The temperature of the extremities (categorical).
- `peripheral_pulse`: The peripheral pulse (categorical).
- `mucous_membrane`: The condition of the mucous membrane (categorical).
- `capillary_refill_time`: Capillary refill time (categorical).
- ... (other columns not listed)

## Data Exploration

The repository includes code for data exploration, including:
- Distribution of categorical features.
- Distribution of numerical features.
- Heatmap of numerical columns.
- Handling missing data using the MissForest library in RStudio.

## Data Preprocessing

- Label encoding is applied to categorical variables.
- Missing values are imputed using the MissForest library.

## Model Training

A LightGBM classifier is trained on the preprocessed data to predict the health outcome of the horses. The model is trained with 100 estimators and a random state of 42.

## Results

The trained model is used to make predictions on the test dataset, and the results are saved in a CSV file.

