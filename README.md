# Regression Analysis on Air Passenger Dataset

## Overview

This project performs regression analysis on the Air Passenger dataset to forecast future airline passengers. Using linear regression, the analysis examines historical trends and visualizes both actual and predicted values. The goal is to provide insights into air travel patterns and improve forecasting accuracy.

## Table of Contents

- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)

## Dataset

The dataset used in this project is the Air Passenger dataset, which contains monthly totals of international airline passengers from 1949 to 1960. It can be found [here](https://raw.githubusercontent.com/jbrownlee/Datasets/master/airline-passengers.csv).

## Installation

To run this project, you need to have Python installed on your machine along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/ahmdmohamedd/regression-analysis.git
   cd regression-analysis
   ```

2. Open the Jupyter Notebook or Python script included in this repository.

3. Run the code to perform regression analysis and visualize the results.

## Results

The analysis yields two key metrics for model evaluation:
- **Mean Absolute Error (MAE)**: A measure of average errors between predicted and actual values.
- **Root Mean Squared Error (RMSE)**: A metric that gives higher weight to larger errors.

The model's performance can be assessed through these metrics, and predictions can be visually compared to historical data.

## Visualization

The project includes visualizations of:
- Historical passenger numbers over time.
- Future predictions for the next 12 months.

These plots help in understanding trends and evaluating the forecasting capabilities of the regression model.
