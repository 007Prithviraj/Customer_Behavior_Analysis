# Customer_Behavior_Analysis

This project aims to detect various types of toxic comments (toxic, severe toxic, obscene, threat, insult, identity hate) using a multi-label classification model built with deep learning. The pipeline includes:

Data preprocessing and tokenization using Keras

Focal loss to handle class imbalance

A custom neural network model

Evaluation using classification metrics (precision, recall, F1)

Visualization of training vs validation metrics

Saving/loading the model for reuse

Real-time prediction on new comments

 Model Type: Custom Sequential Neural Network
 Loss Function: Focal Loss (γ = 2.0, α = 0.25)
 Dataset: Jigsaw Toxic Comment Classification (Kaggle)
 Tech Stack: Python, TensorFlow/Keras, scikit-learn, Matplotlib

This project was completed as part of the IIT Madras Data Science curriculum by Prithviraj Dwivedy, B.Tech CSE, BML Munjal University.

