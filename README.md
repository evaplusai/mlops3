# mlops3 - E2E ml project to test open source MLOps tools

The main objective of this project is learning MLOPs tools from open source and manage ML Project through entire ML lifecycle
It will go in 4 stages:

### 1. Stage - Kick-Starting 
This will leverage best practices to establish project structure, dependancies management and data versioning.

### 2. Stage - Model Pipeline and Reproducing
Create reproducable pipelines, version model artifacts and storage
Manage ML experiements when it involves very large number 

### 3. Stage - CI/CD for ML
Leverage FastAPI, Docker and deployiment to the cloud

### 4. Stage - Monitor ML Project after deployment
Data Drift monitoring and tools to add to DVC pipeline, data drift metrics

#### ML Problem Description
Predict if the bank customer is more likely to leave the bank based on personal and other factors

Dataset source: https://www.kaggle.com/datasets/filippoo/deep-learning-az-ann

#### Use Case
Train the ML model that returns the probability of customer churning.
The problem is of type Binary Classification and for evaluation metrics is used F1 score.
The algorithm need to maximize both precision and recall simultaneously.
