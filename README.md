# apple classification via tensorflow
This repository contains Apple Classifiacation through CNN. This model which type of apple does given image of apple is

## Dataset
Datatest used in this model is divided in training and validation set. There are 4 classes of apples used. Each class contains approximately 500 images foer training and 150 validation images

## tf_record
This notebook converts the training data image to a tfrecord

## tf_cnn-relu
This notebook contains classification using CNN. Here opencv is used for importing & preprocessing and tensorflow is used for making model using relu relu and softmax activation function.

## tf_cnn-own_Activation
his notebook contains classification using CNN and own activation.
f(x)=x/(1+exp(-x))

I got to know about this function by doing some research. This function does no
