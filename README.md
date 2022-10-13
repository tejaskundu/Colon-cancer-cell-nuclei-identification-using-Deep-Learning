# Colon-cancer-cell-nuclei-identification-using-CNN
A ConvNet that can predict the cell type of the images of colon cancer nuclei. The approach is to build a simple ConvNet, perform unsupervised pre-training by training an autoencoder on the unlabelled test image data and then use the 'encoder' section (with trained weights) as a feature extractor for the first part of your ConvNet.

**CONTENTS**
* data.zip consisting of training and testing data, including an example.csv describing the kind of output expected from the ConvNet.
* Colon_Cancer_Nuclei_Identification.ipynb notebook

### Introduction
A deep neural network which can take a 32x32 image with a cell nuclei and classify it into one of the following types:

1. Normal epithelial cells.
2. Cancer epithelial cells. 
3. Immune leukocyte cells. 
4. Connective fibroblast cells.

### File descriptions

* train.zip - zip file containing the training images in subdirectories with the relevant labels
* test.zip - zip file containing the test images
* example.csv - an example submission file in the correct format

### Data fields
* Id - an anonymous id unique to a given image
* Type - the type of cell at the middle of the image

### System and Environment Requirements
To access this project, your system needs the following software - 
Jupyter Notebook(via Anaconda Navigator 1.10.0) or Google Colab account

### Running the application
To run the application locally, you need to run the access the **Colon_Cancer_Nuclei_Identification.ipynb** notebook file through Jupyter notebook, Select "**Kernel** " **>>** **"Restart and Run all"** from the dropdown menu.

### Note:
This project was a part of a competition in Kaggle(as Hamster in Leaderboard) and had certain restrictions and guidelines whcich were required to be followed. To find out more, please visit: https://www.kaggle.com/competitions/deep-learning-for-msc-coursework-2022/
