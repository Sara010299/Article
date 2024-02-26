# Gradient Boosting Classifier for Predicting Self-Harm Risk by enhancing sensitivity

## Project Overview

This project focuses on enhancing sensitivity in predicting the risk of future self-harm among individuals diagnosed with self-harm disorder. Utilizing a gradient boosting classifier (GBC) and clinical data, the model aims to provide accurate predictions of future self-harm incidents. The classifier is trained on a dataset of 2135 records from 64 individuals, featuring time series data on 8 emotions (happy, sad, angry, embarrassed, distressed, relaxed, guilty, and frustrated) along with the number of self-harm incidents.

## Features

- **Data Analysis:** Analysis of 8 emotions and self-harm incidents in a time series format.
- **Machine Learning Model:** Utilizes a gradient boost algorithm from Scikit-Learn to classify the risk of future self-harm.
- **Dataset:** The model is trained on a dataset consisting of 2135 records spread over 64 individuals, with a binary risk classification.
- **Sensitivity Calculation:** Included in the results to assess the model's performance accurately, with a test set separated from 13 of the 64 individuals to maintain proportionality in the self-injury column.

## Installation

1. Clone this repository.
2. Ensure Python 3.x is installed on your system.
3. Install required dependencies:

## Usage

To run the analysis:

1. Download your dataset in `.csv` format and place it in the project directory.
2. Execute the Jupyter Notebook `Final_work.ipynb`:

## Libraries Used

- Scikit-Learn for the gradient boost algorithm and model training.
- Pandas for data manipulation and analysis.
- NumPy for numerical operations.

## Model Performance

The model's performance is evaluated using sensitivity, specificity, and accuracy calculations, alongside a confusion matrix to compare predictions against actual labels.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
