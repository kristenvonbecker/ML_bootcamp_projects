# Logistic Regression

This dataset has columns for gender, weight, and height. The idea is predict gender from the height and weight features.

Outline:
- Reading in CSV data using Pandas
- Scatterplot of weight by height, color-coded by gender (you guessed it: blue for boys and red for girls)
- Classification using Sci-kit-learn's `LogisticRegression()` model
- Tuning the model using K-fold cross-validation over some parameter space
- The math (including probability) behind logistic regression
