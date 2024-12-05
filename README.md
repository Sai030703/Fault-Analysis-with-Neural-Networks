# Fault-Analysis-with-Neural-Networks

# OVERVIEW 

This repository contains a Google Colab notebook that demonstrates the use of neural networks for fault classification in Tennessee Eastman Process Simulation Dataset. The notebook includes steps for exploratory data analysis, data preprocessing, and model training, along with evaluation metrics to assess the model's performance.


# Key Features
Exploratory Data Analysis (EDA) of process data.
Preprocessing steps including feature selection and scaling.
Training a neural network for fault detection and classification.
Detailed evaluation of model performance with metrics and visualizations.

# Dataset
The dataset used in this project is from Rieth et al. (2017), as referenced in the paper "Issues and Advances in Anomaly Detection Evaluation for Joint Human-Automated Systems."

Dataset Description
Format: .RData files
Content: Fault-free and faulty process data for training and testing.
Variables:
faultNumber: Indicates fault type (0 for normal, 1–20 for different fault conditions).
simulationRun: Randomized data samples for training and testing.
process variables: Columns 4–55 represent various system measurements.

# Acknowledgements

This project uses the dataset provided by Pacific Science & Engineering Group, Inc. The dataset is in the public domain and is available on Kaggle.It contains process variables for fault analysis in joint human-automated systems.

