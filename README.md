![TF](https://github.com/Currency-Clasification-Bangkit-2024/MCC-ML/blob/main/assets/Header.png)

# Multiple Images Detection & Classification
Developing a deep learning model for money image detection & classification using Tensorflow and Y0L0: Creating a Convolutional Neural Network (CNN) model and You Only Look Once (Y0L0) model to detect and categorize scanned moneys with Tensorflow and Y0L0v8.

## Project Overview
The objective of this project is to develop two models capable of accurately detecting and categorizing images of Indonesian currency into predefined classes. These models could be integrated into applications and hardware, allowing for the automatic identification and classification of currency types based on images uploaded by users.

## Dataset
The dataset used in this project consists of images depicting various types of Indonesian currency, systematically organized into distinct categories. Each image is annotated with the specific denomination of the currency and its corresponding condition classification.
Yolo: https://drive.google.com/drive/folders/1DtAmzfoMY9rLRaWlSbCj_MKujhEI_cSw?usp=sharing
CNN: https://drive.google.com/drive/folders/1LHaadqULyGbN-oDTdnVLmaxOXN4ah1Cf?usp=sharing

## Feature
- Data Augmentation 
- CNN (Convolutional Neural Networks)
- Y0L0v8

## Requirements For Yolo
- Tensorflow
- Matplothlib
- Numpy
- Pillow
- Scikit-learn
- Ultralytics==8.0.196
- roboflow

## Requirements For CNN
- pandas==2.2.2
- numpy==1.26.4
- matplotlib==3.8.0
- seaborn==0.13.2
- scikit-learn==1.5.2
- tensorflow==2.17.1
- imutils==0.5.4
- pillow==11.0.0

## Documentation Yolo
- Conduct research related to machine learning models
- Collect Indonesian currency datasets
- Split the dataset into 80% for the training set, 10% for the validation set, and 10% for the test test (Y0L0) model
- Y0l0 model with roboflow
- Train, val, and test bost model separately
- Deploy the model

## Documentation CNN
- Conduct research related to CNN machine learning models
- Collect Indonesian currency datasets
- Pre prosessing image with roboflow
- Split the dataset into 80% for the training set and 20% for the validation set
- Create a machine learning model with CNN (Convolutional Neural Network)
- Train the model
- Evaluate the machine learning model
- Testing the model by uploading new test data that the model has never seen before
- Export model to keras and h5 extention

## Results Yolo
The model achieved 99.5% of mAP, 83.8% of precision, and 100% of recall. The performance can be found here.
![acc](https://github.com/Currency-Clasification-Bangkit-2024/MCC-ML/blob/main/assets/results%20-%20yolo.png)

## Results CNN
The model demonstrated outstanding performance, achieving an overall accuracy of 99%. It recorded a macro average precision of 99%, recall of 99%, and an F1-score of 99%. Specific class-level performance metrics showed consistently high precision, recall, and F1-scores across all categories, with some minor variations:

- The highest precision (100%) was achieved for the 1ribu, 20ribu, 50ribu, and 5ribu classes.
- The 2ribu class exhibited a slightly lower precision of 96%, but it achieved a perfect recall of 100%.
- Recall values were near-perfect or perfect across all classes, with most classes scoring 99% or 100%.
![acc](https://github.com/Currency-Clasification-Bangkit-2024/MCC-ML/blob/main/assets/accuracy%20and%20loss%20-%20CNN.jpg)
![acc](https://github.com/Currency-Clasification-Bangkit-2024/MCC-ML/blob/main/assets/result%20-%20CNN.png)


## Future Work
- Add and annotate additional images of Indonesian currency.
- Expand the currency dataset to include international and foreign currencies for future applications.
- Explore advanced architectures and methodologies in experiments to further improve accuracy.
