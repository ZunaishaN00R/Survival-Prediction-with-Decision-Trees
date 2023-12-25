# Survival Prediction with Decision Trees
Built a decision tree model using Pclass, Sex, Age, and Fare from a CSV file to predict if a person would survive. Calculated the model score for assessment.

## Overview

This project involves the development of a decision tree model to predict the likelihood of survival for individuals based on key parameters. Leveraging a dataset provided in a CSV file, the model utilizes features such as `Pclass`, `Sex`, `Age`, and `Fare` to make predictions on whether a person would survive the Titanic disaster.

## Model Building

The project utilizes the following steps for building the decision tree model:

1. **Data Loading and Preprocessing:**
   - The dataset is loaded from a CSV file.
   - Rows with missing values in essential columns (`Pclass`, `Sex`, `Age`, `Fare`, `Survived`) are dropped.
   - The `Sex` column is label-encoded to convert gender to numerical values (0 for female, 1 for male).

2. **Feature Selection:**
   - The model is built using key features, including `Pclass`, `Sex`, `Age`, and `Fare`.

3. **Training the Decision Tree Model:**
   - The dataset is split into training and testing sets.
   - A Decision Tree Classifier is employed to train the model on the training set.

## Model Evaluation

The model's performance is assessed using accuracy as the metric on the testing set. The accuracy score provides an indication of how well the model predicts survival outcomes.

## Decision Tree Visualization

A visual representation of the decision tree is generated using the `plot_tree` function. This tree diagram offers insights into the decision-making process of the model.

## Project Structure

- **titanic.csv:** Dataset containing relevant information.
- **decision_tree_model.ipynb:** Jupyter Notebook with the complete code.
- **README.md:** Documentation providing an overview, code snippets, and usage instructions.

## Usage

1. Install the required libraries using `pip install -r requirements.txt`.
2. Run the code in `decision_tree_model.ipynb`.
3. Explore the decision tree visualization and accuracy score for model assessment.

