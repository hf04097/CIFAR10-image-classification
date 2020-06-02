# CIFAR10-image-classification
Image classification on CIFAR-10 have been performed.

##Describing CIFAR-10 dataset
The CIFAR-10 dataser contains 60000 32x32x3 colour images in 10 classes. There are 50000 training images and 10000 test images. The datalabels are airplane, automobile, bird,cat, deer, dog, frog, horse, ship, truck. More details about the dataset can be found [here](https://www.cs.toronto.edu/~kriz/cifar.html)

## Implementations
### HOG Feature Extraction and SVM Classfier
HOG features are extracted fromt the dataset and then Support Vector Machine (SVM) classifier is applied on extracted features. An accuracy of 88% was reached.

### Feed Forward Neural Network
A feed forward network is implemented with 3 hidden layers of 1024,256 and 100 neurons repsectively. The input to the network is standardized. An accuracy was 55% reached.

### Convolution Neural Network (CNN)
An accuracy of 88%  was reached with the implemented CNN archiecture.

### Transfer Learning
Pre-trained VGG-16 network (trained on ImageNet) was used as a feature extractor, and then it was connected to a feed forward network consisting of fully connected layers. An accuracy of 74.8% was reached

 
