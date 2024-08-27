# Deep Learning Challenge (Alphabet Soup)

## Overview of the analysis:

The purpose of this analysis is to understand the neural network process and identify how I can improve further models using this or other datasets.

## Results:

### Data Preprocessing

- What variable(s) are the target(s) for your model?
  - The (prediction) target for my model is IS_SUCCESSFUL, whether or not the given organization is successful.
- What variable(s) are the features for your model?
  - The input features (variables) are APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
- What variable(s) should be removed from the input data because they are neither targets nor features?
  - The variables removed are EIN and NAME as they are purely for identification purposes.

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - For the first pass, I used an input layer and one hidden layer both using the `relu` activation function with an output layer using the `sigmoid` function because this is a binary classification problem.
- Were you able to achieve the target model performance?
  - I was not able to achieve the target model performance.
- What steps did you take in your attempts to increase model performance?
  - To increase my model performance, I attempted adding another hidden layer, changing the activation functions, and increasing the amount of neurons my model had.

### Summary:

My model continued to have an accuracy of 72% with a loss of 55%. Each iteration of my model did not increase the performance. If I continue to explore this problem, I would use the keras-tuner to ease the burden of model optimization.
