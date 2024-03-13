# Build Your Polynomial Regression Model

This project aims to introduce the concepts of polynomial regression through a hands-on, interactive approach. By implementing a polynomial regression model from scratch, users can explore the intricacies of machine learning algorithms, including forward and backward propagation, loss function computation, and the optimization process using gradient descent.

## Engine

We leverage a custom `Value` class to handle operations, gradients, and the automatic differentiation necessary for polynomial regression. This project draws inspiration and partial adaptation from Andrej Karpathy's [micrograd project](https://github.com/karpathy/micrograd).

## Hypothesis Class

The hypothesis class defines the polynomial regression model, capable of adjusting to different polynomial orders. It demonstrates how model parameters are initialized and combined to predict outputs based on polynomial features of inputs.

## Graph Visualization

Utilizing graph visualization, we can inspect the computational graph of operations, highlighting the forward and backward passes which are crucial for understanding how gradients are computed in deep learning models.

## Visualizing the Optimization

The project includes a section dedicated to visualizing how the polynomial regression model fits the synthetic data over iterations of gradient descent, offering insights into the optimization process.

## Numerical Optimization

An implementation of gradient descent from scratch shows how model parameters are updated iteratively based on the computed gradients of the loss function, emphasizing the importance of learning rates and convergence.

## Exercise

The project culminates with an exercise challenging users to enhance the model by incorporating multiple input features and employing numerical optimization to find the optimal model parameters.

By engaging with this project, users will gain a deeper understanding of polynomial regression, gradient descent, and the foundational principles of machine learning algorithms.

