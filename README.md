# Melanoma cancer detection
> Multiclass classification model using a custom convolutional neural network in TensorFlow to detect melanoma 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Create a CNN model, which can accurately detect 9 classes present in the dataset. 

- What is the background of your project?

The datasets are from 9 classes and the objective is to build a Multiclass classification model using a custom convolutional neural network in TensorFlow to detect melanoma

- What is the business probem that your project is trying to solve?

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the dataset that is being used?

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

![alt text](https://github.com/shrutich91/Melanoma-detection/blob/master/images/Capture1.PNG)

Visualizing an image from every class:

![alt text](https://github.com/shrutich91/Melanoma-detection/blob/master/images/Capture3.PNG)

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
 

Augmentation Analysis
![alt text](https://github.com/shrutich91/Melanoma-detection/blob/master/images/Capture2.PNG)


## Conclusions
- The base model is observed to underfit as the validation accuracy is very low
- Augmentation and Dropout layers are introduced to get rid of the underfitting
- The dataset are not evenly divided into different classes. Some classes are dominant and some are sparse. There is a class imbalance that we need to resolve
- The dataset doesnot have enough data. So Augmentor strategy to augment the number of images is required. The final model has good training, test accuracy



## Technologies Used
- tensorflow - version 2.9.2
- keras - version 2.9.0


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad
- References:https://www.tensorflow.org/



## Contact
Created by [@shrutich91] - feel free to contact me!


