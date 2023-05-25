# deep-learning-challenge

## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

* EIN and NAME—Identification columns
* APPLICATION_TYPE—Alphabet Soup application type
* AFFILIATION—Affiliated sector of industry
* CLASSIFICATION—Government organization classification
* USE_CASE—Use case for funding
* ORGANIZATION—Organization type
* STATUS—Active status
* INCOME_AMT—Income classification
* SPECIAL_CONSIDERATIONS—Special considerations for application
* ASK_AMT—Funding amount requested
* IS_SUCCESSFUL—Was the money used effectively

### Data Preprocessing
#### What variable(s) are the target(s) for your model?

The target for the model is 'IS_SUCCESSFUL'.

#### What variable(s) are the features of your model?

The feature for the model is 'APPLICATION_TYPE',' AFFILIATION', 'CLASSIFICATION', 'USE_CASE',' ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT'.

#### What variable(s) should be removed from the input data because they are neither targets nor features?

The variables that should be removed are 'EIN'.
Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why?

The neural network model included: 67 neurons, 3 hidden layers, and 3 activation functions (relu, tanh, sigmoid). (See Attached photo for details)
![Data_model](https://github.com/SMKSmith/deep-learning-challenge/assets/117343047/84379b0f-5497-45a4-a75a-fb5788f3a1bd)

#### Were you able to achieve the target model’s performance?

No, the highest model performance I achieved was Accuracy: 0.7374635568513119,

#### What steps did you take in your attempts to increase model performance?

The following steps I used to increase the model performance was adding additional bins for outliers in columns. Then 
added the column 'NAME' as a feature. Additional neurons were added to a hidden layer. Three different activation functions were used in total, a different function for each hidden layer.
Once the model was configured and run the variables within the model were re-evaluated to attempt to increase the performance.

## Summary
The results of the deep learning model showed a marginal increase after several optimization attempts. The range of accuracy was 0.7308454513549805 to 0.7374635568513119. The result can predict the 'IS_SUCCESSFUL' result for the application evaluation, however is under the acceptable .75 accuracy. The dataset provided contained quite a few features that can be used to data model and requires maschine learning due to the complexity. In addition to the algorithim, two other methods were used to test the data modeling. This was tested to ensure the most effective and accurate model.
