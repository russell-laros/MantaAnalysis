# Manta Ray Sighting Analysis Project
This GitHub repository contains a comprehensive analysis of Manta Ray sightings using data sourced from a Google Calendar. The project includes data transformation, exploratory data analysis, missing data imputation, time series analysis, and insights derived from the analysis. The repository also contains suggestions for future analysis using regression and integration with atmospheric and oceanic weather data APIs.

## Objective
Analyze the Manta Ray sighting data to uncover patterns, trends, and insights that can help understand the factors influencing the sightings and predict future occurrences.

## Dataset Overview
The dataset used for this project is transformed from a Google Calendar, resulting in a 2-column dataset with one column for date and the other for sightings.

## Analysis Steps
* Transform data from a Google Calendar into a 2-column dataset with columns for date and sightings.
* Perform exploratory data analysis to understand the dataset, identify any issues, and explore the relationships between variables.
* Impute missing data, if any.
* Conduct time series analysis:
* * Smoothing
* * Kalman filtering
 - Seasonal decomposition
 - Check for stationarity
 - ARIMA model
 - LSTM model with PyTorch
 - Facebook's Prophet model
 - Write out the results and insights derived from the analysis.
 - Share thoughts on future analysis using regression and integration with atmospheric and oceanic weather data APIs.

## Repository Structure
* data/: Contains the original dataset and any processed datasets.
* notebooks/: Contains the Jupyter Notebook(s) with the analysis, code, and visualizations.
* models/: Contains trained models and model-related files.
* README.md: This file, containing a summary of the project and its structure.

## How to Run the Analysis
* Clone the repository to your local machine.
* Install the required Python packages by running pip install -r requirements.txt.
* Open the Jupyter Notebook in the notebooks/ directory and run the cells in order.

## Dependencies
* Python 3.9
* pandas
* numpy
* matplotlib
* statsmodels
* pykalman
* pmdarima
* torch
* fbprophet
* jupyter

## Contributing
Please feel free to submit a pull request or open an issue if you have suggestions for improvements or find any bugs.

## License
This project is licensed under the MIT License.
