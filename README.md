deep-learning-challenge

Background The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

I used Co-lab for the challenge. I was unable to get this to work in my VS Code. Co-lab was the easier option.

Resources: Calss excercises for Module 21; https://keras.io/ site - Getting started with KerasTuner; StackOverflow posts- How to decide on activation function?, Understanding Keras Tuner; YouTube - ReLu in Action, Optimizing 3 parameters simultaneously, What is Activation function in Neural Network ? Types of Activation Function in Neural Network

Answers to challenge questions:

What variable(s) are the target(s) for your model? The target variable for the model is the "success" or "failure" of funding applicants

What variable(s) are the features for your model?

AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special considerations for application
ASK_AMT—Funding amount requested
What variable(s) should be removed from the input data because they are neither targets nor features? Variables removed: EIN and NAME

I was only able to achieve 73% target model performance which is below the requested 75%.

Steps taken to increase model performance:

Increasing the number of neurons and epochs enhances model expressiveness, allowing it to capture complex patterns. It also allows the model to refine its predictions and find better parameter values, which can lead to improved accuracy. If there is no balance with increasing epochs, overfitting can occur. 73% accuracy was acheived.

Adding more layers: Adding more layers can enhance the model’s capacity to capture intricate relationships within the data. Each layer learns different levels of abstraction, potentially improving accuracy. Deep models with multiple layers can create hierarchical representations, which is beneficial for complex problems. 73% accuracy acheived with this layer.

Using a different activation function (tanh for the second layer): incorporating an alternative activation function, such as tanh, the model’s interpretation and transformation of input data can be influenced. Activation functions exhibit distinct properties and can capture various non-linear patterns. Utilizing tanh introduces a different non-linearity, which may be better suited for addressing the specific problem, potentially resulting in improved accuracy. 73% accuracy acheieved witht his layer.

Using an automated optimizer, such as a hyperparameter tuner, involves systematically exploring different combinations of hyperparameters. These hyperparameters might include activation functions, the number of layers, the number of neurons, and the number of training epochs. By doing so, you can identify the optimal combination for your specific problem, potentially improving accuracy. I still only achieved 73% accuracy. Running this layer took the longest, almost 30 min.

Conclusion:

Being that I only achieved 73% accuracy, the following could be considered to imporve the performance:

Check data cleaning: ensure the data is properly cleaned which can be crucial to a models performance
Add more data: increasing the size of the data set could help the model learn from a larger and more diverse set of examples
Explore other alternative machine learning alogorithms
Experimenting with these steps could improve accuracy in classification tasks.
