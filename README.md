# Sonar_Data-Classification-with-Logistic_Regression
# Sonar Data Classification with Logistic Regression

This project utilizes logistic regression to classify sonar signals as either rocks (R) or mines (M) based on various features. The dataset used in this project is available as `sonar_data.csv`.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Dependencies](#dependencies)
4. [Results](#results)
5. [Contributing](#contributing)

## Introduction
Sonar data classification is a classic machine learning problem where the goal is to differentiate between objects (in this case, rocks and mines) based on sonar signals. Logistic regression is employed as a classification algorithm due to its simplicity and effectiveness in binary classification tasks.

## Project Structure
- `README.md`: The file you're currently reading, providing an overview of the project.
- `sonar_data.csv`: Dataset containing sonar signal features and corresponding labels (R for rocks, M for mines).
- `sonar_classification.py`: Python script containing the code for data preprocessing, model training, and inference.

## Dependencies
- `numpy`: For numerical computations and array manipulations.
- `pandas`: For data manipulation and analysis.
- `scikit-learn`: For machine learning algorithms and tools.



## Results
After training the logistic regression model on the sonar data, we achieved the following results:
- Training Data Accuracy: 83%
- Test Data Accuracy: 76%

Based on the trained model, you can also make predictions for new sonar signals.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.
