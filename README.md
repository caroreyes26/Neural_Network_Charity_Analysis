# Neural_Network_Charity_Analysis
## Overview of the analysis: Explain the purpose of this analysis.

In this analysis, machine learning and neural networks work together to predict if applicants will be successful if funded by Alphabet Soup. The CSV that was provided by Alphabet Soup's business team includes information on more than 34,000 organizations. Those organizations have received funding from Alphabet Soup.

Dataset provided includes the following information: 

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

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
* What variable(s) are considered the target(s) for your model? IS_SUCCESSFUL
* What variable(s) are considered to be the features for your model? APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
* What variable(s) are neither targets nor features, and should be removed from the input data? EIN and NAME columns

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why? two layers, 100 and 20 neuros, 120 epoch
* Were you able to achieve the target model performance? No - I was only able to achieve 73% 
* What steps did you take to try and increase model performance? I changed the layers and the epochs until it got closer to the target. 

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
