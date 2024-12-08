![TF](https://github.com/Currency-Clasification-Bangkit-2024/MCC-ML/blob/main/assets/Header.png)

# Multiple Images Detection & Classification
Developing a deep learning model for money image detection & classification using Tensorflow and Y0L0: Creating a Convolutional Neural Network (CNN) model and You Only Look Once (Y0L0) model to detect and categorize scanned moneys with Tensorflow and Y0L0v8.

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
- Collect indonesian currency datasets 
- Split the dataset into 80% for the training set, 10% for the validation set, and 10% for the test test (Y0L0) model
- Create a machine learning model with CNN (Convolutional Neural Network) and Y0l0 model with roboflow
- Train, val, and test bost model separately
- Deploy the model

## Results
The model achieved 99.5% of mAP, 83.8% of precision, and 100% of recall. The performance can be found here.
![acc](https://github.com/Currency-Clasification-Bangkit-2024/MCC-ML/blob/main/assets/results%20-%20yolo.png)

## Future Work
- Add and annotate additional images of Indonesian currency.
- Expand the currency dataset to include international and foreign currencies for future applications.
- Explore advanced architectures and methodologies in experiments to further improve accuracy.
