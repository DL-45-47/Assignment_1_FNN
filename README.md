## Assignment 1 - Feedforward Neural Network

### Algorithms included :
* **Gradient Descent**
* **Stocastic Gradient Descent**
* **Momentum Gradient Descent**
* **Nesterov Accelerated Gradient Descent**
* **RMSProp Gradient Descent**
* **Adam Gradient Descent**
* **Nadam Gradient Descent**

### Functionalities used :
* **forward_prop** - Apply forward propagation using weights and bias and return activation layer, preactivation layer and output layer values
* **backward_prop** - Apply backpropagation using activation layer, preactivation layer and output layer values and return gradient of weights and bias
* **init_w_and_b** - Initiate weights and bias
* **activation_func** - Based on choice of activation function, returns corresponding result of activation function
* **activation_func_derivative** - This function helps in calculation of derivative of activation function in backpropagation algorithm
* **softmax** - Calculate softmax function for output layer using pre-activation layer output
* **cross_entropy** - Calculate cross entropy loss on training set by applying L2-regularization
* **val_cross_entropy** - Calculate cross entropy loss on validation set by applying L2-regularization
* **get_accuracy** - Calculate accuracy on training set
* **val_get_accuracy** - Calculate accuracy on validation set
* **predict** - Uses input, weights and bias and returns vector of predicted probability corresponding to each class as result
