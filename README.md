# Neural_Network_Charity_Analysis

## Overview of Analysis
The business team from Alphabet Soup approached Beks with a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within the dataset, there are a number of columns that capture metadata about each organization; these include:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

With our knowledge of machine learning and neural networks, we will use the features in the dataset to help Beks create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup. 

## Results
### Data Preprocessing
- What variable(s) are considered the target(s) for your model? The variable considered the target for this model is the IS_SUCCESSFUL column. 
- What variable(s) are considered to be the features for your model? The variabes considered to be features for this model are Application type and Classification. 
- What variable(s) are neither targets nor features, and should be removed from the input data? The recommended columns to drop during this project were EIN and NAME. They have no effect on our data. 
### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why? For my neural network model, I had 2 hidden layers. There were 80 neurons in the first layer and 25 neurons in the second layer. 
- Were you able to achieve the target model performance?
- What steps did you take to try and increase model performance?
