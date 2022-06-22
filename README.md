# Module-19_Neural_Network_Charity_Analysis

## (1) Overview 
Using machine learning and neural network model to predict whether applicants will be successful if funded by Alphabet Soup.The dataset contains 34,000 organizations that have received funding from Alphabet Soup over the years.

## (2) Results                                                                     

### Data Preprocessing

- What variable(s) are considered the target(s) for your model?
  - The variable that are targeting in this model is the IS_SUCCESSFUL column.

- What variable(s) are considered to be the features for your model?
  - The features in all columns except EIN and NAME which we dropped are being considered.

- What variable(s) are neither targets nor features, and should be removed from the input data?
  - The features that were being dropped are the EIN and NAME columns. 

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

  - The optimized model is made with the inputfeatures, four hidden layers, and the output layer. The first hidden layer has 110 neurons, and the second one has 80, the third one has 40, the fourth one has 20, and the output layer has 1, The sigmoid activation seemed to work better for third hidden layer 3 (40 neurons) and forth hidden layer (20 neurons).

  ![image](https://github.com/sunnycywong/Module-19_Neural_Network_Charity_Analysis/blob/main/Deliverable%203.png)


- Were you able to achieve the target model performance?
  - No, the target for the model was to be 75% or abovem abd U was ibkt ve able to reach to 47%.

- What steps did you take to try and increase model performance?
  - I changed the activation type to "tanh" for all the hidden layers and changed activation on the output layer to "sigmoid". The model performanced increased to 73% which is much closer to the target. 

  ![image](https://github.com/sunnycywong/Module-19_Neural_Network_Charity_Analysis/blob/main/Deliverable%204.png)


## (3) Summary    

In the end the accuracy has gone up from 47% to 73%, which was a possible impact from updating the activation types. I would also believe that adding additional hidden layers with the right activiation type would increase the level of accuracy.




