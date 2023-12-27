## Diabetes Detection Model
### Overview
- This repository contains Python code for a machine learning model that predicts the likelihood of a person having diabetes based on various health-related features. The model is built using the K-Nearest Neighbors (KNN) algorithm and is trained on a dataset containing information about individuals, such as glucose levels, blood pressure, and BMI.

### Contents
- Data Loading and Exploration: The dataset is loaded using Pandas, and an initial exploratory data analysis (EDA) is performed. This includes checking the shape of the data, detecting and handling missing values, and visualizing the distribution of features.

- Data Preprocessing: Zero values in certain features are replaced with NaN, and missing values are imputed using the mean or median values. Feature scaling is applied using the StandardScaler from scikit-learn.

- Model Training: The KNN algorithm is employed to build the predictive model. The optimal number of neighbors is determined through a hyperparameter tuning process using GridSearchCV.

- Model Evaluation: The model is evaluated using accuracy, a confusion matrix, and a classification report. The results provide insights into the performance of the trained model on a test set.

- Streamlit App: A simple web application is created using Streamlit, allowing users to input health-related details for an individual and receive a prediction on whether the person is likely to have diabetes or not.

- Model Deployment: The trained model is saved using the Pickle library, and the Streamlit app loads and utilizes this model for making predictions.
