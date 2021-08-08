# Ruchira24-Face-Identification-Model
Face Identification Model to recognise similar faces

DOMAIN: Face recognition

OBJECTIVE :Build a face identification model to recognise human faces to recognise similar faces. The Objective is to be able to recognise whether two given faces
are of the same person or not.

• DATA DESCRIPTION: Face Aligned Face Dataset from Pinterest. This dataset contains 10,770 images for 100 people. All images are taken
from 'Pinterest' and aligned using dlib library. The dataset comprises of images and its mask where there is a human face.

PROJECT TASK: Here I have used a pre-trained model trained on Face recognition to recognise similar faces. Then I have generated Embedding vectors for each face 
in the dataset and then built distance metrics for identifying the distance between two given images.I have used PCA for dimensionality reduction and finally built
an SVM classifier in order to map each image to its right person.
