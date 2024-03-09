# Melanoma Detection using CNN
> Bbuild a CNN based model which can accurately detect melanoma.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. 
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Conclusions
- After rebalance/resampling of the data (that gave equal proportion of data )and raised the accuray of the mdoel to 90%. This addressed the low accurty problem.
- Overfitting probelm is adressed and now difference between train and val set is nearly 4-5% diff.with these results it's conclusive that current module with rebalanced data is the best module.
- The custom model shows high accuracy in training datasets but still there is scope of improvement in test datasets. 


## Technologies Used
- GoogleColab
- Tensorflow, Keras
