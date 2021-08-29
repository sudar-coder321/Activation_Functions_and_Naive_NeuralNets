# Activation_Functions_and_Naive_NeuralNetwork
This is a naive implementation of all important(significant :innocent:) activation functions and also a Neural Network from scratch by assiging manual weights to each of the neurons (Hidden)

## Analysis on various Activation Functions 

### Most Commonly used - 

- **Linear Function -** Linear activation functions are better in giving a wide range of activations and a line of a positive slope may increase the firing rate as the input rate increases.

- **Sigmoid -** When using a sigmoid activation function , a small change in the input only causes a small change in the output. 
  
  The pros are   
  #### 
   - function is differentiable.
  - monotonic
  - has a smooth gradient
  - has probablistic range of 0 to 1 (normalization)
  -  For X above 2 or below -2, tends to bring the Y value (the prediction) to the edge of the curve, very close to 1 or 0. This enables clear predictions.
 
   The cons are 
 
  #### 
    - The derivative values in the regions where y values react very little to the changes in x are very small and converge to 0.This is called the vanishing gradient and the learning is minimal. 
    - Outputs not zero centered.
    - Computationally more expensive
 
- **Hyperbolic Tangent(TanH) -**   It is used to predict or to differentiate between two classes but it maps the negative input into negative quantity only and ranges in between -1 to  1.The advantage is that the negative inputs will be mapped strongly negative and the zero inputs will be mapped near zero in the tanh graph.

#### **Behavioural Comparison between Linear, Sigmoid and Tanh**

![image](https://user-images.githubusercontent.com/60535124/131256417-2ba7275c-67a9-4245-9a38-5f4c5279c45f.png)


### Linear Unit Functions - 

- **Recitified Linear Unit(ReLU) -** 
  
- **Leaky ReLU -** 

**Exponential Linear Unit -** 

- **Parametric -** A value k ∈ {0, 1, 2, 3} is chosen uniformly at random, and k edges of the activation function graph are randomly selected. Multiplicative per-channel parameters are inserted at these edges and initialized to 1. Whereas evolution is well suited for discovering the general form of the activation function in a discrete, structured search space, parameterization makes it possible to fine-tune the function using gradient descent. 

- **Softplus -** 
 
- **Binary Step -** 

- **ArcTan -** 

- **Gaussian -** 

- **Swish -** 

- **Bipolar -** 
