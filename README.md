# Melanoma Detection
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The first model which has no dropout layer overfits the data.
- After adding image augmentation layer the overfitting problem is removed however the model now underfits the data.
- The final model is created by first augmenting the data set with new images using Augmentor library. This model gives a good fit which neither underfits nor overfits the data.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Acknowledgements
- This project was inspired by UpGrad ML and AI program.
- Reference: Tensorflow man page, Stackoverflow, Google.


## Contact
Created by zuhu2195 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
