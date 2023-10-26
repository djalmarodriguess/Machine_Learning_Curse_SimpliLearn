# Phishing Detector with Logistic Regression (LR)

## Introduction

This project aims to develop a machine learning model for the detection of phishing websites. Using a dataset that includes various website parameters, we will create a binary classification model to determine whether a given website is legitimate or a potential phishing site. Logistic Regression (LR) is the chosen algorithm for this task.

## Project Structure

- [Data](https://github.com/djalmarodriguess/Machine_Learning_Curse_SimpliLearn/tree/master/Datasets): Contains the dataset file used for the project.
- [Project](https://github.com/djalmarodriguess/Machine_Learning_Curse_SimpliLearn/blob/master/Practice%20Project%20II/Pratict%20Project%20II.ipynb): Python code for data analysis, model building, and evaluation.

## Dependencies

- Python 3.12.0
- Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn, and other relevant libraries.

## Data Source

The dataset used in this project contains website attributes and labels indicating whether a website is a phishing site (1) or not (-1).

## Analysis Tasks

1. **Loading and Preprocessing Data:**
   - Load the dataset from the provided source.
   - Explore and preprocess the data, including handling missing values and encoding categorical data.

2. **Data Splitting:**
   - Split the dataset into training and testing sets.

3. **Model Building:**
   - Implement a binary classification model using Logistic Regression.
   - Train the model on the training data.

4. **Model Evaluation:**
   - Make predictions on the test data.
   - Calculate and report the model's accuracy, and any other relevant evaluation metrics.
   - Optionally, visualize the results and decision boundaries.

## Results

The project has produced the following outcomes:

- **Part I - Using All Features:**
  - Accuracy: 0.92
  - Misclassified samples: 259

- **Part II - Using Two Features (Prefix_Suffix and URL_of_Anchor):**
  - Accuracy: 0.85

These results indicate that a model with more features (Part I) achieved a higher accuracy of 92%, but it also had more misclassifications. On the other hand, the simplified model with only two features (Part II) resulted in a lower accuracy of 85%.

## Visual Elements
Visual elements, such as plots and visualizations of model results, will be available in the [Project](https://github.com/djalmarodriguess/Machine_Learning_Curse_SimpliLearn/blob/master/Practice%20Project%20II/Pratict%20Project%20II.ipynb) documentation.

## Future Updates
This project is open to future improvements and updates. Some planned enhancements include:

**Feature Engineering:** Exploring new features and improving the feature selection process for better model performance.

**Hyperparameter Tuning:** Optimizing the LR model with hyperparameter tuning techniques.

**Model Comparison:** Evaluating the performance of other classification algorithms and comparing them to LR.

**Expanded Documentation:** Enhancing project documentation to provide more detailed insights and instructions for users.

## Feedback and Contributions
This project is open to feedback, suggestions, and contributions from the community. If you have ideas for improvement or would like to participate in enhancing this project, please feel free to reach out and contribute.
