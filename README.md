# Neural_Network_Charity_Analysis

## Overview of Analysis

The goal of this project was to help the foundation predict where to make their investements using machine learning and neural networks. A binary 
classifier will be created that will be capable of predicting whether an investor will be successful if funded by Alphabet Soup.



## Results

### Data Prepocessing

* The IS_SUCCESSFUL variable is the target for the model
* The features are APPLICATION_TYPE, CLASSIFICATION, AFFILIATION, USE_CASE, ORGINIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, AND ASK_AMT
* EIN and NAME columns were removed as targets and features.




### Compiling, Training, and Evaluating the Model

For the Neural Netwrok Model it contained 3 layers. The first layer had eighteen neurons and used relu activation function. The second layer had eight neurons and the output
layer used the sigmoid activation function.  In total, there were 10 epochs used, but the model did not meet it's intent.

### Steps taken
* Increased neuron quantity
* Dropped ASK_AMT
* Added a new layer

## Summary
The model used only achieved an accuracy of 71.55%, which did not meet the intent. In order to achieve the performance in the model, I would recommmend
leveraging a different machine learning algorithm that can better handle variables by category or create multiple decision trees.