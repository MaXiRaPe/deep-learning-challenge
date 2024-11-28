# deep-learning-challenge

## 1. Overview
The purpose of this challenge is apply machine learning and neural networks to create a binary classifier
that can predict the success of funding applicants funded by Alphabet Soup.

## 2. Results
(a) Data Processing
- What variable(s) are the targets for your model?
The target for the model is the "IS_SUCCESSFUL" column values.
- What variable(s) are the features for your model?
The columns: "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", 'USE_CASE", 'ORGANIZATION", "STATUS",
"INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT"
- What variable(s) should be removed from the input data because they are neither targets nor features?
The columns corresponding to the ID information, 'EIN' and 'NAME'.

(b) Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
Given the large amount of features to consider in the first part of the model, two inner layers were used
with 48 and
- Were you able to achieve the target model performance?
- What steps did you take in your attempts to increase model performance? 
