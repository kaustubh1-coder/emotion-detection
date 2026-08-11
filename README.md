# Final Project
# Emotion Detection

## Project Description

Emotion Detection is a Python-based application that analyzes text and identifies the emotions expressed in the text. The application uses the Watson NLP Emotion library to detect five emotions: anger, disgust, fear, joy, and sadness.

The application also identifies the dominant emotion based on the highest emotion score.

## Features

- Detects emotions from text input.
- Identifies:
  - Anger
  - Disgust
  - Fear
  - Joy
  - Sadness
- Determines the dominant emotion.
- Provides a Flask-based web interface.
- Handles blank or invalid input with HTTP status code 400.
- Includes unit tests for the emotion detection application.
- Uses Pylint for static code analysis.

## Project Structure

```text
emotion-detection/
│
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detector.py
│
├── templates/
│   └── index.html
│
├── server.py
├── test_emotion_detection.py
└── README.md
