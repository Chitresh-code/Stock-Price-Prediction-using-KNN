 # **Stock Price Prediction using K-Nearest Neighbors (KNN)**
> This project leverages the K-Nearest Neighbors (KNN) algorithm to predict stock prices based on historical data.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## About

This project leverages the K-Nearest Neighbors (KNN) algorithm to predict stock prices based on historical data. Stock price prediction is a crucial task in the financial domain, enabling investors to make informed decisions about buying or selling stocks. KNN, a simple yet effective machine learning algorithm, is utilized here due to its intuitive nature and ease of implementation.

## Features

-  **Data Collection:** The project involves collecting historical stock price data from quandl library.
-  **Preprocessing:** Data preprocessing is performed to clean and prepare the dataset for training. This includes handling missing values, scaling features, and possibly feature engineering.
-  **Model Training:** The KNN algorithm is trained on the preprocessed dataset. KNN works by finding the 'k' nearest data points to a given point in the feature space and making predictions based on the majority class or average value of those neighbors.
-  **Model Evaluation:** The performance of the trained model is evaluated using the root mean squared error (RMSE).
-  **Prediction:** Once the model is trained and evaluated, it can be used to make predictions on the closing value of the stock. We can also predict if we should either buy or sell the stock. Predictions are made based on the nearest neighbors of the input data point in the feature space.
-  **Visualization:** Visualizations such as line plots or candlestick charts can be generated to visualize the actual vs. predicted stock prices, aiding in understanding the model's performance.

## Usage
-   Researchers and practitioners in the financial domain can use this project as a basis for building stock price prediction models using the KNN algorithm.
-   Investors and traders can utilize the predictions generated by the model to make informed decisions about buying, selling, or holding stocks.
- It can also be used to predict the closing value of the stock.


## Dependencies
-   Python
-   NumPy
-   pandas
-   scikit-learn
-  quandl
-  matplotlib
- 
## Contributions 
Contributions to this project are welcome! Developers can contribute by adding new features, improving model performance, optimizing code, or fixing bugs.

## License 
This project is open-source and released under the [MIT License](https://github.com/Chitresh-code/Stock-Price-Prediction-using-KNN/blob/main/LICENSE). Feel free to use, modify, and distribute the code according to the terms of the license.
