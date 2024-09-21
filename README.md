# Implementation of Multilayer Perceptron (MLP) for prediction of diabetes

- This project implements a Multilayer Perceptron (MLP) model using PyTorch to predict diabetes.
- It uses the Pima Indian Diabetes dataset, which is pre-processed, split into training and testing sets, and normalized for neural network training.
- The MLP architecture includes:
  - Input layer with neurons equal to the input features.
  - Hidden layer with 10 neurons and ReLU activation function.
  - Output layer with 1 neuron and Sigmoid activation for binary classification.
  
- The project compares the performance of three optimizers:
  - Adam
  - Adagrad
  - SGD
- Each optimizer uses a learning rate of 0.01, and the model is trained using Binary Cross-Entropy Loss (BCELoss) for 200 epochs.
- The training process is visualized through loss curves.
  
- After training, the model is evaluated on:
  - Accuracy
  - F1 score
  
- Results show that:
  - Adagrad achieves the highest accuracy.
  - All optimizers deliver competitive F1 scores.
  
- A Python script is provided to load the dataset, train the model, and visualize the performance results.

