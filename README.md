# deep-learning-challenge

Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

I used Co-lab for the challenge.  I was unable to get this to work in my VS Code.  Co-lab was the easier option.

Resources: Calss excercises for Module 21; https://keras.io/ site - Getting started with KerasTuner; StackOverflow posts- How to decide on activation function?, Understanding Keras Tuner; YouTube - ReLu in Action, Optimizing 3 parameters simultaneously, What is Activation function in Neural Network ? Types of Activation Function in Neural Network


Answers to challenge questions:

What variable(s) are the target(s) for your model?
The target variable for the model is the "success" or "failure" of funding applicants

What variable(s) are the features for your model?
Information about the applicanIt included; classification, application type, affiliation, organization, status etc.

What variable(s) should be removed from the input data because they are neither targets nor features?
Variables removed: EIN and NAME

I was only able to achieve 73% target model performance which is below the requested 75%.

Steps taken to increase model performance:

1> Increase the number of neurons and epoch: Increasing the number of neurons in a layer enhances the model’s expressiveness, enabling it to capture intricate data patterns. This refinement also improves parameter estimation, potentially leading to better accuracy. However, striking a balance is crucial, as excessive epochs can result in overfitting. In my case, I achieved a 73% accuracy


