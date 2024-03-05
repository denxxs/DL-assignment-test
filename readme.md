# Machine Learning Project on Loan Data

## Overview
This project involves developing a machine learning model using a deep learning approach to predict loan defaults based on various borrower characteristics. The dataset contains information about loan applicants and their financial history.

## Dataset
The dataset consists of 307,511 rows and 122 columns, featuring a mix of numeric and categorical data. Key columns include:
- `SK_ID_CURR`: Identifier for loan
- `TARGET`: Indicates if the loan was repaid (0) or not (1)
- Other features: Personal details of clients and information regarding their financial history.

## Preprocessing Steps
1. Handling missing values.
2. Encoding categorical variables.
3. Normalizing numerical features.
4. Splitting the dataset into training and test sets.

## Model Architecture
- A deep neural network with several dense layers.
- Activation function: ReLU for intermediate layers and sigmoid for the output layer.
- Dropout layers to prevent overfitting.

## Evaluation Metrics
- Accuracy
- ROC-AUC score
- Recall

## Usage
To run the machine learning model:
1. Load the dataset.
2. Apply the preprocessing steps.
3. Compile and train the deep learning model.
4. Evaluate the model performance on the test set.

## Requirements
- Python
- Pandas
- Scikit-Learn
- TensorFlow
- Matplotlib

**Note**: The code should be run in an environment where TensorFlow and the required libraries are installed, such as Google Colab.
