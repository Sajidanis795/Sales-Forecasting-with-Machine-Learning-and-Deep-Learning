# Sales-Forecasting-with-Machine-Learning-and-Deep-Learning

This repository contains a project where I use both machine learning and deep learning techniques to forecast sales.

I have a dataset that includes sales data from various fictitious learning modules from different Kaggle-branded stores in different countries. The data is synthetic but contains many real-world effects like weekend and holiday effects, seasonality, etc. The task is to predict sales for the year 2022.

I approach this problem in two ways:

# Gradient Boosting Regressor: I use this powerful machine learning algorithm to create a model that can handle both numerical and categorical data. The model is trained on preprocessed  and encoded data, and then used to predict sales for 2022.

# Long Short-Term Memory (LSTM) Model: I use this type of Recurrent Neural Network (RNN) to handle the time-series forecasting aspect of this problem. LSTM models are designed to handle sequence prediction problems and are particularly useful for time-series data. I use an LSTM model to predict total sales based on sales data from the previous 30 days.

The repository contains the Jupyter notebook where all the analysis and model training is done, along with the Python scripts for data preprocessing and model training. It also includes the CSV files 

This project showcases the use of both traditional machine learning and deep learning techniques for a complex forecasting task. It demonstrates the steps involved in preprocessing data, training models, and making predictions. It also illustrates how different models can be used to handle different types of data and prediction tasks.
