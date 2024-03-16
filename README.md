# Cats and Dogs classification

***This repository contains implementation of a support vector machine (SVM) to classify images of cats and dogs .***

# Dataset
Kaggle dataset : https://www.kaggle.com/c/dogs-vs-cats/data

 # Getting Started 
 ### Prerequisites
 -   Python 3.x
 - Matplotlib:  `!pip install matplotlib`
 - tqdm:`!pip install tqdm`
-  NumPy:  `!pip install numpy`
- tensorflow:  `!pip install tensorflow`
-  sklearn:  `!pip install sklearn`

# SVM implementation
  
Support vector machine was implemented  using SVC to classify images into cats or dogs
This was done by extracting features from images using a pre-trained VGG16 model to extract features and then feeding them to SVC to train the model.

# Accuracy & Prediction
The model was given an accuracy of **97%**  with testing the model by giving it external images to predict the classification of these images.
