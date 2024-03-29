# CNN_Dog-Cat_Classification

Here I have used Convolutional neural networks to implement cats vs dogs classifier. This entire project is done using keras in TensorFlow.

Special thanks to: Laurence Moroney, Andrew ng.
![Gif](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/05/Cats-Dogs-Classification-deep-learning.gif)

## Dependencies:
1. TensorFlow
2. Python 3.6
3. Numpy

## Dataset:
Data is downloaded from Kaggle.

https://www.kaggle.com/c/dogs-vs-cats/data

## Approach:
Here I am using transfer learning procedure to get good accuracy for my model

1.) Take weights of the inception model up to ‘mixed7’ layer and make them untrainable.

2.) Next flatten the weights.

3.) Define a DNN with 1024 nodes

4.) Used 20% Dropouts.

5.) Dense layers with 1 node and with sigmoid activation function.

## Conclusion:
Cats vs Dogs classifier with 95% accuracy on Training data.
