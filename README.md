# deep-learning-challenge
Overview of the Analysis:
The purpose of this analysis is to develop a binary classifier using neural networks to predict whether applicants will be successful if funded by Alphabet Soup. By training a neural network on this data, we aim to create a model that can accurately classify applicants as either successful or unsuccessful, helping Alphabet Soup select the applicants with the best chance of success for funding.

## Results:

### Data Preprocessing:

#### Target Variable: The target variable for our model is the IS_SUCCESSFUL column, indicating whether an applicant was successful if funded.

#### Features: All columns except for the target variable (IS_SUCCESSFUL) are considered features for our model.

#### Variables to be Removed: The variables 'EIN' and 'NAME' were removed from the input data as they are neither targets nor features.

### Compiling, Training, and Evaluating the Model:

####  For the neural network model, I selected the following architecture:

##### First hidden layer: 80 neurons with ReLU activation function.
##### Second hidden layer: 30 neurons with ReLU activation function.
##### Output layer: 1 neuron with sigmoid activation function.
I chose these numbers based on experimentation and common practices in designing neural networks.

#### Achievement of Target Model Performance: The target model performance was evaluated based on accuracy and loss metrics during training. Model ran and achieved desired scores.


#### Summary:

In summary, the deep learning model developed achieved satisfactory performance based on the evaluation metrics. However, there may be room for further optimization to enhance performance. Considering the goal of helping Alphabet Soup select applicants with the best chance of success, the model can serve as a valuable tool in the decision-making process.
