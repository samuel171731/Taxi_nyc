NYC Taxi Trip Duration Prediction

This repository contains code for predicting the duration of taxi trips in New York City using a Linear Regression model. The data preprocessing steps, model training, and evaluation are implemented using Python and popular machine learning libraries.
Table of Contents

    Installation
    Data
    Preprocessing
    Model Training
    Evaluation
    Usage
    Contributing
    License

Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/nyc-taxi-trip-duration-prediction.git
cd nyc-taxi-trip-duration-prediction

Create a virtual environment and activate it:

bash

python3 -m venv venv
source venv/bin/activate   # On Windows use `venv\Scripts\activate`

Install the required packages:

bash

    pip install -r requirements.txt

Data

The dataset used in this project is the NYC Taxi Trip Duration dataset. The data should be in CSV format and named NYC.csv.
Preprocessing

The preprocessing steps include:

    Removing trips with zero passengers and those with more than 6 passengers.
    Converting datetime columns to appropriate datetime formats.
    Extracting hour and minute features from the datetime columns.
    Encoding categorical variables.
    Dropping unnecessary columns.

Model Training

A Linear Regression model is trained using the processed features to predict the trip duration.
Evaluation

The model is evaluated using Root Mean Squared Error (RMSE).
Usage

    Ensure you have the NYC.csv file in the project directory.

    Run the script:

    bash

    python main.py

    The script will preprocess the data, train the model, and print the RMSE of the predictions on the test set.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
License

This project is licensed under the MIT License.
