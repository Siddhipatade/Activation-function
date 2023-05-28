# Activation-function

The activation function decides whether a neuron should be activated or not by calculating the weighted sum and further adding bias to it.
The purpose of the activation function is to introduce `non-linearity` into the output of a neuron. 

The neural network has neurons that work in correspondence with weight, bias, and their respective activation function. 
In a neural network, update the weights and biases of the neurons on the basis of the error at the output. 

This process is known as `Back-propagation`. Activation functions make the back-propagation possible since the gradients
are supplied along with the error to update the weights and biases. 
The activation function does the non-linear transformation to the input making it capable to learn and perform more complex tasks. 

## Variants of Activation Function 

#### 1. Linear Function
Equation : Linear function has the equation similar to as of a straight line i.e. `y = x`

Range : -inf to +inf

![image](https://github.com/Siddhipatade/Activation-function/assets/91780318/58f295e2-80a8-4af3-83aa-796e3ee98291)

### 2. Sigmoid Function
It is a function which is plotted as ‘S’ shaped graph.
Equation : 

    A = 1/(1 + e-x) 

Value Range : 0 to 1
Uses : Usually used in output layer of a binary classification, where result is either 0 or 1.
![image](https://github.com/Siddhipatade/Activation-function/assets/91782986/be4c3f43-b17a-484d-978f-b45087faa23e)


### 3. Tanh Function 
Equation :

![image](https://github.com/Siddhipatade/Activation-function/assets/91780318/ec1eb92d-d168-4f47-a9c7-e0013cd20c58)

Value Range :- -1 to +1
Nature :- non-linear
Uses :- Usually used in hidden layers of a neural network as it’s values lies between -1 to 1.

![image](https://github.com/Siddhipatade/Activation-function/assets/91780318/24ecb14a-15d3-4d46-af09-384e27bb34fc)

### 4. RELU Function 
It Stands for Rectified linear unit. It is the most widely used activation function. implemented in hidden layers of Neural network.
Equation :

    A(x) = max(0,x). 

It gives an output x if x is positive and 0 otherwise.

Value Range :- [0, inf)

![image](https://github.com/Siddhipatade/Activation-function/assets/91780318/49b60933-68ed-4aba-9619-a9e17b903dbe)

### 5. Softmax Function

The softmax function is also a type of sigmoid function but is handy when we are trying to handle multi- class classification problems.
Nature :- non-linear

![image](https://github.com/Siddhipatade/Activation-function/assets/91780318/f657ea19-edc0-402c-8f35-d49894565a54)

