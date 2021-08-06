This repository contains two files. 
The first file contains Age and gender models build independently.
The second file shows the structure of pipeline where we pass an image and it will detect age and gender along with person location.
Highlights:
1. OpenCV was used for various image related processing.
2. For face detection we used MTCNN model.
2. It can work with an image with multiple persons.
3. The model architecture used in age and gender detection is same except the activation function in output layer. We took linear activation function over relu for regression 
purpose i.e., age detection and for gender detection we used sigmoid activation i.e., classificatin purpose.

Steps include:
1. Data collection : open source dataset taken from kaggle https://www.kaggle.com/nipunarora8/age-gender-and-ethnicity-face-data-csv . It is based on famous UTK dataset.
2. Model building.
3. Assembling all the three models together.
4. Write information on given image.
