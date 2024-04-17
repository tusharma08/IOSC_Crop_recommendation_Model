# Crop Recommendation Model

This repository contains the code for a crop recommendation model. The model is designed to predict the best crop to be cultivated based on various environmental factors such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall.

## Project Overview

The goal of this project is to build a predictive model that can accurately recommend the best crop to be cultivated under specific environmental conditions. This model can be useful for farmers and agricultural consultants to make informed decisions about crop selection.

## Data

The dataset used for this project is a crop recommendation dataset, which includes features such as:

- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- pH
- Rainfall
- Label (crop name)

The dataset is loaded from a CSV file named `Crop_recommendation.csv`.

## Models

Multiple models are used in this project to compare their performance in predicting the best crop to be cultivated. The models include:

- Logistic Regression
- Naive Bayes
- Support Vector Machine
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- Bagging
- AdaBoost
- Gradient Boosting
- Extra Trees

## Results

The model's performance is evaluated using the accuracy score. The results are compared between the models to determine which one performs better in predicting the best crop to be cultivated.

## How to Run

1. Clone this repository.
2. Install the required Python packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `sklearn`.
3. Run the Jupyter notebook `crop-recommendation.ipynb` to execute the code and see the results.

## Contributing

Contributions are welcome. Please feel free to submit a pull request or open an issue to discuss potential improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
