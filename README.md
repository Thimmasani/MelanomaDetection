# Skin Disease Classification Using CNN  
> A deep learning project focused on classifying skin diseases into 9 categories using image data.

## Table of Contents  
* [General Info](#general-information)  
* [Technologies Used](#technologies-used)  
* [Conclusions](#conclusions)  

## General Information  
- This project uses a Convolutional Neural Network (CNN) to classify images of skin diseases into 9 categories, including melanoma, basal cell carcinoma, and seborrheic keratosis.  
- **Background:** Accurate diagnosis of skin diseases is critical for effective treatment. This project aims to assist in automating the diagnostic process using deep learning.  
- **Business Problem:** Manual diagnosis of skin diseases can be subjective and time-intensive. A reliable image classification model could support dermatologists by providing consistent, accurate predictions.  
- **Dataset:** The dataset comprises 2239 images, split into 1792 for training (80%) and 447 for validation (20%), covering 9 disease classes.  

## Conclusions  
- CNN models are effective for image classification but require significant fine-tuning for improved validation accuracy.  
- Training accuracy improved significantly from 23.16% to 76.09% over 20 epochs, but validation accuracy remained relatively low, peaking at 55.48%.  
- The model may face overfitting or be limited by the dataset size or quality, as indicated by the disparity between training and validation performance.  
- Future improvements could include data augmentation, hyperparameter tuning, or experimenting with pre-trained models.  

## Technologies Used  
- Python 3.8  
- TensorFlow 2.10  
- Keras (integrated with TensorFlow)  
- NumPy 1.22  
- Matplotlib 3.5 for visualization  

