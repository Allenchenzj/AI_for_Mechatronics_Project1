# AI_for_Mechatronics_Project1
This project aims to solve the famous fashion-minist classification problem by applying the neuro network layer.
The basic task applies the neuro network structure with only two fully-connected layers. The number of neurons at 
the hidden layer is 200. The tf.nn.relu was used as the activation function in the output of the hidden layer. There
are 10 epoches to train the model and within each epoch different batches of training data were processed progressively.
The final accuracy for the testing data is 88.9%. 

For the additional task, a convolutional neuro network structure was constructed to attempt the model. There are two 
convolutional layers after which the max pooling was applied. The filter size is 5*5 which makes the number of output
channel increase to 32 in the first convolutional layer and the increased to 64 in the second convolutional layer. Then 
two fully-connected layers were followed to process the image data after the convolutional structure. The hidden lay has 
1024 neurons. 
