# Udacity Dog Breed Classifier

##About
In this project we will be implementing 2 image classification models to classify 133 different dog breeds. The first model we will build from scratch by using a series of Convolution layers and Linear layers. For the 2nd model we will use a pretained VGG16 model as a feature and detector and transfer it's learning to our task of image classification. If a dog image is passed to the network it will predict it's breed but if a human image is passed to the network it will predict a resembling dog breed.

##How to use
1) Download/Clone the GitHub repository
2) Download the dataset by following the steps provided here:
a) Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
b) Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 
3) Open the 'dog_app.ipynb' file.
4) Follow the instructions provided in the notebook and run all the cells in the notebook.

NOTE : Use of a GPU is highly recommended during training process

##Results
1) Model built from scratch (model_scratch.pt) attains an accuracy of 10%.
2) Model built using transfer learning (model_transfer.pt) attains an accuracy of 85%.