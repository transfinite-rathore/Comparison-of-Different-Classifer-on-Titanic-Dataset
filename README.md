
# Titanic Dataset Analysis and Machine Learning Models

## Overview
This project analyzes the Titanic dataset using various machine learning classification models to predict survival outcomes. The dataset includes information about passengers such as age, gender, ticket class, and fare.
## Project Structure
Data Files:
* Final_train_data.csv: CSV file containing the training data.
* Final_test_data.csv: CSV file containing the test data.

Code Files:
* titanic_ml_models.ipynb: Jupyter Notebook containing the Python code for data preprocessing, model training, and evaluation.

Models:
* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Decision Tree (DT)
* Random Forest (RFC)
## Installation

Clone the repository

```bash
  git clone https://github.com/transfinite-rathore/Comparison-of-Different-Classifer-on-Titanic-Dataset.git
```
Navigate to the project
    
    cd titanic_ml_models
Install the required libraries

    pip install -r requirements.txt
## Usage

1.Open titanic_ml_models.ipynb in Jupyter Notebook or any compatible environment.

2.Execute the cells in the notebook sequentially to load the data, preprocess it, train different machine learning models, and evaluate their performance.

3.Modify hyperparameters or experiment with different models as needed.


## Dependencies
* Python 3.x

* Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn
## Results
* Logistic Regression: Accuracy - 93.78%
* K-Nearest Neighbors (KNN): Accuracy - 85.17% (with optimal k=6)
* Support Vector Machine (SVM): Accuracy - 93.78%
* Decision Tree (DT): Accuracy - 91.63%
* Random Forest (RFC): Accuracy - 84.21% (with max_depth=8 and n_estimators=10)
