# EVA8 - Phase1-Session2.5-PyTorch101
A neural network that takes : 2 inputs:

An image from the MNIST dataset (say 5), and
A random number between 0 and 9, (say 7)
and gives two outputs:
The "number" that was represented by the MNIST image (predict 5), and The "sum" of this number with the random number and the input image to the network (predict 5 + 7 = 12)

![image](https://user-images.githubusercontent.com/15637770/211095063-934b1bfe-4128-4467-b493-0ec36dbfd73f.png)

#Training log
Epoch 1 : 
Train set: Average loss: 1.0943
Test set: Average loss: 0.004, MNIST Accuracy:98.44, Addition_Accuracy:45.91

Epoch 2 : 
Train set: Average loss: 0.4699
Test set: Average loss: 0.002, MNIST Accuracy:99.04, Addition_Accuracy:94.78

Epoch 3 : 
Train set: Average loss: 0.1508
Test set: Average loss: 0.001, MNIST Accuracy:99.22, Addition_Accuracy:98.99

Epoch 4 : 
Train set: Average loss: 0.0900
Test set: Average loss: 0.000, MNIST Accuracy:99.21, Addition_Accuracy:99.0

Epoch 5 : 
Train set: Average loss: 0.0595
Test set: Average loss: 0.000, MNIST Accuracy:99.4, Addition_Accuracy:99.29
