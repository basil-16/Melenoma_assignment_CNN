# Project Name
>To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- General information 
  - To build a reliable Convolitonal Neural Network to accurately classify the presence of Melonoma given any one of the image of 9 types
  Actinic keratosis
  Basal cell carcinoma
  Dermatofibroma
  Melanoma
  Nevus
  Pigmented benign keratosis
  Seborrheic keratosis
  Squamous cell carcinoma
  Vascular lesion
- What is the background of your project?
  - We have been given images of 9 different disease and we have to build a model which accurately classifies a major common skin cancer type- Melonoma
- What is the dataset that is being used?
  -The Dataset which we were provided it weas divide into train and test and the train folder it was further bifurcated into 9 different skin diseases, the name of the root folder was Skin Cancer ISIC The Internation Skin Imaging Collaboration

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
  - Our Vanilla CNN was grossly overfitting making it really unreliable for skin cancer detection
- Conclusion 2 from the analysis
  - We managed to bridge the gap between the train and valiodation accuracy but the accuracy took a huge hit and the model ewas underfitting
- Conclusion 3 from the analysis
  - Using Augmetor library we managed to solve the issue of class imbalance and the accuracy of train and validation improved, although alight overfitting was noticed
- Conclusion 4 from the analysis
  - We used Augmentor library again and created about 1000 images per class which helped to solved the issue of overfitting, now the model seems to be ready for classify melonoma




## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
