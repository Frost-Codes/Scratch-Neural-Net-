# Creating a Neural Network from Scratch

We'll create the neural network using numpy python library. You need to be familiar with basic calculus concepts like:

  1. Power Rule
  2. Constant multiplier rule
  3. Product rule
  4. Quotient rule
  5. chain rule
  6. Derivative of exp and ln
  7. Partial Derivatives
  8. Matrix multiplication
  
## The basics of a neural net are:

  1. A forward pass where we multiply inputs(X/features) with the weights, add a bias then pass results through an activation function to introduce non-linearlity.
  
  2. Repeat step 1 util you get to output layer where you will use a function of your choice e.g softmax to tailor you output according to your requirements.
  
  3. Calculate the loss of the neural network i.e ``` Y_target - Y_predictions 1``` this tells you how far the neural nets predictions are from the true values
  
  4. Calculate the gradient of the loss with respect to the weights and bias for each layer (Calculus)
  
  5. Update weights and bias for each layer ``` w_new -= learning_rate * w_change ```
  6. Repeat 1-5 to fine tune model
  7. Use trained model to make predictions/generate new content

#### Learning rate defines the size of the step you take in gradient decent.
