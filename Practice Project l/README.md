# California Housing Price Prediction

## Introduction

This project is my endeavor to predict median house values in California using the provided dataset, which encompasses various features related to housing. I've embarked on a regression task with the primary goal of predicting housing prices based on attributes such as median income, location, and house characteristics.

## Project Structure

- [Data](https://github.com/djalmarodriguess/Machine_Learning_Curse_SimpliLearn/blob/master/Datasets/housing.csv): Contains the dataset file, "housing.csv."
- [Project](https://github.com/djalmarodriguess/Machine_Learning_Curse_SimpliLearn/blob/master/Practice%20Project%20l/Practice%20Project%20l.ipynb): Python code for data analysis and model building.

## Dependencies

- Python 3.12.0
- Libraries: numpy, pandas, scikit-learn, matplotlib, seaborn

## Data Source

The dataset used in this project is sourced from the US Census Bureau, providing information on various metrics related to housing in California.

## Analysis Tasks

1. **Load the Data:**
   - I start by reading the "housing.csv" file.
   - I print the first few rows of the dataset.
   - I extract input (X) and output (Y) data.

2. **Handle Missing Values:**
   - To maintain data integrity, I fill missing values with the mean of the respective column.

3. **Encode Categorical Data:**
   - I convert categorical columns to numerical data for model compatibility.

4. **Split the Dataset:**
   - I split the data into an 80% training dataset and a 20% test dataset.

5. **Standardize Data:**
   - To ensure consistent scaling, I standardize both training and test datasets.

6. **Perform Linear Regression:**
   - I train a Linear Regression model on the training data.
   - I predict output for the test dataset.
   - I print the root mean squared error (RMSE).

7. **Perform Decision Tree Regression:**
   - I train a Decision Tree Regression model on the training data.
   - I predict output for the test dataset.
   - I print RMSE for Decision Tree Regression.

8. **Perform Random Forest Regression:**
   - I train a Random Forest Regression model on the training data.
   - I predict output for the test dataset.
   - I print RMSE for Random Forest Regression.

## Results

The Random Forest Regression model outperforms the Linear Regression and Decision Tree Regression models for this specific problem. It has the lowest mean absolute error and root mean squared error and the highest R² score.

## Visual Elements

For detailed visualizations and plots of the results, please refer to the project's documentation in the [Project](https://github.com/djalmarodriguess/Machine_Learning_Curse_SimpliLearn/blob/master/Practice%20Project%20l/Practice%20Project%20l.ipynb) file.

## Future Updates

I'm committed to continually improving this project and adding new features. Here's what you can expect in future updates:

- **Improved Handling of Missing Values:** I plan to explore more advanced techniques for handling missing values, ensuring our dataset is cleaner and more accurate.

- **Outlier Detection and Removal:** I will implement robust outlier detection methods and procedures for removing outliers, enhancing the overall model's robustness.

- **Expanded Data Exploration:** Future updates will include a more in-depth exploratory data analysis (EDA) with additional visualizations and detailed insights into the dataset.

- **Model Enhancements:** I'll be working on fine-tuning existing models and exploring new machine learning algorithms to further improve prediction accuracy.

- **Feature Engineering:** I aim to enhance feature engineering techniques to capture more nuanced patterns in the data.

- **Optimized Documentation:** I plan to expand our documentation to provide more comprehensive information about the project, its goals, and how to use it effectively.

- **Enhanced Visual Elements:** Expect more detailed plots and visualizations that will make it even easier to understand the results of our analysis.

I'm open to suggestions and contributions from the community, so if you have ideas or want to help improve this project, please feel free to reach out and contribute.
