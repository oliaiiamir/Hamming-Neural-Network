# Hamming-Neural-Network
Hamming NN based on Neural Network design by. T. Hagan, B. Demuth, Hudson Beale and De Jesús
# Code description
## Feedforward layer
### Set function:
To set input data and weight for first layer
### FF function:
To calculate output for FeedForward layer by inner join the weight and input, and then add bias to it
### Import prototype matrix:
Import number of prototypes and size of prototypes and finally showing the output of FeedForward layer using FF and Set functions
## Recurrent layer
### Poslin function:
This function find negative values in matrix and turn them to zero
* Zero or positive numbers don't change
### Iteration function:
To calculate next(t) output based on previous(t-1) output of recurrent layer
### BW function:
Take epsilon, set weight for Recurrent layer and calculate output of Recurrent layer using a while loop and Iteration function
## Output
Use NN to calculate output for each Prototype, and then compare them with output of P(input) using Hamming distance
# See the book for more information 
