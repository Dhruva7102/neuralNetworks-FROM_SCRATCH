
## Objective

To build a basic neural network architecture from from the ground up, without the assistance of popular packages like Tensorflow or Pytorch, to perform digit classification on the MNIST dataset.



## Motivation
It's easy to loose sight of the fact that modern ML stands on the shoulders of giants. Though the robust tools and packages avalable at a developers disposal make learning ML methods easier, it has proved a worthwhile endeavor to forgo them and deepen my understanding of how neural network archetectures function under the hood. Getting intimately familiar with the theory and math behind the code helped me appreciate their architecture and made me a better practitioner.

## Implementation Details
The network will be a standard multi-layer perceptron network with 3 layers, the details of which are as follows

Input Layer - 784 neurons
  -   28 x 28 pixel data; 784 total pixel values

Hidden Layer - 10 neurons
  -   ReLu activation
 
Output Layer - 10 neurons
  -   SoftMax activation
