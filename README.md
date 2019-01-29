# Digit-Recognition-by-LeNet5-in-tensorflow
Implementation of the LeNet-5 deep neural network model in Tensorflow for handwritten digit recognition

Specs

Input Image is 28x28x1 and converted to 32x32x1 as per LeNet requirements.

Convolution layer 1: Using filter(f=5,s=1), the output shape should be 28x28x6.

Activation 1: ReLu activation function.

Pooling layer 1: Using Maxpool(f=2,s=2), the output shape should be 14x14x6.

Convolution layer 2: Using filter(f=5,s=1), the output shape should be 10x10x16.

Activation 2: ReLu activation function.

Pooling layer 2: Using Maxpool(f=2,s=2), the output shape should be 5x5x16.

Flatten layer: Flatten the output shape of the final pooling layer such that it's 1D instead of 3D.

Fully connected layer 1: This should have 120 outputs.

Activation 3: ReLu activation function.

Fully connected layer 2: This should have 84 outputs.

Activation 4: ReLu activation function.

Fully connected layer 3: This should have 10 outputs.

Activation 5: SoftMax activation function.
