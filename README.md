# Neural Network for Multiclass Classification - Coded from Scratch in Python

This project used MNIST Dataset from Keras for coding a Neural Network from scratch for a N layer neural network for multiclass classification. It features the following: 
- Vectorization
- Only iterations (no convergence condition)
- Multi-class problem - used softmax and cross entropy
- Code works for any number of hidden layers provided as input
- L2 regularization

The training function takes as input: X, y, max_iter=1000, alpha=0.01, and hidden_layers. Data has been splitted into training and test. Error curves have been plotted for training and validation errors (cost and accuracy):
- for different number of hidden layers (1, 2, 3, 4, 5, etc)
- for different alpha values (choosing the "best" hidden layer configuration from the previous item)
- for different values of lambda (regularization parameter)

Outcome:
Summary
The configuration with the network 1 hidden layer worked best among all. Models with multiple hidden layers work better for the datasets that have so many features. I also get better result for the model with learning parameter, alpha = 0.1; it means the model reaches its gradient descent either too slow with smaller values of alpha and fulctuates highly with higher values of alpha. For the regularization parameter, lambda = 5 provided the best result. For the rest of the values, the weight decay was more than optimum for the model.
