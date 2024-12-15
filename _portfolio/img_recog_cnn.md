---
title: "Applying Convolutional Neural Networks for Pattern Recognition"
excerpt: "Building and evaluating a convolutional neural network for image classification on the CIFAR-10 dataset. Also applicable in decoding neural signals like EMG<br/><img src='/images/portfolio/cifar_10_recog_cnn/aug_cifar10_data_01.png'>"
collection: portfolio
# category: general
---

#### Objective: 
To train and evaluate a convolutional neural network to classify images from the CIFAR-10 dataset into 10 distinct classes (e.g., airplane, automobile, bird).

#### Key Components:
- Utilizes PyTorch's DataLoader for efficient batching, shuffling, and preprocessing of images.
- Custom CNN architecture optimized for image classification.
- Uses a CrossEntropyLoss and Adam optimizer for training.
- Results shows some impressive performance in generalizing on sophisticated augmented images with about **85% Accuracy** in recognition.

<img src='/images/portfolio/cifar_10_recog_cnn/accuracy_trend_01.png'>" 


#### Lessons 
Transfer experience and skills to analyze complex patterns in neural data, such as decoding brain signals (e.g., EEG, fMRI, or spike trains) for advancing machine learning applications in neuroimaging and neural decoding tasks

Explore the full source code and implementation details on GitHub:  
[View Code on GitHub](https://github.com/CaptainJamesMaximus/machine_learning_ai/tree/main/image_recognition_with_convolutional_nn)