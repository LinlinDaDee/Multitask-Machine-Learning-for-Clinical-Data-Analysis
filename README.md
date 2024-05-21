# Overview
Machine learning has gained widespread attention for its excellent data analysis capabilities and is widely used in fields such as healthcare. Most of the traditional machine learning techniques focus on solving single-labelled classification problems, such as binary or multi-classification problems. However, the actual situation is often more complex, for example, medical research may need to predict multiple diseases at the same time. Such problems introduce the concept of multitask learning (MML), which allows models to predict multiple related target variables simultaneously.

In this project, I analyze clinical trial data provided by the confidential department of a well-known hospital. The anonymized patient characteristics include binary, categorical, and continuous variables with 11 predictive targets for medical conditions. The goal is to construct a model that performs well with average binary cross-entropy loss, using simple multitask learning strategies and neural networks.
# Project Structure
1. Exploratory Data Analysis (EDA):
- Perform initial data inspection and visualization.
- Handle missing values and data preprocessing.
2. Model Construction:
- Implement commonly used machine learning algorithms.
- Construct simple multitask learning models.
- Build neural network models for multitask learning.
3. Outcome Evaluation:
- Evaluate model performance using metrics such as average binary cross-entropy loss.
- Compare the performance of different models.
