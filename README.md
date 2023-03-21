# Medical Insurance Cost Prediction Model
## Problem Statement
Medical insurance is an essential aspect of healthcare, providing individuals and families with access to affordable medical care. However, insurance costs can vary greatly depending on various factors, such as age, health status, and location. This makes it difficult for individuals to plan and budget for their healthcare expenses. A medical insurance cost prediction model can help address this challenge by providing accurate estimates of insurance costs. A medical insurance cost prediction model can be used by individuals and families to estimate their healthcare expenses and plan for the future. By analyzing factors such as age, health status, family history, and insurance plan type, these models can predict future healthcare costs with a high degree of accuracy. This information can help individuals and families choose the right insurance plan and make informed decisions about their healthcare expenses.
## Data Information
The dataset can be download using this [link](https://www.kaggle.com/datasets/mirichoi0218/insurance)

The dataset contains factors which would affect the insurance of a person such as the age, sex, BMI and region of the person.
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. As the current dataset contains textual and numerical data, we encode the textual data.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use the Random Forrest Regressor as our model available in the sklearn library. We also need to evaluate the models using appropriate evaluation metrics.
