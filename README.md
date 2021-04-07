# SageMaker and Step Functions

In this workshop you will explore the development cycle of machine learning model on AWS.
In the first part, you will find a sample project fully developed in an ml.m4.4xlarge SageMaker notebook instance. On purpose, the notebooks are divided in different stages

1. Exploratory analysis
2. ETL to prepare training data
3. Training the model with Hyperparameter Optimization
4. Putting "new data" through a preprocessing pipeline to get it ready for prediction
5. Batch predictions for new data

In the second part of this workshop we will implement this project in production automatizing it's execution using a combination of CloudWatch, Step Functions, Lambda, Glue and SageMaker.

