## Overview
This project implements a real-time emotion detection system using computer vision and deep learning techniques. The system detects faces in a live video stream from a webcam and predicts the corresponding emotion for each face detected. Emotions recognized include Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

## How to Run
To run the Emotion Detector, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Python installed.
3. Install the required dependencies by running:
    ```
    pip install -r requirements.txt
    ```
4. Run the `emotion_detector.py` script:
    ```
    python emotion_detector.py
    ```
5. The webcam will activate, and the emotion detection system will start analyzing the live video feed.

## Project Components
- `emotion_detector.py`: Main Python script implementing the emotion detection system.
- `haarcascade_frontalface_default.xml`: Haar cascade classifier file for face detection.
- `model.h5`: Trained Keras model for emotion classification.

## Model Information
The model used for emotion classification was trained using a dataset of facial expressions. It consists of a convolutional neural network (CNN) architecture trained on thousands of images labeled with different emotions.

## Screenshots
![neutral](https://github.com/akshat-agr/Emotion-Detector/assets/134093103/99c42614-f432-4f92-8853-a28fd51663af)
![happy](https://github.com/akshat-agr/Emotion-Detector/assets/134093103/a36456f6-5fcc-45c1-ad84-31c5a0065814)
![surprise](https://github.com/akshat-agr/Emotion-Detector/assets/134093103/7d5e7817-0edc-40a4-8fdc-5b4d5c3c7281)
