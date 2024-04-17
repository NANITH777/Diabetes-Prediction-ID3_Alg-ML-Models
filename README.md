# Diabetes Prediction - Data Mining and Machine Learning Models

This project aims to predict diabetes using data mining techniques and various machine learning models. We utilized a diabetes dataset to train and evaluate multiple learning models.

## Introduction

Diabetes is a common chronic disease affecting millions of people worldwide. Predicting diabetes using medical data can help identify individuals at risk and implement appropriate preventive measures. In this project, we explored a diabetes dataset and used data mining techniques along with machine learning models to predict the presence of diabetes.

##Data Cleaning Process

Before building the learning models, we cleaned the data to remove missing values, outliers, and duplicates. Additionally, we encoded the features to improve model performance. We also normalized the features to ensure consistency and enhance the learning process.

## ID3 Algorithm and Decision Tree Construction

We employed the ID3 algorithm to construct a decision tree from the diabetes data. The goal was to determine the most important features for predicting diabetes and understand the progression of the decision tree.

![Decision_tree](https://github.com/NANITH777/VM_Odev_ID3_Algorithm/assets/109669139/d2cd2796-0422-44fc-9e18-2bed94bedc45)

## Data Splitting and Learning Models

The data was split into training and testing sets to assess model performance. We utilized multiple learning models, including `RandomForestClassifier`, `LogisticRegression`, `LinearRegression`, `GaussianNB`, `MultinomialNB`, and `DecisionTreeClassifier`.

## Model Evaluation

We evaluated model performance using metrics such as `accuracy` and `confusion matrix`. We also utilized GridSearchCV to find the best parameters for each model and calculated the average of each model to compare their performance.

## Results and Conclusion

Our analysis showed that the RandomForestClassifier model had the best performance for predicting diabetes on this dataset. However, it is important to note that each model has its advantages and limitations, and further analysis may be needed to refine predictions.

## Execution Instructions

To run this code, please follow these steps:
1. Clone this repository to your local machine.
2. Ensure you have installed all dependencies listed in the requirements.txt file.
3. Run the main script to train and evaluate the models.


Feel free to customize this README by replacing the generic sections with the specific details of your project. If you have screenshots, code demos, or other relevant resources, feel free to include them in your repository and reference them in your README.
