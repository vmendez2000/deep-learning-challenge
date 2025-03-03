# deep-learning-challenge
# Alphabet Soup Charity Success Prediction
## Overview
### This project is focused on developing a deep learning model that predicts the success of funding applications for a nonprofit organization called Alphabet Soup. The goal is to use machine learning techniques to predict whether a funding application will be successful based on a variety of features related to each application. The model is trained using a neural network architecture, and different optimization methods are applied to improve performance.

## Requirements
### The following libraries are required to run this project:
* pandas
* tensorflow
* scikit-learn
* matplotlib (optional for visualizations)

## File Structure

#### │── README.md                            # This file
#### │── AlphabetSoupCharity.h5               # Original model saved in HDF5 format
#### │── AlphabetSoupCharity_Optimization.h5  # Optimized model saved in HDF5 format
#### │── Report.txt                           # Text file of project report
#### │── AlphanerSoupCharity_Optimization,ipynb # Jupyter Notebook
#### └── Module_21_Challenge.ipynb            # Jupyter Notebook

## Project Workflow
### 1. Data Preprocessing
* The dataset is loaded from a CSV file.
* Unnecessary columns like EIN and NAME are dropped.
* Categorical variables are one-hot encoded.
* Features are scaled using StandardScaler.
### 2. Model Training
* A neural network is created using TensorFlow/Keras.
* The model consists of an input layer, hidden layers, and an output layer with a sigmoid activation function for binary classification.
* The model is compiled with the Adam optimizer and binary cross-entropy loss.
* Early stopping, dropout layers, and learning rate reduction are used to optimize performance and prevent overfitting.
### 3. Model Evaluation
* The model's accuracy is evaluated using a test dataset.
* The model is saved in an HDF5 file format for future use.
### 4.Model Optimization
* An optimized model is created by adding regularization techniques such as dropout and learning rate scheduling.
* The optimized model is trained and evaluated using the same test dataset.

## Code Source and Acknowledgements
* The structure and foundation of the code were created by me for this project. However, some code snippets were sourced from the following locations to help with preprocessing and model architecture:
    * Stack Overflow: For solutions related to handling missing data, encoding categorical variables, and implementing callbacks.
    * TensorFlow/Keras Documentation: For implementing the neural network architecture and optimization techniques.

## References
#### IRS. Tax Exempt Organization Search Bulk Data Downloads. IRS website
## Resources
#### ChatGBT was used to help complete this project. 

