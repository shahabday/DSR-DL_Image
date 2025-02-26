# MC-questions

Instructions: any amount of answers might be correct.

We recommend to try not to use internet search but to answer the materials
with your knowledge.

## Topics

### Regularization for image classification

Which of the techniques can help regularize?
+ Batchnorm
+ Dropout
+ L2 norm
- RMSprop

### Playing with parameters. Momentum

Which of the following SGD variants is based on both momentum and adaptive learning?
- RMSprop
- Adagrad
+ Adam
- Nesterov

### Saving, checkpointing and loading your models

What is the formats of saving models in Tensorflow version 2?
+ ckpt
+ h5
- pyc
+ ONNX

### CNN

https://iq.opengenus.org/cnn-questions/

Which of the following is well suited for perceptual tasks?
- Fully-connected neural networks
- Recurrent neural networks
+ Convolutional neural networks
- Reinforcement Learning

The input image has been converted into a matrix of size 28 X 28 and a kernel/filter of size 7 X 7 with a stride of 1. What will be the size of the convoluted matrix?
- 20x20
- 21x21
+ 22x22
- 25x25

The robotic arm will be able to paint every corner in the automotive parts while minimizing the quantity of paint wasted in the process. Which learning technique is used in this problem?

- Supervised Learning
- Unsupervised Learning
+ Reinforcement Learning
- Supervised and Unsupervised Learning

Which of the following layers is NOT differentiable for backpropagation?

- Batchnorm
- Conv
- Dropout
+ Argmax

How do the following receptive fields compare: A) two consecutive layers of stride-1 3x3 convolutions, B) single layer of a 5x5convolution?

- A's receptive field is bigger
- A's receptive field is smaller
+ A and B have the same receptive field
- You cannot compare these layers

Which of the following statements is true when you use 1×1 convolutions in a CNN?

- It can help in dimensionality reduction
+ It can be used for feature pooling
- It suffers less overfitting due to small kernel size
- All of the above

### MiniVGGNet

Which of the following classifiers are non-linear?

- PCA
+ VGG-16
- SVM without kernel
+ Random Forest

### Learning Rate schedulers

While training a model, you see it start to output a loss value of `NaN`. What should you do?

- Reduce the size of your training data set
+ Reduce the learning rate
- Increase the number of parameters in your model
- Increase the learning rate


### Data Augmentation

You’re training a classifier to distinguish between images of cats and images of dogs. Which data augmentations techniques will be helpful?

- Vertically flipping the images
+ Adding Gaussian noise to the image
+ Shifting the image a few pixels to the right
- Adding images of rabbits

Do the https://deeplizard.com/learn/video/14syUbL16k4 has a 6 questions quiz.

What is true about test-time augmentation?

- You only add data augmenation after a few batches
- You inject noise to the labels instead of the samples
+ You enable augment your samples during inference time
- You should never do test-time augmenation

### Transfer learning

When fine-tuning a ConvNet, which layers should we fine-tune?

+ depends on the amount of data
+ the last convolutional layer
- the earliest convolutional layer
- You should always fine-tune all layers

### Training models (gotchas)

How are the amount of training data and the validation performance of a model related?

- Model performance increases linearly with the amount of data
- Model performance increases exponentially with the amount of data
- Model performance and the amount of training data are not related
+ Model performance scales with the log of the amount of data

### Debugging deep learning models

Which techniques visualize what ConvNets learn?

- Adam
- Eve
+ Grad-CAM
+ visualizing filter maps of hidden layers
