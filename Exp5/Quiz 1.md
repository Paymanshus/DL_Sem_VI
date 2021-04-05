# The Basics of ConvNet

#### Q. What do you think applying this filter to a grayscale image will do? ⎡⎣⎢⎢⎢01101331−1−3−3−10−1−10⎤⎦⎥⎥⎥
- Detect vertical edges
- Detect horizonal edges <br>
***Ans. Detect Vertical Edges***

#### Q. Suppose your input is a 300 by 300 color (RGB) image, and you are not using a convolutional network. If the first hidden layer has 100 neurons, each one fully connected to the input, how many parameters does this hidden layer have (including the bias parameters)?
- 27,000,010
- 27,000,100 <br>
***Ans. 27,000,100***

#### Q. Suppose your input is a 300 by 300 color (RGB) image, and you use a convolutional layer with 100 filters that are each 5x5. How many parameters does this hidden layer have (including the bias parameters)?
- 2600
- 2800 <br>
***Ans. 2600***

#### Q. You have an input volume that is 63x63x16, and convolve it with 32 filters that are each 7x7, using a stride of 2 and no padding. What is the output volume?
- 29x29x16
- 29x29x32 <br>
***Ans. 29x29x16***

#### Q. You have an input volume that is 15x15x8, and pad it using “pad=2.” What is the dimension of the resulting volume (after padding)?
- 19x19x8
- 29x29x12 <br>
***Ans. 19x19x8***

#### Q. You have an input volume that is 63x63x16, and convolve it with 32 filters that are each 7x7, and stride of 1. You want to use a “same” convolution. What is the padding?
- 4
- 3 <br>
***Ans. 4***

#### Q. You have an input volume that is 32x32x16, and apply max pooling with a stride of 2 and a filter size of 2. What is the output volume?
- 8x8x16
- 16x16x16 <br>
***Ans. 16x16x16***

#### Q. Because pooling layers do not have parameters, they do not affect the backpropagation (derivatives) calculation.
- False
- True <br>
***Ans. False***

#### Q. In lecture we talked about “parameter sharing” as a benefit of using convolutional networks. Which of the following statements about parameter sharing in ConvNets are true?
- It reduces the total number of parameters, thus reducing overfitting.
- It prevents a feature detector to be used in multiple locations throughout the whole input image/input volume. <br>
***Ans. It reduces the total number of parameters, thus reducing overfitting.***

#### Q. We talked about “sparsity of connections” as a benefit of using convolutional layers. What does this mean?
- Each activation in the next layer depends on only a small number of activations from the previous layer.
- Each activation in the next layer depends on a large number of activations from the previous layer. <br>
***Ans. It reduces the total number of parameters, thus reducing overfitting.***
