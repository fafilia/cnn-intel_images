#  Intel Image Classification Using Convolutional Neural Network (CNN)

## Overview
This time, I will do image classification using Convolutional Neural Network (CNN). CNN is very familiar algorithm to classify an image according to the class of the image. CNN consists of neurons that have same weight, bias and activation functions as Multilayer Perceptron (NN in general), but we will get to know a new term called convolution layer. The dataset I used was an Intel Image Classification dataset that I got from [Kaggle](https://www.kaggle.com/puneet6060/intel-image-classification). This dataset is a landscape image data worldwide. The dataset consists of 25000 images measuring 150x150 pixels and it divided into 6 classes, as follows:
- 0 : Buildings
- 1 : Forest
- 2 : Glacier
- 3 : Mountain
- 4 : Sea
- 5 : Street

## Dependencies
Actually to follow this module you only need to install `tensorflow`, `keras`, `scikit-learn` with pip or conda command and you are good to go. But here some libraries that needed to be installed first that I use at this module :
- os
- pandas
- numpy
- matplotlib
- keras
- tensorflow

## Conclusion
Image classification is the task of taking an input image and outputting a class (building, mountain, sea, etc) or a probability of classes that best describes the image. Convolution Neural Network can be an option for image classification. CNN itself is one type of neural network that is commonly used in image data. It can be said that CNN is used to detect and recognize objects in an image.
The problem as well as the inputs and outputs, let’s think about how to approach this. What we want the computer to do is to be able to differentiate between all the images it’s given and figure out the unique features that make a building is a building or that make a mountain is a mountain, etc. This is the process that goes on in our minds subconsciously as well. When we look at a picture of a mountain, we can classify it as such if the picture has identifiable features such as a landscape that has a conical shape. In a similar way, the computer is able perform image classification by looking for low level features such as edges and curves, and then building up to more abstract concepts through a series of convolutional layers. This is a general overview of what a CNN does.
I hope this short project help you to understand and can kickstart you to learn more about images classification and Convolutional Neural Network. You can also see this project on my [Kaggle](https://www.kaggle.com/fafiliam/intel-images-classification-cnn) kernel.
 
Happy learning~
