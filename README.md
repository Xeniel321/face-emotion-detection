# Facial Emotion Recognition using CNN

## Overview
This project implements a Facial Emotion Recognition system using a Convolutional Neural Network (CNN).
It detects human emotions from facial expressions in images using deep learning techniques.

The model uses Haar Cascade classifiers for face detection and a trained CNN model for emotion classification.

---

## Features
- Detects emotions from human faces
- CNN-based deep learning model
- Face detection using Haar Cascade
- Pre-trained model included

---

## Project Structure

project/
│── src/
│   └── emotion_detection_cnn.ipynb
│
│── models/
│   ├── model.json
│   └── model.h5
│
│── assets/
│   ├── haarcascade_frontalface_default.xml
│   ├── haarcascade_frontalface_alt2.xml
│   └── images/
│
│── data/                (dataset not included)
│── requirements.txt
│── README.md
│── LICENSE

---

## Dataset

This project uses the FER2013 dataset.

Dataset is not included due to size.
You can download it from:
https://www.kaggle.com/datasets/msambare/fer2013

---

## Model Details

Model Type: Convolutional Neural Network (CNN)

Emotions Detected:
- Happy
- Sad
- Angry
- Surprise
- Neutral
- Fear
- Disgust

---

## Usage

Run Jupyter Notebook:

jupyter notebook

Open:
emotion_detection_cnn.ipynb

---

## Requirements

- tensorflow
- keras
- numpy
- opencv-python
- matplotlib
- pandas
- jupyter

---

## Future Improvements

- Real-time webcam emotion detection
- Improve model accuracy
- Deploy as a web app
- Use advanced models like ResNet

---

## License

This project is licensed under the LICENSE file.

---

## Contribution

Feel free to fork and improve this project.