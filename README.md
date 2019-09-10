# imageRecogCNN_clothing
Clothing and fashion Image Recognition using Deep Convolutional Neural Networks (CNN)




#### Oivetti database of face images from AT&T research lab. It includes 400 faces (64x64 pixels) from 40 people (10 images per person) Use Face Recognition algorithm to recognize each person using PCA dimensionality reduction and non-linear SVM

- Building the feature matrix and label vector: Each image is considered as a data sample with pixels as features. Thus, to build the feature table you have to convert each 64x64 image into a row of the feature matrix with 4096 columns and <u>Normalize</u> each column of your feature matrix

<!-- ![Screenshot](blob/Capture.png) -->

![Screenshot](https://github.com/cowboyuniverse/FaceRecognitionSVM/blob/master/blob/Capture.PNG)

-  Using PCA to reduce the dimensionality from
4096 to 50. "Fit" my PCA on my training set only, and then use this fitted model to “transform” both training and testing sets. Designing and training a non-linear SVM classifier to recognize the face based on the training datasetthat's now normalized and randomize the SVC state.  

<!-- ![Screenshot](blob/Capture3.png) -->

![Screenshot](https://github.com/cowboyuniverse/FaceRecognitionSVM/blob/master/blob/Capture3.PNG)



-Using GridSearchCV to find the best value for parameter C in your SVM.

<!-- ![Screenshot](blob/Capture4.png) -->

![Screenshot](https://github.com/cowboyuniverse/FaceRecognitionSVM/blob/master/blob/Capture4.PNG)



author: yosep kim

github.com/cowboyuniverse

