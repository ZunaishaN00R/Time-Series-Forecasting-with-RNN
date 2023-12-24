# Time-Series-Forecasting-with-RNN
Time Series Forecasting with Recurrent Neural Network

## Overview

This project demonstrates the application of Recurrent Neural Networks (RNN) for time series forecasting, specifically in predicting electric production over time. The dataset used is 'Electric_Production.csv', containing monthly electric production values.

## Files and Directories

- **/content/Electric_Production.csv:** Dataset containing electric production values.
- **/notebooks/Time_Series_Forecasting_with_RNN.ipynb:** Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and visualization.
- **/results/:** Folder containing the generated model predictions and visualizations.
- **/README.md:** This file, providing an overview of the project.

## Dependencies

- Python 3.7 or higher

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ZunaishaN00R/Time-Series-Forecasting-with-RNN.git
   cd Time-Series-Forecasting-with-RNN
# Time Series Forecasting with RNN

Open and run the Jupyter Notebook 'Time_Series_Forecasting_with_RNN.ipynb' to execute the code.

**Model Training**
- The dataset is split into training and testing sets.
- MinMax scaling is applied to normalize the data.
- Sequences of data are created for training the RNN model.
- The RNN model architecture consists of a SimpleRNN layer and a Dense layer.
- The model is compiled using the Adam optimizer and mean squared error loss.
- Training is performed for 50 epochs with a batch size of 32.

**Model Evaluation**
- The trained model is evaluated on both training and testing sets.
- Metrics such as RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error) are calculated.
- R2 score is computed to assess the goodness of fit.

**Model Predictions**
- Predictions are made on the test set and inverse transformed to the original scale.
- Future predictions are generated for the next 50 time steps.

**Results Visualization**
- Visualizations include actual vs. predicted values on the training and testing sets.
- A plot shows the actual electric production values and future predictions.

**Results**
- Training RMSE: 2.33
- Testing RMSE: 3.91
- Training MAE: 1.79
- Testing MAE: 2.82
- Training R2 Score: 0.97
- Testing R2 Score: 0.84

**Future Work**
- Fine-tune hyperparameters for improved performance.
- Explore other architectures like LSTM or GRU.
- Experiment with different sequence lengths for better predictions.
