![TF](https://github.com/Currency-Clasification-Bangkit-2024/MCC-ML/blob/main/assets/Header.png)

# Multiple Images Detection & Classification
Developing a deep learning model for money image detection & classification using Tensorflow and Y0L0: Creating a Convolutional Neural Network (CNN) model and You Only Look Once (Y0L0 model to detect and categorize scanned moneys with Tensorflow and Y0L0v8.

## Project Overview
The objective of this project is to develop two models capable of accurately detecting and categorizing images of Indonesian currency into predefined classes. These models could be integrated into applications and hardware, allowing for the automatic identification and classification of currency types based on images uploaded by users.

## Dataset
The dataset used in this project consists of images depicting various types of Indonesian currency, systematically organized into distinct categories. Each image is annotated with the specific denomination of the currency and its corresponding condition classification.
- https://drive.google.com/drive/folders/1DtAmzfoMY9rLRaWlSbCj_MKujhEI_cSw?usp=sharing

## Feature
- Data Augmentation 
- CNN (Convolutional Neural Networks)
- Y0L0v8

## Requirements 
- Tensorflow 
- Matplothlib
- Numpy
- Pillow
- Scikit-learn
- Ultralytics==8.0.196
- roboflow

## Documentation
- Conduct research related to machine learning models
- Collect fresh and rotten fruits and vegetables datasets 
- Split the dataset into 70% for the training set and 30% for the validation set
- Create a machine learning model with CNN (Convolutional Neural Network) using MobileNetV2 architecture
- Train the model 
- Evaluate the machine learning model
- Testing the model by uploading new test data that the model has never seen before
- Deploy the model using Fast Api

## Results
The model achieved a test accuracy of 97% on the test dataset. The training and validation loss/accuracy plots can be found here.
![acc](https://github.com/Mubazir-Bangkit-2023/mubazir-machine-learning/assets/95016158/6f2c7efe-5c95-42ad-9b88-568b92606d11)

![loss](https://github.com/Mubazir-Bangkit-2023/mubazir-machine-learning/assets/95016158/64495ff1-56f3-4b27-a2d6-4597ce07d845)


## Future Work
- Expand the data set to include a wider variety of fruits and vegetables
- Explore advanced architectures and methodologies in experiments to enhance accuracy further.
