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
- How many neurons, layers, and activation functions did you select for your neural network model, and why? For my neural network model, I had 4 hidden layers. There were 100 neurons in the first layer, 80 neurons in the second layer
- Were you able to achieve the target model performance? No, 
- What steps did you take to try and increase model performance? On the first attempt, I removed some features including: 'STATUS', 'USE_CASE_CommunityServ', 'USE_CASE_Heathcare','USE_CASE_Other', 'USE_CASE_Preservation', and 'USE_CASE_ProductDev. Also, I made the test size equal to 0.30 or 30% of the data. With this attempt, I included three layers with units equal to 100, 60, and 35 respectively. With that attempt, it came to an accuracy of 0.6917 or 69.17%.

On the second attempt, I added a hidden layer with 10 units (or neurons) and with a different activation of "sigmoid." With this attempt, the accuracy came out to be 0.5169 or 51.69%. 

On the last attempt, I changed the test size to 0.20 or 20%. With this attempt, the accuracy increased slightly to 0.5200 or 52%.
