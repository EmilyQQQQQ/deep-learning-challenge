# deep-learning-challenge

Step 4: Write a Report on the Neural Network Model

1. Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis is to create a deep learning model using a neural network for Alphabet Soup, a nonprofit organization. The goal is to predict whether applicants will be successful if funded by Alphabet Soup based on various input features.

2. Results: Using bulleted lists and images to support your answers, address the following questions:

a) Data Preprocessing

Target Variable(s): The target variable for the model is IS_SUCCESSFUL, indicating whether the funding application was successful.
Feature Variable(s): The feature variables include all the input features except for EIN and NAME.
Variables Removed: EIN and NAME were removed from the input data as they are neither targets nor features.

b) Compiling, Training, and Evaluating the Model

Neural Network Architecture:
The model architecture consists of an input layer, two hidden layers with 10 and 5 neurons, respectively, and an output layer with 1 neuron using the sigmoid activation function.
The number of neurons and layers was chosen to create a simple yet effective model for the given classification problem.

Model Performance:
After training for 100 epochs, the model achieved an accuracy of approximately 72.6% on the test set.
The loss on the test set was around 0.558.

Target Model Performance:
The target model performance was not explicitly mentioned, but the achieved accuracy of 72.6% could be considered reasonable depending on the specific requirements.

Steps to Increase Model Performance:
Various strategies could be employed to enhance model performance:
Adjusting the neural network architecture by adding more layers or neurons.
Tuning hyperparameters such as learning rate, batch size, or the number of epochs.
Feature engineering or exploring other preprocessing techniques.
Trying different activation functions.

3. Summary:
The deep learning model demonstrates moderate success in predicting the success of funding applications. While the accuracy of 72.6% is decent, there is room for improvement. Experimenting with different neural network architectures, hyperparameter tuning, and exploring alternative models could potentially enhance performance.