# Melanoma Detection leveraging Convolutional Neural Networks
> Building and training multiclass classification model using a custom convolutional neural network in TensorFlow. This model can be used to detect melanoma without the need of human intervention and manual analysis of the images.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution has to be build which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).

## Conclusions
#### Conclutions from Model 1 - (No data augmentation)
Looking at the model-1 accuracy and loss graphs of training and validation data we can see that
- **Model is clearly overfitting as training accuracy is significatly more than validation accuracy**.
- Validation accuracy is plateauing after about 5 epochs.

#### Conclutions from Model 2 - (data augmentation using Keras library)
Looking at the model-2 accuracy and loss graphs of training and validation data we can see that
- **Model is clearly underfitting as both training and validation accuracy is around 50% even after training the model for 20 epochs**.

#### Conclutions from Model 2 - (data augmentation using Augmentor library)
Looking at the model-1 accuracy and loss graphs of training and validation data we can see that
- **Model is clearly overfitting as training accuracy is significatly more than validation accuracy**.
- Validation accuracy is plateauing after about 10 epochs.

## Technologies Used
- Python - version 3.12.3
- Tensor Flow - version 2.18.0
- Keras - version 3.18.0
- Augmentor - version 0.2.12


## Contact
Created by [@singh-anshuman] - feel free to contact me!