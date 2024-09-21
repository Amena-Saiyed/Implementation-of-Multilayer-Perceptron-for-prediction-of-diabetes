Dataset
The dataset used is the Pima Indian Diabetes dataset, available from the LIBSVM dataset repository.

Model Architecture
Input Layer: Number of neurons equal to the number of features.
Hidden Layer: 10 neurons with ReLU activation.
Output Layer: 1 neuron with Sigmoid activation for binary classification.
Optimizers
The project compares three optimizers:

Adam: Adaptive learning rate and faster convergence.
Adagrad: Learning rate adjusts based on the frequency of updates.
SGD: Standard stochastic gradient descent.
Training
The model is trained using the Binary Cross-Entropy Loss (BCELoss) function over 200 epochs. The learning rate is set to 0.01 for all optimizers.

Evaluation
The model is evaluated using two metrics:
Accuracy: Proportion of correctly classified samples.
F1 Score: Harmonic mean of precision and recall, useful for imbalanced data.
