<img src="Images\1.png" alt="drawing" style="width:500px;"/>

# Building an Image Classification Model for Analyzing Chest X-Rays

#### Author: Ryan S. Chung

## Overview
This project focuses on creating and tuning a Convelutional Neural Network model to predict whether a chest X-Ray is abnormal or not.  In this project the data set used included images of healthy chest X-rays and ones which indicated signs of Pneumonia.

## Business Problem
An agency is looking to find a method to accurately predict whether a provided chest X-ray has indicators of Pneumonia or not.  The said agency is looking to be able to relay such information to the providers in which the images were supplied in order to assist the provider in determining whether individuals have Pneumonia or not.

## Data
For this project, a dataset from kaggle called Chest X-Ray Images (Pneumonia) was used.  It should also be menioned that the initial source of images for the kaggle dataset were obtained from Mendeley Data which houses thousands of validated OCT and Chest X-Ray images.  The data from the kaggle set was well organized which made its use for the completion of this project swift.  As stated earlier, the images from the kaggle dataset consisted of healthy chest X-rays and chest X-rays with indications of Pneumonia.

## Methods
This project involved creating two statisical models in order to achieve its goal in presenting the provider with a means to predict whether a chest X-ray has Pneumonia or not.  The initial model created was a Multi-Layer Perception Model which was then followed by the creation of a Convelutional Neural Network model.  The CNN was then run through a grid search to find the best parameters for the model using talos.

## Results
The final CNN model created was able to predict whether a chest X-ray had Pneumonia or not on the training set of images with an accuracy of 100%.  On the testing set of images, the model had an accuracy of about 75%.

## Repository Structure
- Visualizations + Images
- chest_xray
- grid
- .gitignore
- Notebook PDF
- Notebook IPYNB
- P4 Presentation
- Presentation PDF
- README.