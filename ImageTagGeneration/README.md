# Image Tag Genreation on Yelp Dataset

This module of project focuses on automatically generating cuisine type tags for the pictures uploaded by the user. 

### Algorithms Used
```
XGBoost
Tensorflow based 3-layer CNN
```
### Data Preprocessing
| XGBoost       | 3-layer CNN   |
|:-------------:|:-------------:|
| Used Histogram of oriented gradients (HOG)| Data Augmentation |
|Feature agglomeration      | Resize Image to 256*256
|Sampling the train and test data|


###### Histogram of Oriented Gradients (HOG)
The histogram of oriented gradients (HOG) is a feature descriptor used in computer vision and image processing for the purpose of object detection. In HOG technique,the image is divided into small connected regions called cells, and for the pixels within each cell, a histogram of gradient directions is compiled. The descriptor is the concatenation of these histograms. For more information about HOG, headover to [wikipedia](https://en.wikipedia.org/wiki/Histogram_of_oriented_gradients) <br>

###### Data Augmentation
Image data augmentation is a technique that can be used to artificially expand the size of a training dataset by creating modified versions of images in the dataset. Training deep learning neural network models on more data can result in more skillful models, and the augmentation techniques can create variations of the images that can improve the ability of the fit models to generalize what they have learned to new images. For more [click here](https://machinelearningmastery.com/how-to-configure-image-data-augmentation-when-training-deep-learning-neural-networks/)
