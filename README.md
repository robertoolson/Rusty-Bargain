# Rusty Bargain Used Car Value Analysis

## Project Description

Rusty Bargain faces a challenge in enhancing its platform with a feature that can provide immediate, accurate car valuations. This project undertakes the task of creating a predictive model capable of estimating a car's market value based on its characteristics. The quality of prediction, speed of prediction, and training time are the project's priorities, intending to streamline the process of selling or purchasing used vehicles through Rusty Bargain.

## Installation

To set up this project locally, follow these steps:

```bash
git clone https://github.com/your_username/your_project.git
cd your_project
pip install -r requirements.txt
```

## Models Evaluated

Linear Regression: Serves as a baseline model for sanity checks.
Decision Tree: A simple model to capture non-linear patterns without extensive parameter tuning.
Random Forest: An ensemble method for higher accuracy through bootstrapping and feature randomness.
LightGBM: A gradient boosting framework that uses tree-based learning algorithms, known for its speed and efficiency.

## Key Findings

Model Accuracy: LightGBM demonstrated the best balance between prediction accuracy and computational efficiency, with a Root Mean Squared Error (RMSE) of 1703.92.
Prediction Speed: Decision Tree was the fastest model in making predictions, followed closely by Linear Regression, making them suitable for applications requiring quick responses.

## Requirements

For a complete list of the Python packages needed to run the models, refer to the requirements.txt file.