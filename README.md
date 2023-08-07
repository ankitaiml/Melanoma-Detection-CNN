# Project Name: Melanoma Skin Cancer Detection using CNN



## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements



## General Information
- We have a dataset with 2357 images of different cancer types. 
- These images are distributed among 9 classess, each class represents a type of skin cancer.
- We have to build a model to predict the type of skin cancer by observing the input image. 


## Technologies Used
- tensorflow - version 2.12.0
- kersa - version 2.12.0
- Optimizer - Adam
- Loss - categorical_crossentropy
- Metrix - Accuracy
- We also have used Dropouts, Batch Normanization, and Data Augmentations to handle class imbalance and overfitting

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
- The primary and basic model was overfitting due to complexity and class imbalance.
- The sceond model, with augmentation resolved the problem of overfitting but couldn't improve the model performance.
- The third model, equipped with class imbalance traetment, and batch normalization resolved the problem of overfitting and improved the performance to 91% train and 83% validation which is good.



## Acknowledgements
Give credit here.
- We took help of documentations from tensorflow documentation available on https://www.tensorflow.org/.
- We also took help of stackoverflow to deal with errors that occured during our model creation.



## Contact
Created by Poorvi Patil, Ankit Chaturvedi, and Dishu Jamnal.

