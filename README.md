#Final Project
# Repository for final project
# Emotion Detection Web Application

## Project Overview
This project is part of the IBM Skills Network final project on AI-based web application development. It uses the Watson NLP Emotion Detection service to identify emotions expressed in a text statement.

## Features
- Detects anger, disgust, fear, joy, and sadness.
- Identifies the dominant emotion.
- Provides a web interface using Flask.
- Handles empty or invalid input.
- Includes unit tests and code quality checks.

## Technologies Used
- Python
- Flask
- Requests
- Watson NLP Emotion Detection API
- PyLint

## Project Structure
```text
oaqjp-final-project-emb-ai/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
```

## Installation
Install the required packages:

```bash
pip install flask requests pylint
```

## Running the Application
Run the Flask server:

```bash
python server.py
```

Open `http://127.0.0.1:5000` in your browser.

## Testing
Run the unit tests:

```bash
python -m unittest test_emotion_detection.py
```

## Author
Avni Selote
