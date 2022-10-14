# Neural Network Charity Analysis
## Overview of the analysis:
This analysis was created to make a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The following was made using a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. 

The following columns capture metadata about each organization:
* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special consideration for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

## Results:

### Data Preprocessing
#### What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL field.
#### What variable(s) are considered to be the features for your model?
ORGANIZATION, USE_CASE, STATUS, APPLICATION_TYPE, INCOME_AMT, AFFILIATION, SPECIAL_CONSIDERATIONS, CLASSIFICATION, ASK_AMT

#### What variable(s) are neither targets nor features, and should be removed from the input data?
EIN & NAME
### Compiling, Training, and Evaluating the Model
#### How many neurons, layers, and activation functions did you select for your neural network model, and why?
hidden_nodes_layer1 = 80, hidden_nodes_layer2 = 30, number_input_features = 43, 2 layers and Relu activation function 
#### Were you able to achieve the target model performance?
No I was not able to achieve the target model
 
## Summary:
The deep learning neural network model only reached an accuracy of 72.36% which was less than the required 75%.  Supervised machine learning models could be used or other classification models like the balanced random forest classifer which would generate a classified output worth comparing to the deep learning model.
