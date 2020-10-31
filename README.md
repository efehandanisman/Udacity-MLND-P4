# Udacity-MLND-P4:Dog Breed classification Project

This is the fourth project of the Udacity Machine Learning Engineer Nanodegree.

Aim of the project is classifying dog breeds when a dog is fed into application. In case a human fed into application, it returns the most resembling dog to that human. 
In case the image neither dog nor human, it returns an error. PyTorch, numpy, glob, matplotlib and OpenCV are the main libraries used while developing the project.

Data is avaliable at the links below for human and dog datasets.

* https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip
* https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip 

The project submission includes documents outlined below:

* ProjectReport.pdf
* proposal.pdf
* README.md
* Six jpg images to test the model
* dog_app.ipynb

Project Outline: 

1. Human face detector with Haar_cascade classifier.
2. Dog detector with VGG16
3. CNN model for dog breed classification
4. Transfer Learning with pretrained ResNet50 
5. Final Algorithm to complete the app.
