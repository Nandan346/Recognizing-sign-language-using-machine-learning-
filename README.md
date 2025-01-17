# Hand Gesture Recognition Using Flask and OpenCV

This project is a web-based hand gesture recognition application built using Flask, OpenCV, and a pre-trained TensorFlow/Keras model. It detects hand gestures in real time through a webcam feed and classifies them into predefined labels.

## Features
- Real-time hand detection and gesture recognition.
- Utilizes a custom-trained deep learning model (`keras_model.h5`) for gesture classification.
- Displays live video feed with recognized gestures and bounding boxes.
- Easy-to-use Flask web interface.

## Requirements
- Python 3.8+
- Flask
- OpenCV
- cvzone
- TensorFlow/Keras
- NumPy

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/hand-gesture-recognition.git
   cd hand-gesture-recognition
   
pip install -r requirements.txt

python app.py
hand-gesture-recognition/
│
├── app.py                  # Main application script
├── templates/
│   └── index.html          # HTML template for the web interface
├── Model/
│   ├── keras_model.h5      # Pre-trained gesture recognition model
│   └── labels.txt          # Corresponding labels for the model
├── static/
│   └── css/                # (Optional) Custom styles for the interface
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
