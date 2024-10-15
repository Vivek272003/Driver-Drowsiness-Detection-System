# Driver-Drowsiness-Detection-System
This system is designed to monitor drivers in real-time, detect drowsiness based on facial features, and issue alerts to prevent accidents caused by fatigue.

## Features
-Drowsiness Detection: Monitors eye aspect ratio (EAR) to detect fatigue.
Alerts: Provides audio and visual warnings when drowsiness is detected.
Face Recognition (Optional): Verifies the driver's identity for security.
Reports: Logs events and generates behavior reports.

## Technologies Used
Languages: Python
Libraries: OpenCV, Dlib, TensorFlow, Keras, Tkinter
Other: Haar Cascades, InceptionV3, Pygame

## System Overview
Data Preparation: Organizes datasets of open and closed eyes.
Model Training: Uses InceptionV3 for feature extraction and custom layers for classification.
Real-Time Detection: Captures video, detects faces/eyes, and triggers alerts if drowsiness is detected.

## Installation
Clone the repo: git clone https://github.com/yourusername/driver-drowsiness-detection-system.git
Install dependencies: pip install -r requirements.txt
Run detection: python drowsiness_detection.py

## Usage
Run the script to start real-time monitoring.
Press q to exit.

## Future Enhancements
Multi-camera support, mobile app integration, predictive analytics, and vehicle system integration.
