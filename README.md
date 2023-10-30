# Drowsiness-Detection

This project is a drowsiness detection system that uses a Convolutional Neural Network (CNN) model and Haar Cascade classifier. It is implemented in Python using the TensorFlow and Keras frameworks. The system is designed to monitor a driver's alertness by analyzing video frames in real-time.

# Overview
- The system begins by detecting the driver's face using a Haar Cascade classifier.
- Once the face is detected, the system extracts the driver's eyes from the video frames.
- The CNN model is then used to classify whether the driver's eyes are open or closed.
- If the driver's eyes are detected as closed for a precise number of successive frames, an alert is triggered to notify the driver.

# Dataset
- The dataset used for training the CNN model was obtained from Kaggle. It contains labeled images of both open and closed eyes, which are essential for training the model to make accurate predictions.
- Lien: [[kaggle datasets download -d kutaykutlu/drowsiness-detection](https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset)](https://www.kaggle.com/datasets/prasadvpatil/mrl-dataset)

# Usage
- Clone the repository to your local machine.
- Install the required dependencies, including TensorFlow ,OpenCV and requirement.txt.
- Run the system by executing the main script.
  
# Dependencies
- Python 3.11
- TensorFlow
- OpenCV

# File Structure
- drowsiness_demo.py: Run the infernce model.
- drowsiness_train.py: Contains the CNN model architecture and training code.
- haarcascade_frontalface.xml:  For face detection.
- haarcascade_lefteye_2splits.xml: For left eye detection.
- haarcascade_righteye_2splits.xml: For right eye detection.

# Contributing
If you'd like to contribute to this project, please open an issue or a pull request.
