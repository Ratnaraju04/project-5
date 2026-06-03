Project Title

Chest X-Ray Disease Classification Using CNN and Deep Learning

What You Built

You developed a Convolutional Neural Network (CNN) that classifies chest X-ray images into four categories:

Normal
Pneumonia
Tuberculosis
Unknown
Technologies Used
Python
TensorFlow / Keras
CNN (Convolutional Neural Network)
NumPy
Pillow (PIL)
Flask
Kaggle Dataset
Joblib
Dataset

You used the Kaggle dataset:

Combined Unknown, Pneumonia and Tuberculosis Chest X-Ray Dataset

The dataset contains:

Train set
Validation/Test set
Four image classes
Model Architecture

Your CNN consists of:

Input Image (64×64 Grayscale)
        ↓
Conv2D (32 Filters, 3×3, ReLU)
        ↓
MaxPooling2D
        ↓
Flatten
        ↓
Dense (128, ReLU)
        ↓
Dense (4, Softmax)
Workflow
Download dataset using KaggleHub
Preprocess images
Resize to 64×64
Convert to grayscale
Normalize pixel values
Train CNN model
Predict disease class
Save model as:
XRay_Model.joblib
XRay_Model.keras
Deploy using Flask web application
Resume Project Description
Chest X-Ray Disease Classification using Deep Learning
Developed a CNN-based medical image classification system to detect Normal, Pneumonia, Tuberculosis, and Unknown conditions from chest X-ray images.
Implemented image preprocessing, normalization, and grayscale conversion using TensorFlow and NumPy.
Built and trained a deep learning model using TensorFlow/Keras with Softmax-based multi-class classification.
Achieved automated disease prediction through a Flask web application with real-time image upload and inference capabilities.
Deployed the trained model using .keras and .joblib formats for production-ready predictions.
Naukri Project Description (Short Version)

Chest X-Ray Disease Classification | TensorFlow, CNN, Flask

Built a CNN-based deep learning model for classifying chest X-ray images into Normal, Pneumonia, Tuberculosis, and Unknown categories.
Performed image preprocessing, model training, and real-time prediction using TensorFlow/Keras.
Deployed the solution through a Flask web application for automated disease detection.
