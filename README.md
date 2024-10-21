# digits-_recognition_neural_network
 A digit recognition neural network is a type of neural network used to classify handwritten digits (0-9). One of the most well-known datasets for this task is the MNIST dataset, which consists of 28x28 pixel grayscale images of handwritten digits. Here's an overview of how you might build a digit recognition neural network using a common architecture:

Steps to Build a Digit Recognition Neural Network
1. Dataset Preparation (MNIST Dataset)
2. Neural Network Architecture
3. Activation Function- Used for hidden layers
4. Loss Function - Categorical Crossentropy is used as the loss function, as it works well with multi-class classification problems.
5. Optimizer- You can use optimizers like SGD  for training the model.
6. Training Process- Perform multiple epochs of training with batches of the data
   
Steps followed :
*We are importing tensorflow as keras 
*The module which works here is matplotlib numpy
*We are training two sets of values (x_train,y_train) and analysing the length of the values 
*Using matshow for representing the value 
And followed the same steps for the next value (y_train)
*Now the trained values are flattened with their shape and length 
*The model values are evaluated with optimizer 'Adam' for overcoming hiddenlayers 
*Then the import of seaborn for visualization for the following values 
*We use Flatten layer so that we don't have to call .reshape on input dataset
