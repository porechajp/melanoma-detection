# Melanoma Detection Assignment

This assignment is to build Convolutional Neural Network to classify the given images in  detecting melanoma.

There 9 classes in the dataset and the model should classify the unseen image into one of these 9 classes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

- The dataset has images classified into following classes,

    - actinic keratosis 
    - basal cell carcinoma
    - dermatofibroma
    - melanoma
    - nevus
    - pigmented benign keratosis
    - seborrheic keratosis
    - squamous cell carcinoma
    - vascular lesion

- The goal of the project is to train CNN Model using the train dataset to classify the given image into one of these classes.

- Due to insufficient train dataset we are supposed to use data augmentation techniques.

- We should build multiple models with different parameters and analyze them with respect to over / underfitting and how they perform on test dataset.


## Conclusions
- The models built using only given train dataset generally underfit and perform badly on test data.
- Dropout helped to improve performance (and prevent overfitting) however the BatchNormalization did not. The model using BatchNormalization kept underfitting.
- Augmentor really helped to improve the training of CNN model.
- Having more no. of filter layers and two Dense layers in FC helps to improve the accuracy marginally.


## Technologies Used
- tensorflow 2.15
- matplotlib 3.8.2
- numpy 1.26.2
- pandas 2.1.4
- scikit-learn 1.3.2


## Acknowledgements
Give credit here.

- Referred https://stats.stackexchange.com/ and https://datascience.stackexchange.com/ for various doubts resolution.

- The upgrad live class helped me to get started.

- Documentation on tensorflow.org


## Contact
Created by [@porechajp] - feel free to contact me!