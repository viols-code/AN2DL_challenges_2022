# Artificial Neural Networks and Deep Leaning Challenges 2022/2023

### Team members
* [Viola Renne](https://github.com/viols-code)
* [Alessandro Rossi](https://github.com/AlexRouge)
* [Lea Zancani](https://github.com/LeaZancani)

**Tutor:** Prof. Matteo Matteucci
**Group's name:** viola_rossi_blu   
**Final grade:** 10/10

![Python](https://img.shields.io/badge/python-3776AB?logo=python&logoColor=ffdd65&style=for-the-badge&logoWidth=)
![Keras](https://img.shields.io/badge/keras-3776AB?logo=keras&style=for-the-badge&logoWidth=)
![TensorFlow](https://img.shields.io/badge/tensorflow-3776AB?logo=tensorflow&style=for-the-badge&logoWidth=)

## First Homework
**Area:** Convolutional Neural Networks - Image Classification  
**Time:** Two weeks

In this homework we were required to classify species of plants, which were divided into categories according to the species of the plant to which they belong. Being a classification problem, given an image, the goal is to predict the correct class label.

### Dataset Details
Image size: 96x96  
Color space: RGB  
File Format: JPG  
Number of classes: 8  
Classes:
- 0: "Species1"
- 1: "Species2"
- 2: "Species3"
- 3: "Species4"
- 4: "Species5"
- 5: "Species6"
- 6: "Species7"
- 7: "Species8"

Training images per class:
- Species1 : 186
- Species2 : 532
- Species3 : 515
- Species4 : 511
- Species5 : 531
- Species6 : 222
- Species7 : 537
- Species8 : 508


### Evaluation
The metric used to evaluate models and place the Teams in Leadeboard was the Total Accuracy.

### Results
#### First phase - Development
In the first phase, of two weeks, with a total of 530 partecipants, our group achieved the following results:
- EfficientNetb4 - Accuracy: 0.9246  - Position: 21
- EfficientNetb4 - Accuracy: 0.9151 - Position: 35 (tied with other 3 groups)
- Xception - Accuracy: 0.8944 - Position: 79 (tied with other 3 groups)

Our handmade CNN reached an accuracy of 0.83

Counting only the groups, and not the position of each member, our group was the 14th best.

#### Second phase - Final
In the second phase (on a different hidden test set), of two days, with a total of 515 partecipants, our group achieved the following results:
- EfficientNetb4 - Accuracy: 0.9154  - Position: 30
- EfficientNetb4 - Accuracy: 0.9007 - Position: 60
- Xception - Accuracy: 0.8926 - Position: 91

Our handmade CNN reached an accuracy of 0.80

Counting only the groups, and not the position of each member, our group was the 14th best.

Results can be found at [this link](https://codalab.lisn.upsaclay.fr/competitions/8522#results)

## Second Homework
**Area:** Time Series Classification  
**Time:** One week

In this homework, we were asked to correctly classify samples in the multivariate time series format. In other words, since this is a classification problem, the objective is to correctly map the information contained in the features calculated over time to their labels.

### Dataset Details
Time series shape: 2429x36x6  
File format: .npy  
Number of classes: 12  
Classes:  
- 0: "Wish"
- 1: "Another"
- 2: "Comfortably"
- 3: "Money"
- 4: "Breathe"
- 5: "Time"
- 6: "Brain"
- 7: "Echoes"
- 8: "Wearing"
- 9: "Sorrow"
- 10: "Hey"
- 11: "Shine"

### Evaluation
The metric used to evaluate models and place the Teams in Leadeboard was the Total Accuracy.

### Results
#### First phase - Development
In the first phase, of one week, with a total of 527 partecipants, our group achieved the following results:
- ResNet - Accuracy: 0.7485  - Position: 18 (tied with other two groups)
- Bidirectional - Accuracy: 0.7183 - Position: 141 (tied with other six groups)

Counting only the groups, and not the position of each member, our group was the 11th best.

#### Second phase - Final
In the second phase (on a different hidden test set), of two days, with a total of 525 partecipants, our group achieved the following results:
- ResNet - Accuracy: 0.7351  - Position: 82 (tied with other four groups)
- Bidirectional - Accuracy: 0.7183 - Position: 176 (tied with other three groups)

Results can be found at [this link](https://codalab.lisn.upsaclay.fr/competitions/9056#results)

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original-wordmark.svg" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" width="40"/>
