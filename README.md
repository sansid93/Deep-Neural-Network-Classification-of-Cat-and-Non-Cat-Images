## Deep Neural Network to classify between cat and non cat Images
Developed a 4 layer neural network to classify cat and non cat images with 80% accuracy. RELU was used as an activation function for the hidden layers and Sigmoid function has been used as an activation layer for the output layer

#### The below are the parameters for the neural networks
* Train_x's shape: (12288, 209)
* Test_x's shape: (12288, 50)
* No of Hidden layers: 3
* No of Epochs: 2500
* Learning rate: 0.0075

#### Result Analysis:
A few types of images that the model tends to do poorly on include the following,

* Cat body in an unusual position
* Cat appears against a background of a similar color
* Unusual cat color and species
* Camera Angle
* Brightness of the picture
* Scale variation (cat is very large or small in image)
* Hope to improve the model by tuning the hyperparameters and by using regularization.


