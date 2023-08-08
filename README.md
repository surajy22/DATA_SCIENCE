# Project Name
> Outline a brief description of your project.
In this assignment, we will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Business Understanding
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion
- Business Goal:
You are required to build a multiclass classification model using a custom convolutional neural network in TensorFlow.

Business Risk:
Predicting a incorrect class of skin cancer

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Overfitting was observed with the inital model build
- data_augmentation and dropout used to cater the overfitting issue,
- data imbalance observed due to big difference in number of samples per category
- Augmentor used to overcome imbalance issue and model accuracy seems to be better

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- numpy
- matplotlib
- seaborn
- plotly
- sklearn
- statsmodel
- tensorflow

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- https://seaborn.pydata.org/
- https://plotly.com/
- https://pandas.pydata.org/
- https://learn.upgrad.com/
- https://www.tensorflow.org/)


## Contact
Created by [@surajy22] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
