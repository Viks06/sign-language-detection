
# Project Title

A brief description of what this project does and who it's for
Sign Language Detection Using Machine Learning

# Overview

This project uses a machine learning model to detect and classify hand gestures representing sign language. It leverages OpenCV for video capture, MediaPipe for hand tracking, and a pre-trained model to classify gestures into predefined categories.

# Features

Real-time hand detection using MediaPipe
Gesture classification using a trained ML model
Supports multiple sign language gestures

# Technologies Used

1. Python

2. OpenCV

3. MediaPipe

4. Scikit-learn

5. NumPy

6. Pickle (for model loading)

# Installation

Clone the repository:

git clone https://github.com/your-repo/sign-language-detection.git
cd sign-language-detection

Install dependencies:

pip install opencv-python mediapipe numpy scikit-learn

Ensure you have the trained model file (model.p) in the project directory.

Usage

    Run the inference script:

    python inference_classifier.py

The webcam will open and start detecting hand gestures.

The detected gesture will be displayed on the screen.

    Press q to exit the program.

File Structure

inference_classifier.py - Main script to run real-time sign language detection

model.p - Pre-trained ML model for gesture classification

# How It Works

Captures real-time video from the webcam.

Uses MediaPipe to detect hand landmarks.

Extracts and normalizes landmark coordinates.

Feeds the extracted data into the trained ML model.

Displays the predicted gesture on the screen.

# Supported Gestures

The model currently recognizes the following gestures:

A, B, C, D

HI

YES

THANKS

PEACE

KON(custom gesture)

# Future Improvements

Expand the dataset to support more gestures
Improve model accuracy with additional training
Develop a user interface for better interaction
