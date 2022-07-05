# Colon-cancer-cell-nuclei-identification-using-Deep-Learning
A ConvNet that can predict the cell type of the images of colon cancer nuclei. The approach is to build a simple ConvNet, perform unsupervised pre-training by training an autoencoder on the unlabelled test image data and then use the 'encoder' section (with trained weights) as a feature extractor for the first part of your ConvNet.

**CONTENTS**
* data/ folder consisting of training and testing data
* Colon_Cancer_Nuclei_Identification.ipynb notebook

### Introduction
A deep neural network which can take a 32x32 image with a cell nuclei and classify it into one of the following types:

1. Normal epithelial cells.
2. Cancer epithelial cells. 
3. Immune leukocyte cells. 
4. Connective fibroblast cells.


### System and Environment Requirements
To access this project, your system needs the following software - 
Jupyter Notebook(via Anaconda Navigator 1.10.0) or Google Colab account

### Running the application
To run the application locally, you need to run the access the **Colon_Cancer_Nuclei_Identification.ipynb** notebook file through Jupyter notebook, Select "**Kernel** " **>>** **"Restart and Run all"** from the dropdown menu.

### Note:
This project was a part of a competition in Kaggle and had certain restrictions and guidelines whcich were required to be followed. To find out more, please visit: https://www.kaggle.com/competitions/deep-learning-for-msc-coursework-2022/
