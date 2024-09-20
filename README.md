## PyCaret-ML-Workflows
PyCaret Low Code Assignment - Part 2

Introduction
PyCaret is an open-source, low-code machine learning library in Python that automates end-to-end machine learning workflows. With PyCaret, complex machine learning tasks can be completed with just a few lines of code, significantly reducing the manual effort required. It integrates many machine learning libraries, including Scikit-learn, XGBoost, and LightGBM.

This assignment covers the implementation of various machine learning algorithms using PyCaret, applied across different types of datasets. The purpose is to explore PyCaret’s capabilities in binary classification, multi-class classification, regression, clustering, anomaly detection, association rule mining, and time series forecasting.

#For a detailed explanation and step-by-step walkthrough of the assignment, including dataset exploration and code execution, please refer to the full explanation video on YouTube:
1. https://youtu.be/AIYPsU9jcqg 
2. https://youtu.be/YjDiag_bK3U
3. https://youtu.be/ayqyFQcRGx0
4. https://youtu.be/zHMRkQG078M 


Steps in PyCaret Workflow
1. Setup
The setup() function initializes the environment and performs necessary data preprocessing, such as missing value imputation, scaling, encoding, and feature engineering. It prepares the dataset for model building and evaluation.
2. Compare Models
The compare_models() function is used to train and evaluate multiple models on the dataset. PyCaret automatically compares the performance of different algorithms based on the provided dataset.
3. Analyze Model
Once a model is selected, the analyze_model() function provides various visualizations to help understand its performance. These visualizations include confusion matrices, ROC curves, residual plots, and feature importance plots.
4. Prediction
The predict_model() function is used to generate predictions using the finalized model. It applies the trained model to unseen data for prediction purposes.
5. Save
The trained model can be saved using the save_model() function for later use. This allows easy reuse of the model without having to retrain it every time.


Machine Learning Algorithms Implemented
#Below are the machine learning tasks performed using PyCaret:

Binary Classification : Applied on datasets with two outcome labels, focusing on predicting binary outcomes like 'Yes/No', 'True/False'.
Multi-class Classification : Implemented for datasets with more than two categories, such as classifying images or text into multiple categories.
Regression : Implemented regression models to predict continuous outcomes, such as house prices or stock prices.
Clustering : Used unsupervised learning techniques to group similar data points together, based on feature similarities.
Anomaly Detection : Focused on detecting rare events or outliers in datasets, like fraudulent transactions or equipment failures.
Association Rule Mining : Extracted patterns and relationships between items in transactional datasets, commonly used in market basket analysis.
Time Series Forecasting (Univariate without Exogenous Variables) : Predicted future values in a time series without considering any external factors.
Time Series Forecasting (Univariate with Exogenous Variables) : Similar to the univariate approach but incorporates external or exogenous variables that can influence the predictions.

Datasets Used
* Pre-loaded datasets from PyCaret library
* Imported custom datasets using Pandas from external sources like Google Drive
The datasets were used to test and evaluate different machine learning models in each of the categories mentioned above.

How to Use : 
1. Install PyCaret:
 -->>> pip install pycaret
2. Clone the repository and download the Colab notebooks.
3. Run the Colab notebooks, which contain the implementation of the above models, using both pre-loaded datasets and custom datasets loaded through Pandas.

Conclusion
PyCaret offers a low-code, easy-to-use interface for machine learning workflows. By automating most of the repetitive tasks, it speeds up the process of model building, evaluation, and deployment. This assignment demonstrates the application of PyCaret across various machine learning tasks using different datasets.
For more details, watch the full explanation video here -> https://drive.google.com/file/d/1Q_z9zXvEgUuVUKPMXqeXkO11POCeypPq/view?usp=drive_link 



###Second part ->
Here i perfred two demo with the help of pycaret and Gradio. Where Gradio is an open-source Python library that allows developers to quickly create user-friendly web interfaces for machine learning models, enabling easy interaction and visualization of model predictions.
1. Wine Quality Prediction Using PyCaret and Gradio -> Gitlink : https://github.com/intimanjunath/PyCaret-ML-Workflows/blob/main/pycaret_gradio_wine.ipynb
2. Survival Prediction on the Titanic Dataset Using PyCaret and Gradio -> Gitlink : https://github.com/intimanjunath/PyCaret-ML-Workflows/blob/main/Pycaret_Gradio_titanic.ipynb
Here is the YouTube link explaning the above two videos : https://youtu.be/UQE9cu2GcAk 


This covers all the task of the PyCaret and Gradio, please refer the above code and links in this repo. 
