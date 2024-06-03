# Emotion Detection Project

## Overview

This project aims to develop a real-time emotion detection system using computer vision and deep learning techniques. The system captures video input from a webcam, detects faces, and classifies emotions based on facial expressions. The project utilizes pre-trained models and implements a user-friendly interface to display emotion predictions.

## File Descriptions

### 1. `emotion_app.py`

This script captures video from a webcam, detects faces using a Haar Cascade Classifier, and classifies emotions using a pre-trained ResNet50 model. The script displays the video feed with detected faces and emotion labels.

### 2. `test.py`

Similar to `emotion_app.py`, this script captures video, detects faces, and classifies emotions. It provides an option to load different pre-trained models and uses a custom CNN model or a ResNet50 model for emotion classification.

### 3. `Emotion_Detection_Complete_Project.ipynb`

This Jupyter Notebook contains the complete workflow of the project, including data preprocessing, model training, and evaluation. It provides detailed insights and visualizations to help understand the project implementation and performance.

## How to Run

1. **Install Dependencies**:
   Ensure you have the necessary libraries installed. You can install the required libraries using the following command:
   ```bash
   pip install -r requirements.txt
   ```

2. **Download Pre-trained Models**:
   Ensure you have the pre-trained models (`Final_Resnet50_Best_model.keras` or `Custom_CNN_model.keras`) and place them in the appropriate directory.

3. **Run the Scripts**:
   To start the emotion detection system, run either of the Python scripts:
   ```bash
   python emotion_app.py
   ```
   or
   ```bash
   python test.py
   ```

4. **Interact with the Application**:
   The application will open a window displaying the video feed with detected faces and their corresponding emotion labels. Press `q` to quit the application.

