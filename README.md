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

I use the following step to increase model performance
create more bins for rare occurrences in columns
add column NAME as a feature
add more neurons to a hidden layer
use different activation functions for the hidden layers.
Summary:
The overall results of the deep learning model slightly increased after many attempts of optimization from accuracy 0.7287463545799255 to 0.7540816068649292. The result can predict the 'IS_SUCCESSFUL' result for application evaluation. The dataset includes many features to be considered so it needs a machine learning ability to learn complex and non-linear relationships between the input features and the target.

However, the deep learning model is often considered a "black box" and hard to interpret, due to its complexity. Alternatively, we may use other machine learning algorithms, such as Decision Trees and Random Forests. The code 'AlphabetSoupCharity_Optimisation_ipynb' demonstrates these two models and achieved about 0.73/0.74 accuracy, which is slightly lower than the deep learning model but a bit easy to visualize.
