# Coursera Project to classify Cats vs Non-Cats
## The detailed explanation of [Building](https://github.com/raghu826/Deep_Neural_Network/blob/master/Cats%20vs%20Non-Cats%20model/Building%20Neural%20Network.ipynb) and [Application](https://github.com/raghu826/Deep_Neural_Network/blob/master/Cats%20vs%20Non-Cats%20model/Application.ipynb) of the neural network model can be found in jupter notebooks.
#### Outline of the Assignment
To build your neural network, you will be implementing several "helper functions". These helper functions will be used in the next assignment to build a two-layer neural network and an L-layer neural network. 
Each small helper function you will implement will have detailed instructions that will walk you through the necessary steps. Here is an outline of this assignment, you will:
- Initialize the parameters for a two-layer network and for an  LL -layer neural network.
- Implement the `forward propagation module`.
    - Complete the LINEAR part of a layer's forward propagation step (resulting in  Z[l]Z[l] ).
    - We give you the `ACTIVATION function (relu/sigmoid)`.
    - Combine the previous two steps into a new [LINEAR->ACTIVATION] forward function.
    - Stack the `[LINEAR->RELU]` forward function L-1 time (for layers 1 through L-1) and add a `[LINEAR->SIGMOID]` at the end (for the final layer  LL ). This gives you a new L_model_forward function.
- Compute the loss.
- Implement the `backward propagation module`.
  - Complete the LINEAR part of a layer's backward propagation step.
  - We give you the gradient of the ACTIVATE function (relu_backward/sigmoid_backward)
  - Combine the previous two steps into a new [LINEAR->ACTIVATION] backward function.
  - Stack [LINEAR->RELU] backward L-1 times and add [LINEAR->SIGMOID] backward in a new L_model_backward function
- Finally update the parameters.


