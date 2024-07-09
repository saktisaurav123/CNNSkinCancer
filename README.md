# Skin Cancer Classification using CNN
> In this assignment, We built a multiclass classification model using a custom convolutional neural network in TensorFlow. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- What is the business probem that your project is trying to solve?
A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- What is the dataset that is being used?
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
With Initial model, training and validation accuracy were very low.
- Conclusion 2 from the analysis
Tried with augmentation by rotating and flipping images, accuracy improved but still was very less.
- Conclusion 3 from the analysis
Found out that the class imbalance was there with 2 class dominating. 
- Conclusion 4 from the analysis
Use Augmentor library to help with class balancing.
New model trained on class balanced set performed far better.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Tensorflow
- Numpy
- Keras

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad


## Contact
Created by [@saktisaurav123] - feel free to contact me!