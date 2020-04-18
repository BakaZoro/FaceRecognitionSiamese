# FaceRecognitionSiamese

A Siamese Network is pair of Convolutional Neural Networks (CNN) that have identical weight and take a pair of images along with their label as an input. They are very handy when we have a small amount of dataset on each member of a class. The Siamese Netwoks creates a pair of feature vector for each input and measures the absolute distance between them. If the distance is lesser than a threshold value then the two images are considered to be of the same class. 
In case of Face Recognition , the classes are the different people. Two images of two/same people along with thier label are fed into the Siamese Network at the same time and the distance between them is measured. The model is first trained on the training data and then the predictions are made on the test data. This kind of learning how to detect is called One Shot Learning or Few Shot Learning, when a few examples of a class are used. Here, Few Shot Learning has been implemented.


Dependencies:

1. AT&T Dataset. Link to dataset: https://www.kaggle.com/kasikrit/att-database-of-faces
2. Python3
3. Tenserflow version 2.2.0-rc3

The AT&T Dataset contains 40 folders. For the given code, all the 40 folders are uploaded onto the drive and the drive is then mounted. The images are read from the folders that are on the Drive.
Download the .ipynb file and directly open in your notebook.


