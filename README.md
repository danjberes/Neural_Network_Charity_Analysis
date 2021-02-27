# Neural_Network_Charity_Analysis

## Overview

This purpose of this analysis was to create a binary classifier that helps predict whether applicants will be able to make successful investments. Using the csv file provided, it would be converted into a binary classifier to help predict which applicants would end up being successful if funded by Alphabet Soup.

## Results

For data preprocessing there were several things to consider:
* For this model the target variable is "IS_SUCCESSFUL"
  * This variable shows us if the money was used effectively
* The feature variables were INCOME_AMT, CLASSIFICATION, and ASK_AMT
* The variables that are clutter are EIN, NAME, and ORGANIZATION as they likely do not contribute significant prediction factors.
* This model used 2 hidden layers
  * The activation functions that were used were RELU and SIGMOID
  * The amount of neurons were 20 and 10 for each hidden layer
* This model did not achieve the target model performance
* Removing several variables and adding an additional layer did not increase model accuracy

## Summary

Changing several variables only negatively impacted accuracy. While the model did not perform to the expectations set, there may be an optimal set of variables and layers that can reach the accuracy desired for this model.

