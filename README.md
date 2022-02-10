# MLP-MNIST
Multilayer Perceptron for identifying digits, MNIST dataset


#The model is compiled with the loss function as categorical crossentropy 
#which is generally used for multi-class classification models and produces a one-hot array containing the possible match for each category.
#The optimizer is Adam which is a stochastic gradient descent method. The metric used for judging the performance of the model is accuracy.

# the input data is passed, the numeber of epochs = 20 which represents the hyperparameter that defines the number of time that the algorithm will work
# the batch size = 350 which defines the number of samples to work through before updating internal parameters. 
#verbosity = 1 which means its a progress bar
# validation split which represents a fraction of the training data to be used as validation data.
