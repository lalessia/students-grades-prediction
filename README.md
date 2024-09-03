# High School Students' Grade Prediction

This repository contains a project focused on data exploration and grade prediction for a sample of high school students, with the goal of identifying key factors influencing academic performance.

## Project Structure

- **`dataset/`**: This folder contains the data sources used in the project. The datasets have been extracted from [Kaggle](https://www.kaggle.com/datasets/uciml/student-alcohol-consumption/data) and are utilized for both data exploration and prediction.

- **`grade_EDA_PDA.ipynb`**: This Jupyter Notebook is the core of the project. It includes:
  - **Exploratory Data Analysis (EDA)**: Investigation of the dataset to understand the distributions, relationships, and key patterns.
  - **Predictive Data Analysis (PDA)**: The application of machine learning models to predict students' grades based on the explored features.

- **`grade_documentation.pdf`**: This PDF document provides detailed documentation of the project, including the methodology, data processing steps, model selection, and evaluation.

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/lalessia/students-grades-prediction.git
```
2. Navigate to the project directory:
```bash
cd students-grades-prediction
```
3. Open the Jupyter Notebook: You can open the notebook using Jupyter Notebook or Jupyter Lab.
```bash
jupyter notebook grade_EDA_PDA.ipynb
```
4. Install requirements: You can install all the required packages using the following command:
```bash
pip install -r requirements.txt
```
5. Run the notebook: Execute the cells in the notebook to perform the data exploration and run the predictive models.

## Key Challenges
This project presented several significant challenges:

 - **Variable Encoding**: Properly encoding categorical variables was crucial to ensure that the data could be effectively utilized in the analysis. Choosing the right encoding techniques was essential to maintain the integrity of the data and avoid introducing biases.

 - **Feature Selection**: Identifying the most impactful features for data analysis was a critical step. It required careful consideration to ensure that only the variables with the highest predictive power were included, which directly influenced the accuracy of the analysis and predictions.

 - **Regression Algorithm Selection**: Choosing the most appropriate regression algorithms for predicting final grades was another major challenge. The selection process involved evaluating various models to find the best fit for the data, balancing complexity with predictive performance.

## Project Overview

### Dataset
The dataset used in this project includes information on various aspects of high school students, such as demographic details, alcohol consumption habits, family environment and academic performance. 
The dataset has been preprocessed and is available in the dataset/ folder.

### EDA
The Exploratory Data Analysis (EDA) phase focuses on understanding the relationships between different variables within the dataset. 

### PDA
The project applies several machine learning algorithms to predict students' final grades.

Implemented sklearn algorithms:

  - svm
    - [SVR](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVR.html)
  - tree
    - [DecisionTreeRegression](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeRegressor.html)
  - ensemble
      - [RandomForestRegression](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)
      - [GradientBoostingRegression](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html)
      - [BaggingRegression](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingRegressor.html)
  - neighbors
      - [KNeighborsRegression](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsRegressor.html)
  - neural_network
      - [MLPRegression](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html)
  - linear_model
    - [LinearRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html)
    - [Lasso](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Lasso.html)
    - [Ridge](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.Ridge.html)
    
The models are evaluated based on their 
- accuracy, precision, recall, and F1 score. 

The notebook provides a step-by-step guide to how these models are implemented and evaluated.

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Contributions that improve the analysis, add new models, or enhance the documentation are welcome.
