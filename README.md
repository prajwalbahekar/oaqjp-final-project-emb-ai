# Emotion Detection Application

## Project Overview
This project uses IBM Watson Natural Language Processing to detect emotions expressed in a given text.

## Features
- Detects five emotions: anger, disgust, fear, joy, and sadness.
- Identifies the dominant emotion.
- Provides a Flask-based web application for users to submit text.
- Handles invalid or empty text inputs.

## Technologies Used
- Python
- IBM Watson Emotion Detection API
- Flask
- Requests
- unittest
- PyLint

## Project Structure
- `EmotionDetection/` — Emotion detection package.
- `server.py` — Flask web application.
- `test_emotion_detection.py` — Unit tests.
- `templates/` — HTML templates.
- `static/` — Frontend JavaScript and static assets.

## How to Run
1. Install the required dependencies.
2. Run the application using `python3 server.py`.
3. Open the application through the configured port 5000.
4. Enter text to analyze its emotions.

## Testing
Unit tests were executed successfully, and static code analysis with PyLint achieved a score of 10/10.
