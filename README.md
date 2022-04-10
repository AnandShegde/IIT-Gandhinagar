# SRIP - tasks

Tasks given By Prof. Nipun Batra

### Steps for running the files:
clone the repository.

All the files except Neural Network for MNIST dataset.ipynb will run directly in google colab.
For Neural Network for MNIST dataset.ipynb, extract the contents from mnist_train.csv.zip to the same directory where Neural Network for MNIST dataset.ipynb is present and run the code.


## 1. Animating bivariate normal distribution
Run the code Bivariate Gaussian Visualizer.ipynb.

![image](https://user-images.githubusercontent.com/79975787/162630369-19168bbb-fec5-4e44-b295-37a4946e08b6.png)

Use the widgets to change mean and Covariance to visualize bivariate guassian for yourself.

## 2. Sampling method to draw samples from a multivariate Normal (MVN) distribution
Multivariate Gaussian Sampling.ipynb is for drawing samples from MVN distribution. It can generate Samples from MVN for any dimensions.

## 3. Implement two hidden layers neural network classifier from scratch in JAX
Implemented neural network to classify the data 
Got a test set accuray of 91.50% on the test set by training the neural network. 

![image](https://user-images.githubusercontent.com/79975787/162632036-514d6289-1b0e-4760-a2be-e283ae1e9fa9.png)

## 4. Bayesian Linear Regression from scratch with BlackJAX
Generated synthetic 1d linear dataset with added noise.

Used Baysian linear regression to get the distribution for the Parameters using

<ul>
  <li>analytical solution</li>
  <li>Sampling using BlackJAX.</li>
</ul>

plotted the results.

![image](https://user-images.githubusercontent.com/79975787/162631914-4d2cba8b-25fe-41d2-b86b-9b577c39b61b.png)





