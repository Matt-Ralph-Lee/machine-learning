# Machine Learning Projects

Welcome to the Machine Learning Projects repository! This repository contains three diverse projects, each addressing unique challenges and applications within the realm of machine learning.

# Table of Contents
1. (3D User Interface)[#Project 1: 3D User Interface]
2. (Apple Quality Classification Machine Learning Project)[#Project 2: Apple Quality Classification Machine Learning Project]
3. 

## Project 1: 3D User Interface

### Overview

This project aims to address the limitations of current 3D user interfaces, particularly those relying on remote controls, which often exhibit discrepancies between user movement and on-screen representation. The goal is to create a 3D user interface that offers unrestricted movement for a more intuitive and immersive experience.

### Key Features

- **Simultaneous Hand Movement and Pose Estimation:** The project incorporates advanced machine learning techniques to estimate both hand movement and hand pose simultaneously. This enables precise and dynamic interactions within the 3D environment.

- **Ring-Shaped Camera Implementation:** To eliminate movement restrictions, a unique approach has been adopted by implementing a ring-shaped camera directly on the user's hand. This design choice ensures that the camera moves seamlessly with the user, providing an accurate representation of real-world movement.

- **Image Estimation Challenges:** Due to the ring-shaped camera, capturing an image of the entire hand appearance becomes challenging. However, leveraging machine learning, the project successfully overcomes this limitation by employing techniques to estimate the hand's appearance.

### Video Demonstration

https://github.com/Matt-Ralph-Lee/machine-learning/assets/95742819/c04fac8e-f41f-4f68-8cb1-1b16bfcc0681





## Project 2: Apple Quality Classification Machine Learning Project

### Overview

This project focuses on utilizing machine learning techniques to classify the quality of apples based on various features. The goal is to achieve accurate classification with an emphasis on achieving over 90% accuracy using the CatBoostClassifier.

## Introduction

This project focuses on using machine learning techniques to classify the quality of apples. The classification is based on various features of apples, and the ultimate goal is to achieve a classification accuracy of over 90% using the CatBoostClassifier.

## Dataset

The dataset used for this project contains table data with various features related to apples. Each entry in the dataset represents an apple, and the features include aspects such as size, sweetness, weight, and other relevant characteristics.

## Machine Learning Approach

The machine learning approach adopted in this project involves the use of the scikit-learn library for tasks such as data preprocessing, model training, and evaluation. The primary classification algorithm chosen for this project is the CatBoostClassifier, a gradient boosting algorithm that is well-suited for categorical features.

## Exploratory Data Analysis (EDA)

Before diving into model training, exploratory data analysis (EDA) is performed to gain insights into the dataset. This includes visualizations and statistical summaries to understand the distribution of features, identify correlations, and preprocess data if necessary.

## Training

The training process involves splitting the dataset into training and testing sets. The training set is used to train the machine learning model, and the testing set is used to evaluate its performance. Hyperparameter tuning may be employed to optimize the model.

## CatBoostClassifier

The CatBoostClassifier is a key component of this project. It is a powerful algorithm designed for categorical feature support, handling missing data, and providing high-quality results with default hyperparameters. The goal is to fine-tune the parameters to achieve a classification accuracy exceeding 90%.




## Project 3: Image Classification with Tensorflow

### Overview

This project focuses on image classification using the popular CIFAR-10 dataset. The primary goal is to build a ResNet (Residual Neural Network) from scratch using TensorFlow, showcasing proficiency in deep learning concepts and model implementation.

### Key Features

- **Image Classification:** This project uses CIFAR-10 as dataset.

- **ResNet:** The project uses machine learning technique especially ResNet[https://arxiv.org/pdf/1512.03385.pdf]. It is written from scratch.

- **Tensorflow:** Uses Tensorflow to implement machine learning architecture
