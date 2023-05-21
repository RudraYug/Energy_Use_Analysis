
# Energy Use Analysis

The code in this repository performs an analysis of energy use based on the PJME hourly dataset. It includes several steps, such as data preprocessing, visualization, feature creation, model training, and prediction. The dataset used, "PJME_hourly.csv," is loaded and prepared for analysis.

The code begins by importing necessary libraries, including pandas, numpy, matplotlib, seaborn, xgboost, and scikit-learn. The PJME hourly dataset is loaded using pandas and processed to ensure the correct data types and indexing.

The energy use data is visualized using line plots, providing insights into the patterns and trends over time. The dataset is then split into training and test sets based on a specified date.

Additional time-based features are created, such as hour, day of the week, quarter, month, year, day of the year, day of the month, and week of the year. These features will be used for modeling and analysis.

The relationship between the newly created features and the energy use target variable is visualized using box plots, allowing for an understanding of how these features impact energy consumption.

A regression model, specifically an XGBoost regressor, is created and trained using the training set. The model's performance is evaluated on the test set using the root mean squared error (RMSE) metric.

Feature importance is calculated and displayed, indicating the relative importance of each feature in the prediction model.

Predictions are made on the test set using the trained model, and the predicted values are merged with the original dataset. Line plots are used to compare the actual energy use and the predicted values.

Specific weeks of data are visualized, showcasing the actual energy use and the corresponding predictions.

The code calculates the RMSE score on the test set to assess the model's accuracy.

Lastly, the top 10 error values, sorted by date, are calculated and displayed, providing insights into the instances where the model has the highest deviation from the actual values.

Please note that this is a brief description of the code's functionality, and the actual implementation may include more details and specific configurations.
## Table Of Contents

- Prerequisites
- Code Overview
- Installation
- Code Explanation
- Usage
- Contribution
- Conclusion
- License
- Related

## Prerequisites

Make sure you have the following prerequisites installed:

- [Python 3.x](https://www.python.org/downloads/)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [seaborn](https://seaborn.pydata.org/)
- [xgboost](https://xgboost.readthedocs.io/en/stable/)
- [scikit-learn](https://scikit-learn.org/stable/)

You can install the required Python libraries using pip:

**`pip install pandas numpy matplotlib seaborn xgboost scikit-learn`**


## Code Overview

The code performs the following steps:

- Import the required libraries (pandas, numpy, matplotlib, seaborn, xgboost, scikit-learn).
- Load the PJME hourly dataset and preprocess it.
- Visualize the energy use in MW over time.
- Split the dataset into training and test sets based on a specified date.
- Visualize the train/test split.
- Extract additional time-based features from the dataset.
- Visualize the relationship between features and the target variable.
- Create an XGBoost regression model.
- Train the model using the training set and evaluate its performance on the test set.
- Calculate and display the feature importance.
- Make predictions on the test set and merge them with the original dataset.
- Visualize the actual energy use and predicted values.
- Visualize a specific week of data, including the actual energy use and predictions.
- Calculate the RMSE score on the test set.
- Calculate and display the top 10 error values by date.

Feel free to modify and adapt the code according to your specific requirements.
## Installation

To use this code, follow the instructions below:

- Clone the repository:

**`git clone https://github.com/your_username/repository.git`**

- Install the required dependencies using pip:

**`pip install pandas numpy matplotlib seaborn xgboost`**

- Place the dataset file, **"PJME_hourly.csv"** in the same directory as the code file.



## Code Explanation

The provided code performs the following steps:

- Imports the necessary libraries for data manipulation, visualization, and modeling.

- Loads the **"PJME_hourly.csv"** dataset into a pandas DataFrame and sets the **'Datetime'** column as the index.

- Visualizes the energy use data as a line plot, providing an overview of the time series.

- Splits the dataset into training and test sets based on a specified date.

- Creates additional time-based features from the index, such as hour, day of the week, quarter, month, year, day of the year, day of the month, and week of the year.

- Visualizes the relationship between the newly created features and the target variable (energy use) using box plots.

- Trains an XGBoost regression model on the training set, using the specified features and target variable.

- Calculates and visualizes the feature importance, indicating the relative importance of each feature in the prediction model.

- Makes predictions on the test set using the trained model and merges the predicted values with the original dataset.

- Visualizes the actual energy use and the corresponding predictions using line plots.

- Further visualizes specific weeks of data, comparing the actual energy use and the predicted values.

- Calculates the root mean squared error (RMSE) score on the test set to evaluate the model's performance.

- Calculates and displays the top 10 error values, sorted by date, providing insights into the instances where the model deviates the most from the actual values.
## Usage

To use this code, follow these steps:

- Ensure that the required dependencies are installed (see the Installation section).

- Place the **"PJME_hourly.csv"** dataset file in the same directory as the code file.

- Run the code in your preferred Python environment.

## Contribution

Contributions to this code are welcome. If you would like to contribute, please follow these steps:

- Fork the repository.

- Create a new branch for your contribution.

- Make your modifications and improvements.

- Test your changes to ensure they work as expected.

- Submit a pull request with a clear description of your changes.
## Conclusion

This code provides a comprehensive analysis of energy use based on the PJME hourly dataset. By preprocessing the data, creating additional features, and training an XGBoost regression model, it offers predictions for energy use. The code also includes visualizations to help understand the patterns and relationships in the data.

Feel free to modify and adapt this code for your own projects. If you have any questions or feedback, please open an issue in the repository. I want to thank kaggle for providing with the dataset.


Happy analyzing!
## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License - see the LICENSE file for details.


## Related

Here are some related projects

- [Spotify_Analysis](https://github.com/RudraYug/Spotify_Analysis.git)

- [Tic_Tac_Toe](https://github.com/RudraYug/Tic_Tac_Toe.git)

- [Football_Prediction_Analysis](https://github.com/RudraYug/Football-Prediction-Analysis.git)

- [Flipkart_Web_Scraping](https://github.com/RudraYug/Flipkart_Web_Scraping.git)

- [Car_Prices_Prediction_Project](https://github.com/RudraYug/Car_Prices_Prediction_Project.git)