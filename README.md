# Diabetes Retinopathy Prediction
This repo contains the source code for prediciting diabetes retinopathy using Machine Learning and Deep Learning together. 

Diabetes Retinopathy detection has always been the major project in fighting the war against the disease. This is why researchers are turning their attention to artificial yet accurate ways of detecting the disease. A viable solution would be through a look at the colour fundus photographs (CFPs). 

This code attempts to find the combination of pre-trained models and machine learning algorithms that would correctly classify the diabetes retinopathy stage of patients – No Diabetes Retinopathy, Mild, Moderate, Proliferate, and Severe. The data for this work can be download on Kaggle. Find it here. https://www.kaggle.com/sovitrath/diabetic-retinopathy-224x224-2019-data

Pre-trained models used were models with a proven track for the popular Image classification of the ImageNet dataset. They are VGG16, ResNet, Inception, MobileNet, and DenseNet. In this work, however, they were not used as classifiers but rather as initial feature extractors. In other words, they were used to find underlying patterns in the images of each class but were not used to make the actual classification. 

The feature extraction from the pre-trained models was then passed to machine learning algorithms for classification. Four machine learning algorithms were combined with the pre-trained models for classification. They include random forest, support vector machines, k-nearest neighbours, and Gaussian Naïve Bayes. 

The models were evaluated on various parameters such as accuracy, precision, etc to find the best performing result. 
