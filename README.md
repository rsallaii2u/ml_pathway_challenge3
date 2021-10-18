# ml_pathway_challenge3

## Overview

The purpose of this analysis is to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

The target IS_SUCCESSFUL is 1 if the applicant is successful and 0 otherwise.

## Results

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL

- What variable(s) are considered to be the features for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, and INCOME_AMT

- What variable(s) are neither targets nor features, and should be removed from the input data?
STATUS, SPECIAL_CONSIDERATIONS, and ASK_AMT (No relationship with IS_SUCCESSFUL)

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?

Layer1: 120 RELU

Layer2: 60 RELU

Layer3: 30 TANH

- Were you able to achieve the target model performance?
No.

- What steps did you take to try and increase model performance?
Enhanced data cleaning, tried different number of neurons, layers and activation functions.

## Summary

In summary the final model was able to achieve an accuracy of 72.5%.
However, this is not a significant improvement compared to a Logistic Regression that is more simple and interpretable.

There might be some data engineering steps that can potentialy improve the model or even capture aditional features.
