# Dog-s-Breed-Classifier

# About the Project
This is one of the milestone projects in the Deep Learning Nanodegree from Udacity. The goal of the notebook is to create an algorithm that classifies an image as a dog or human. After classifying the image, the algorithm uses one of the neural networks to classify a dog breed to the image, regardless if it'S classified as a dog or human. Most of the code was provided by Udacity, but the convolutional layer classification was integrated by me. The Jupyter notebook dog_app.ipynb contains the following topics: creating convolutional layer from scratch and using a pretrained vgg16 for transfer learning to improve the classification of dog breeds. 

# Project Overview

As mentioned previously, the project is about classifying an image as being a dog or human. The output of this algorithm will be as following:

In the dog_app.ipynb notebook there are several ways to classify either a human or a dog.  The following methods are used; OpenCV, pretrained vgg16 model, CNN from scratch and transfer learning of a partially pretrained vgg16 model. Ultimately all methods except the CNN from scratch are used to create an algorithm which predicts whether a fed image is a human or a dog. Regardless of the classification the algorithm uses the transfer-learning-CNN to predict what dog breed the fed image resembles. 

# Project Instructions

## Instructions

This notebook runs on PyTorch, it is expected that you already have this installed in your environment.

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/lopezyouhei/Dog-Breed-Classifier.git
		cd Dog-Breed-Classifier
	```

2. If you will be working with the neural networks, you'll need to download the following dataset [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
3. If you will be working with the neural networks, you'll need to download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
4. Make sure you have already installed the necessary Python packages according to the README in the program repository.
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```

