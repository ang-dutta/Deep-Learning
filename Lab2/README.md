## Lab 2: MNIST Digit Recognition & Hyperparameter Tuning

This assignment focuses on building and refining Convolutional Neural Networks (CNN) for handwritten digit classification. The primary goal is to observe how different architectural choices affect model performance.

### Assignment Details
* Questions: Assignment2.pdf
* Solutions: U23AI006_DL_lab2.ipynb

### Key Tasks & Experiments

#### 1. The Activation Function Challenge
Compare training loss and accuracy curves using Sigmoid, Tanh, and ReLU. Observe the effects of vanishing gradients and documentation of convergence speeds.


#### 2. The Optimizer Showdown
Keep the best activation function constant and switch between SGD, SGD with Momentum, and Adam to observe stability and accuracy gains.


#### 3. Regularization & Normalization Scenarios
Evaluate the contrast between models without Batch Normalization and Dropout, models with low Dropout (0.1), and models with both Batch Normalization and standard Dropout (0.25).