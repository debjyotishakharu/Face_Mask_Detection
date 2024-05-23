# Face_Mask_Detection

## Model Architecture
A working Deep Learning model to classify images of person with or without mask.

Ths model can be deployed for detecting whether a person is wearing a mask or not in order to warn if it is a "Face Mask Zone" area.

The model is trained using a CNN (Convolutional Neural Network) which consists of input layers fed into a convulational block followed by a dense layers, finally giving the output.


## Dataset Information
Data set consists of 7553 RGB images in 2 folders as with_mask and without_mask. Images are named as label with_mask and without_mask. Images of faces with mask are 3725 and images of faces without mask are 3828. The dataset link is present [here](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset).

## Technologies Used
This project was implemented using the following technologies:

TensorFlow and Keras: for building and training the deep learning model.

PIL, OpenCV: for image processing.

os: for handling the image files.

Matplotlib: for visualizing the training and validation results
