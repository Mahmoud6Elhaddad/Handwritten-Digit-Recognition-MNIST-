# Handwritten Digit Recognition (MNIST)

A deep learning project to recognize handwritten digits using the MNIST dataset.  
This project was developed as part of my Machine Learning Internship.

## Overview
- **Dataset:** MNIST (CSV format: train.csv, test.csv)
- **Model:** Convolutional Neural Network (CNN)
- **Frameworks:** TensorFlow/Keras
- **Techniques Used:** EarlyStopping, ModelCheckpoint, Confusion Matrix

## Project Workflow
1. **Data Preprocessing:**
   - Normalized pixel values to range [0, 1]
   - Reshaped images to (28, 28, 1)

2. **Model Building:**
   - CNN with Conv2D, MaxPooling, Flatten, Dense layers
   - Optimizer: Adam
   - Loss: Categorical Crossentropy

3. **Training:**
   - Implemented EarlyStopping and ModelCheckpoint
   - Trained on train.csv and validated using a validation split

4. **Evaluation:**
   - Accuracy: **99%** 
   - Confusion Matrix for detailed performance analysis

## Results
- Achieved high accuracy in digit recognition
- Tested on sample images from test.csv
- Predictions visualized using Matplotlib
