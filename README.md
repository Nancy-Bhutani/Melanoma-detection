# Melanoma detection
> Building a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).The data set contains 9 different diseases.


## Table of Contents
* [General Information]
* [Technologies Used]
* [Conclusions]



## General Information
-A  multiclass classification model using a custom convolutional neural network in TensorFlow is used to solve Melanoma detection problem.
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.
-We have built a  solution that can evaluate images and alert dermatologists about the presence of melanoma hwhich has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).The data set contains the following 9 diseases: Actinic keratosis, Basal cell carcinoma,Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion.



## Conclusions
- The first CNN model created was an overfittid model. 
- Therefore, data augmentation and dropout techniques were used to overcome overfitting problem.
- Flipping, rotation and zooming techniques were used for the data augmentation.
- There is class imbalance in the dataset, so another model is created to rebalance the class usimg python package 'Augmentor' which gives us a valid model to check for Melanoma presence.




## Technologies Used
- numpy- 1.21.5
- pandas - 1.4.4
- matplotlib - 3.5.1
- keras - 2.12.0
- tensorflow - 2.12.0



## Contact
Created by [@Nancy-bhutani] - feel free to contact me!

