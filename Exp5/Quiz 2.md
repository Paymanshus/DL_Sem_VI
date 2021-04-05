#  ConvNets

#### Q. Which of the following are common reasons for using open-source implementations of ConvNets (both the model and/or weights)?
- The same techniques for winning computer vision competitions, such as using multiple crops at test time, are widely used in practical deployments (or production system deployments) of ConvNets.
- Parameters trained for one computer vision task are often useful as pretraining for other computer vision tasks. <br>
***Ans. Parameters trained for one computer vision task are often useful as pretraining for other computer vision tasks.***

#### Q. Which of the following are common reasons for using open-source implementations of ConvNets (both the model and/or weights)?
- A model trained for one computer vision task can usually be used to perform data augmentation even for a different computer vision task.
- It is a convenient way to get working an implementation of a complex ConvNet architecture. <br>
***Ans. It is a convenient way to get working an implementation of a complex ConvNet architecture.***

#### Q. Which ones of the following statements on Inception Networks are true?
- A single inception block allows the network to use a combination of 1x1, 3x3, 5x5 convolutions and pooling.
- Making an inception network deeper (by stacking more inception blocks together) should not hurt training set performance.
- Inception networks incorporates a variety of network architectures (similar to dropout, which randomly chooses a network architecture on each step) and thus has a similar regularizing effect as dropout. <br>
***Ans. A single inception block allows the network to use a combination of 1x1, 3x3, 5x5 convolutions and pooling.***

#### Q. Suppose you have an input volume of dimension nH x nW x nC. Which of the following statements you agree with? (Assume that “1x1 convolutional layer” below always uses a stride of 1 and no padding.)
- You can use a 1x1 convolutional layer to reduce nC but not nH, nW.
- You can use a 1x1 convolutional layer to reduce nH, nW, and nC.
- You can use a pooling layer to reduce nH, nW, but not nC. <br>
***Ans. You can use a 1x1 convolutional layer to reduce nC but not nH, nW.***

# Deep Convolution Models
#### Q. Suppose you have an input volume of dimension 64x64x16. How many parameters would a single 1x1 convolutional filter have (including the bias)?
- 2
- 4097
- 1
- 17 <br>
***Ans. 17***

#### Q. Which ones of the following statements on Residual Networks are true?
- Using a skip-connection helps the gradient to backpropagate and thus helps you to train deeper networks
- A ResNet with L layers would have on the order of L2 skip connections in total.
- The skip-connection makes it easy for the network to learn an identity mapping between the input and the output within the ResNet block. <br>
***Ans. Using a skip-connection helps the gradient to backpropagate and thus helps you to train deeper networks***

#### Q. Training a deeper network (for example, adding additional layers to the network) allows the network to fit more complex functions and thus almost always results in lower training error. For this question, assume we’re referring to “plain” networks.
- True
- False <br>
***Ans. False***

#### Q. In order to be able to build very deep networks, we usually only use pooling layers to downsize the height/width of the activation volumes while convolutions are used with “valid” padding. Otherwise, we would downsize the input of the model too quickly.
- True
- False <br>
***Ans. False***

#### Q. Which of the following do you typically see in a ConvNet?
- Multiple CONV layers followed by a POOL layer
- Multiple POOL layers followed by a CONV layer
- FC layers in the first few layers <br>
***Ans. Multiple CONV layers followed by a POOL layer***

#### Q. Which of the following do you typically see as you move to deeper layers in a ConvNet?
- nH and nW increases, while nC decreases
- nH and nW decreases, while nC also decreases
- nH and nW increases, while nC also increases
- nH and nW decrease, while nC increases <br>
***Ans. nH and nW decrease, while nC increases***
