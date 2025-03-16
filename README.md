# Melanoma_Detection_Assignment
> Project aims to build a CNN based model which can accurately detect melanoma, which is a dangerous form of skin cancer, from the images provided to the model based on International Skin Imaging Collaboration (ISIC) dataset. The model will help dermatologists in early detection, reducing manual efforts and thus proceed with early treatment of the disease.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- Project aims to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


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

- Several convolution models were built from scratch and augmentation strategies implemented, before arriving at the final model, which helps to detect melanoma from different types of images provided to it.



## Conclusions
- The class "seborrheic keratosis" comprises the smallest proportion of samples. "Pigmented benign keratosis" and "melanoma" significantly outweigh other classes.
- Following 30 epochs, the final model attains a train accuracy of 73% and validation accuracy of 68%. 
- The data augmentation layers with random flipping, rotation, zooming, and addition of dropout layers reduced overfit slightly.
- The implementation of class rebalancing has notably enhanced the model's performance across both training and validation datasets. The ultimate model displayed well-balanced performance, displaying no signs of underfitting or overfitting.


## Technologies Used
- pandas - version 2.2.2
- numpy - version 1.26.4
- matplotlib - version 3.7.1
- seaborn - version 0.13.2
- scikit-learn - version 1.5.2
- scipy - version 1.13.1
- statsmodel - 0.14.4
- scikit-learn - 1.6.1
- tensorflow - 2.18.0
- keras - 3.8.0
- Augmentor - 0.2.12



## Acknowledgements
- This project was based on International Skin Imaging Collaboration (ISIC) dataset.


## Contact
Created by anusha761 - feel free to contact me!
