# celeba_vgg
Project: VGG16 Model Implementation

Overview

This Jupyter Notebook (VGG16_fix (1).ipynb) contains the implementation of the VGG16 convolutional neural network model. The VGG16 model is a deep learning architecture widely used for image classification tasks, originally developed by the Visual Geometry Group (VGG) at the University of Oxford.

Features

Loads the pre-trained VGG16 model (or a custom-trained version if applicable).

Performs image preprocessing, including resizing and normalization.

Extracts features from images using convolutional layers.

Fine-tunes the model for custom classification tasks if necessary.

Evaluates model performance using various metrics.

Requirements

Ensure you have the following dependencies installed before running the notebook:

Python 3.x

TensorFlow/Keras

NumPy

OpenCV/PIL for image handling

Matplotlib/Seaborn for visualization

Jupyter Notebook

File Structure

VGG16_fix.ipynb - Jupyter Notebook containing the code and explanations.

celeba-gender-partitions.csv - csv file that guiding a partition rule. each file name alongside with one of number: 0,1,2. 0 for training data, 1 for validating data, 2 for test data.

file_list.txt - name list of each file

list_attributed_edited_v2.csv - list of filename those attributed few character of the image. the true attributed marked with 1 whereas not by 0.
