# Machine-Learning-iris-linear-regression
Predicting petal length from sepal length using Linear Regression | Iris dataset


# Predicting Petal Length using Linear Regression — Iris Dataset

## Overview
This project is part of my Machine Learning learning journey.
It demonstrates a simple Linear Regression model built using
the classic Iris dataset to predict petal length from sepal length.

## Dataset
- **Source:** Scikit-learn built-in Iris dataset
- **Total samples:** 150 flowers across 3 species
- **Input (X):** Sepal Length (cm)
- **Output (y):** Petal Length (cm)

## What I did
- Explored the data using scatter plots
- Found a strong positive correlation of 0.87 between sepal and petal length
- Split data into 80% training and 20% testing
- Trained a Linear Regression model
- Evaluated using Mean Squared Error (MSE): 0.58

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Key Findings
- The model performs reasonably well using a single feature
- MSE of 0.58 is acceptable given the scale of the data (1.0 to 6.9 cm)
- Model accuracy can be improved using multiple features

## Next Steps
- Multiple regression using all features
- Outlier detection and handling
- Explore classification models on the same dataset
