# Stock Price Prediction

This GitHub repository contains a Python script for analyzing and predicting stock prices using historical data. The script leverages popular data science and machine learning libraries, including NumPy, Matplotlib, Seaborn, Scikit-Learn, Pandas, and Keras. It is designed to work with a JSON configuration file and historical stock price data in CSV format.

## Table of Contents

- [Requirements](#requirements)
- [Usage](#usage)
- [Introduction](#introduction)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Data Preprocessing](#data-preprocessing)
- [Building and Training a Deep Learning Model](#building-and-training-a-deep-learning-model)
- [Model Evaluation](#model-evaluation)
- [Making Predictions](#making-predictions)
- [Root Mean Squared Error (RMSE)](#root-mean-squared-error-rmse)
- [Contributing](#contributing)
- [License](#license)

## Requirements

Before using this script, make sure you have the following libraries installed:

- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Pandas
- Keras

You can install the required packages using pip:

```bash
pip install numpy matplotlib seaborn scikit-learn pandas keras
```

## Usage

1. Create a JSON configuration file (e.g., `config.json`) with the following content:

```json
{
    "train_data_path": "your_train_data.csv",
    "test_data_path": "your_test_data.csv"
}
```

Replace `"your_train_data.csv"` and `"your_test_data.csv"` with the paths to your historical stock price data files.

2. Use the provided Python script to analyze and predict stock prices:

```python
# ... (script content)

# Make sure to replace 'your_train_data.csv' and 'your_test_data.csv' with the actual file paths in the JSON configuration.

# ... (script content)
```

Please replace `'your_train_data.csv'` and `'your_test_data.csv'` with the actual paths to your training and testing data files in the JSON configuration file.

## Introduction

This script provides a comprehensive workflow for stock price prediction:

1. **Exploratory Data Analysis (EDA)**: It begins with an exploratory data analysis to understand the dataset's characteristics.

2. **Data Preprocessing**: The script preprocesses the data, filtering and cleaning it, and performs feature selection.

3. **Building and Training a Deep Learning Model**: It builds a deep learning model using Keras, a popular deep learning library.

4. **Model Evaluation**: The script evaluates the model's performance on a testing dataset and provides key metrics.

5. **Making Predictions**: After training, the model is used to make predictions on new data.

6. **Root Mean Squared Error (RMSE)**: The script calculates and displays the Root Mean Squared Error, a crucial metric for regression tasks.

## Exploratory Data Analysis (EDA)

The script begins by loading historical stock price data from a CSV file and provides an initial overview, including the dataset's shape, basic statistics, and information about the columns. It also performs visualizations like pairplots and identifies top dates with the highest closing stock prices.

## Data Preprocessing

Data preprocessing includes filtering rows based on specific conditions, standardizing the data using a scaler, splitting the data into training and testing sets, and defining a deep learning model for regression. 

## Building and Training a Deep Learning Model

A deep learning model is built using Keras. It consists of multiple dense layers with different numbers of units and uses the mean squared error (MSE) loss function for training. The model is trained using early stopping to prevent overfitting.

## Model Evaluation

The model is evaluated on the testing dataset, and its performance is assessed using the Mean Squared Error (MSE). The training history is visualized to understand the model's learning progress.

## Making Predictions

After training, the model is used to make predictions on the test data.

## Root Mean Squared Error (RMSE)

The script calculates and displays the Root Mean Squared Error, a standard metric for measuring the model's predictive accuracy.

## Contributing

Feel free to contribute to this project by opening issues, suggesting improvements, or submitting pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Get started with stock price prediction using this script and start making informed investment decisions today!
