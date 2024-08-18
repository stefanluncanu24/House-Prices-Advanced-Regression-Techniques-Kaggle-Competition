# House Prices - Advanced Regression Techniques Competition
Our team: me, @JonahK12 and @SLvr-Srfrn competed in the House Prices - Advanced Regression Techniques challenge on Kaggle. It was our first competition, and as of 16 August 2024, we're thrilled to be in the top 12% for predicting house prices.

# House Prices Prediction

This repository contains the code for predicting house prices using machine learning techniques, with the dataset sourced from a popular Kaggle competition (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).

## Overview

The project involves several key phases:
1. **Data Loading and Preprocessing**: Cleaning and preparing the data for modeling.
2. **Data Visualization**: Visualizing relationships and data trends.
3. **Feature Engineering**: Enhancing model performance by transforming features.
4. **Model Training**: Building and tuning an XGBoost model.
5. **Model Evaluation**: Assessing the model's performance.
6. **Prediction and Submission**: Making predictions and preparing submissions for the competition.

## Dependencies

This project requires the following Python libraries:
- Pandas
- Seaborn
- Matplotlib
- XGBoost
- Scikit-learn


## Dataset

The dataset used is `train.csv` for training and `test.csv` for predictions. The data includes various features related to the properties such as area, condition, year built, etc., along with the sale price.

## Usage

Run the Jupyter notebook `code.ipynb.ipynb` to execute the code:
- Load the dataset.
- Perform preprocessing and cleaning.
- Visualize the data.
- Train the XGBoost model.
- Evaluate and generate predictions.

## File Descriptions

 - code.ipynb - the final code used for the submission
 - submission.csv -  the output of the code
 - test.csv - the unlabeled "finaltest" data used for determining our team score
 - train.csv - the labeled dataset used for building the model
 - plots.rar - an archive containing all the label(feature) plots
 - data analysis.ipynb - code used for the analysis of the data

## Results

The trained XGBoost model predicts house prices based on the input features. The performance is evaluated using Mean Squared Error (MSE), and results are saved for submission to the Kaggle competition.

![image](https://github.com/user-attachments/assets/28806118-8d56-450c-b468-4097dd693d8d)

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## Contact

Email: stefanluncanu24@gmail.com



