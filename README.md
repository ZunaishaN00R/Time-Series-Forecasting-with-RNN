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
- Required Python libraries are listed in the 'requirements.txt' file.

## Setup and Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ZunaishaN00R/Time-Series-Forecasting-with-RNN.git
   cd your-repo
# Time Series Forecasting with RNN

## Open and Run the Jupyter Notebook

```bash
git clone https://github.com/ZunaishaN00R/Time-Series-Forecasting-with-RNN.git
cd Time-Series-Forecasting-with-RNN
# Open and run the Jupyter Notebook 'Time_Series_Forecasting_with_RNN.ipynb' to execute the code.


## Model Training

- The dataset is split into training and testing sets.
- MinMax scaling is applied to normalize the data.
- Sequences of data are created for training the RNN model.
- The RNN model architecture consists of a SimpleRNN layer and a Dense layer.
- The model is compiled using the Adam optimizer and mean squared error loss.
- Training is performed for 50 epochs with a batch size of 32.

