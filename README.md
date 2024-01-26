# Wine Classification with Naive Bayes

This repository demonstrates the application of Naive Bayes classifiers on the Wine dataset using scikit-learn. The dataset comprises chemical analysis results of wines, and the goal is to predict the wine's class.

## Contents

1. **Data Loading and Exploration:**
   - The Wine dataset is loaded using scikit-learn's datasets module.
   - A pandas DataFrame is created for easier data manipulation and analysis.

2. **Data Splitting:**
   - The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn.

3. **Gaussian Naive Bayes:**
   - A Gaussian Naive Bayes classifier is applied to the training data.
   - Model accuracy is evaluated on the test set.

4. **Multinomial Naive Bayes:**
   - A Multinomial Naive Bayes classifier is applied to the same dataset.
   - Model accuracy is evaluated on the test set.

5. **Prediction Example:**
   - The Gaussian Naive Bayes model is used to make predictions for a specific data point.

## Usage

- Clone the repository and run the provided Jupyter notebook to see the code in action.
- Experiment with different Naive Bayes classifiers and explore the dataset.

## Dependencies

- scikit-learn
- pandas
- Jupyter notebook environment

## Note

- The code ensures correct data splitting and provides accuracy scores for both Gaussian and Multinomial Naive Bayes models.
- It also demonstrates making predictions using the trained model for a specific data point.

Feel free to use, modify, and contribute to this repository. Happy coding!
