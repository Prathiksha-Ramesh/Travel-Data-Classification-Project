# Travel Data Classification Project

## Overview

This project involves building and evaluating machine learning models for predicting outcomes using a travel-related dataset. The primary focus is on comparing the performance of different classifiers, specifically Random Forest and AdaBoost, through Receiver Operating Characteristic (ROC) analysis. The project includes data preprocessing, model training, and evaluation using ROC curves.

## Project Structure

- **notebook.ipynb**: Jupyter Notebook containing the full implementation, including data preprocessing, model training, and evaluation.
- **Travel.csv**: The dataset used for training and testing the models.
- **auc.png**: ROC curve plot for the Random Forest classifier.
- **auc_adaboost.png**: ROC curve plot for the AdaBoost classifier.
- **.gitignore**: Specifies files and directories to be ignored in the repository.
- **requirements.txt**: Lists all the Python packages required to run the project.
- **LICENSE**: Contains the licensing information for the project.

## Requirements

To run this project, the following Python packages are required:

- numpy
- seaborn
- matplotlib
- scikit-learn
- pandas
- xgboost

You can install the required packages by running:

```bash
pip install -r requirements.txt
```
## Dataset

The dataset used in this project, `Travel.csv`, contains various features related to travel data. The goal is to predict a specific outcome (e.g., whether a customer will purchase a travel package). The data is preprocessed and then used to train different classifiers.

## Models and Evaluation
Two models are evaluated in this project:

1. Random Forest Classifier

The ROC curve for this model is saved as `auc.png`.
This model's performance is evaluated by its area under the ROC curve (AUC).
AdaBoost Classifier

The ROC curve for this model is saved as `auc_adaboost.png`.
Like the Random Forest model, this classifier is evaluated by its AUC.
Both models are evaluated using the ROC curve, which plots the True Positive Rate (Sensitivity) against the False Positive Rate (1-Specificity) across different threshold values.

## How to Run
To run the project:

- Clone this repository to your local machine.
- Ensure you have the necessary Python packages installed by running `pip install -r requirements.txt`.
- Open the notebook.ipynb file in Jupyter Notebook.
- Follow the steps in the notebook to preprocess the data, train the models, and evaluate their performance using the ROC curves.

## Results
The ROC curves demonstrate the performance of the Random Forest and AdaBoost classifiers. The AUC values are used to compare the models, with higher AUC indicating better model performance.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
The dataset used in this project was obtained from [source, if applicable].
Special thanks to the developers of scikit-learn, pandas, and xgboost for providing excellent tools for machine learning and data analysis.