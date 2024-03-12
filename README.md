# Melanoma Detection Assignment
> The goal is to develop a Convolutional Neural Network (CNN) model that can accurately identify melanoma, a deadly type of cancer that accounts for 75% of skin cancer deaths. The model aims to evaluate images and alert dermatologists about the presence of melanoma, potentially reducing the manual effort required in diagnosis. The dataset for this project, available for download, is sourced from the International Skin Imaging Collaboration (ISIC). It comprises 2357 images of malignant and benign oncological diseases. The images are sorted according to the ISIC classification, with an equal number of images for each category, except for melanomas and moles. The dataset includes images of various diseases such as Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#Contact)

## General Information
The project aims to build a Convolutional Neural Network (CNN) model to accurately detect melanoma, a deadly skin cancer, using a dataset of 2357 images of various oncological diseases from the International Skin Imaging Collaboration (ISIC). The model could potentially reduce manual effort in diagnosis by alerting dermatologists about the presence of melanoma.

The broad objectives of this assignment are:

1. Data Reading/Data Understanding.
2. Dataset visualization
3. Model Building & training
4. Model Building & training on the augmented data.
5. Model Building & training on the rectified class imbalance data

## Conclusions
Based on models and augmentation technique we used following are the observations

- When samples are less overfitting is a real possibility
- Augmentation does help in reducing the overfitting.
- Sampling techniques used by Augmenter does help in reduction in overfitting
- For class balanced and augmented data learning stops after 30 epochs where post this we can see gradual increase in overfitting

Based on Lasso following are the 10 key columns that influence the price of property

## Technologies Used
- pandas
- matplotlib
- seaborn
- sklearn
- tensorflow
- keras

## Contact
Created by [@akaushikdel99] - feel free to contact me!