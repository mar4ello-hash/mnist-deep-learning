# mnist-deep-learning
Deep Learning with MNIST dataset

These tasks present three different techniques for ‘classification’ of a novel dataset.

The dataset is the AddNIST dataset from https://github.com/RobGeada/cvpr-nas-datasets. 
Each image is a composition of three MNIST digits one in each of the three colour channels.
Some examples are given in Figure 1. 

![lfQzzG7](https://user-images.githubusercontent.com/69586412/172048648-7e9566dd-13c6-4cb6-86cd-821535044065.png)

Figure 1: Examples of the AddNIST dataset. Each image (the large image) is made up of 
three MNIST images – one in each of the three colour channels. The label for the image is 
the sum of the three numbers and then subtract 1. So, for example the top left image is r=3, 
g=2, b=4 and the label is r+g+b-1 = 8. 

The dataset is constructed in such a way that there are only 20 possible ‘classes’ for the 
prediction – the numbers 0 through 19. In no scenario should the answers add up to less 
than zero or more than 19. 

Task 1: Train an MNIST Deep Learning network to recognise the digits 0 to 9 from MNIST

Task 2: Using a pre-built Deep Learning network

Task 3: Build your own Deep Learning network
