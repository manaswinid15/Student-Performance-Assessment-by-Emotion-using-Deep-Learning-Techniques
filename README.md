# Student-Performance-Assessment-by-Emotion-using-Deep-Learning-Techniques
Overview

This project aims to assess student performance by analyzing facial emotions while solving coding problems. The system leverages Deep Learning, Computer Vision, and Machine Learning techniques to identify emotional patterns and predict whether a student successfully completes a coding task.

The solution captures student videos through a webcam, detects facial expressions in real time, classifies emotions using a Convolutional Neural Network (CNN), and uses a K-Nearest Neighbors (KNN) classifier to predict performance outcomes. The model achieved approximately 86% accuracy on the custom dataset.

Problem Statement

Traditional assessment methods evaluate only the final outcome of a task and often overlook student engagement, frustration, confidence, and emotional behavior during problem-solving. This project introduces an AI-driven approach to assess performance by analyzing emotional responses throughout the learning process.

Features
Real-time video capture using webcam
Face detection using OpenCV Haar Cascade Classifier
Emotion recognition using Deep Learning (CNN)
Classification of 7 emotions:
Happy
Sad
Angry
Fear
Surprise
Disgust
Neutral
Emotion frequency analysis
Student performance prediction using KNN
Automated Executed / Not Executed classification
Technology Stack
Python
OpenCV
TensorFlow
Keras
NumPy
Pandas
Scikit-Learn
CNN (Convolutional Neural Network)
KNN (K-Nearest Neighbors)

Dataset

The project utilizes the FER2013 facial emotion dataset for emotion recognition training and testing. The model classifies facial expressions into seven emotion categories before using the emotion distribution for performance prediction.

System Workflow
Student Video Input
        ↓
Face Detection (OpenCV Haar Cascade)
        ↓
Emotion Recognition (CNN)
        ↓
Emotion Count Generation
        ↓
Feature Extraction
        ↓
KNN Classification
        ↓
Performance Prediction
(Executed / Not Executed)

Model Architecture
Emotion Recognition
A CNN-based emotion recognition model processes facial images and classifies them into seven emotional states. The architecture consists of:
Convolution Layers
Batch Normalization
Pooling Layers
Fully Connected Layers
Softmax Output Layer

Performance Prediction

The detected emotion frequencies are stored as features and passed to a KNN classifier, which predicts whether the student successfully completed the coding task.

Results

Successfully classified student emotions from video input
Predicted student task completion status
Achieved approximately 86% classification accuracy on custom datasets
Demonstrated the potential of emotion-aware educational analytics systems

Future Enhancements
Integration with online learning platforms
Real-time dashboard for educators
Transformer-based emotion recognition models
Multi-modal analysis using voice and facial expressions
Improved accuracy through larger datasets

Conclusion

This project demonstrates how Deep Learning and Machine Learning can be combined to assess student performance through emotional behavior analysis. By leveraging CNN-based emotion recognition and KNN classification, the system provides valuable insights into student engagement and learning outcomes, reducing the limitations of traditional assessment methods.
