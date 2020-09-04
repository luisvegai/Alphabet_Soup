
- How many neurons and layers did you select for your neural network model? Why?

The first neural network model I tried had 3 layers:
1 input layer, 1 hidden layer, and 1 output layer.
This is the standard for a first model to try.
The number of epochs were 50.
The number of neurons for the hidden layer was 80.
Since the number of inputs I have is equal to 38 (38 columns), I chose
a number of neurons between 2 or 3 times the number of inputs.
This model had an accuracy of 0.721



- Were you able to achieve the target model performance? 
What steps did you take to try and increase model performance?

After many tries, changing number of hidden layers, number of neurons per layer,
and activation functions such as relu, tanh, and leaky_relu, I could reach an accuracy of 0.727
The steps I did to try to increase the performance were:
  * Increasing the number of hiden layers by adding 2 extra layers.
  * Setting the number of neurons of the hidden layers to 80, 40, 5.
  * Setting the activation function to leaky relu for the hidden layers.
  * Increasing the number of epochs to 100

The resulting model increased the accuracy to 0.727



- If you were to implement a different model to solve this classification problem, which would you choose? Why?

I would choose to try SVM since SVMs are less prone to overfitting given that
they are trying to maximize the distance between the closest data points of the groups, 
rather than encompass all data within a boundary. The neural network model 
could be converging on a local minima.
