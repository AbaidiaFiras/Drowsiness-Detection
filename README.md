# Drowsiness-Detection
Drowsiness Detection System
This project is a drowsiness detection system that uses a Convolutional Neural Network (CNN) model and Haar Cascade classifier. It is implemented in Python using the TensorFlow and Keras frameworks. The system is designed to monitor a driver's alertness by analyzing video frames in real-time.

Overview
The system begins by detecting the driver's face using a Haar Cascade classifier.
Once the face is detected, the system extracts the driver's eyes from the video frames.
The CNN model is then used to classify whether the driver's eyes are open or closed.
If the driver's eyes are detected as closed for a precise number of successive frames, an alert is triggered to notify the driver.
Dataset
The dataset used for training the CNN model was obtained from Kaggle. It contains labeled images of both open and closed eyes, which are essential for training the model to make accurate predictions.

Usage
Clone the repository to your local machine.
Install the required dependencies, including TensorFlow and OpenCV.
Run the system by executing the main script.
The system will start capturing video frames and monitoring the driver's drowsiness.
Dependencies
TensorFlow
OpenCV
File Structure
main.py: The main script to run the drowsiness detection system.
cnn_model.py: Contains the CNN model architecture and training code.
haarcascade.xml: The Haar Cascade classifier for face detection.
data/: A directory containing the dataset used for training the model.
License
This project is licensed under the MIT License.

Acknowledgments
The Haar Cascade classifier was provided by OpenCV.
The dataset used for training the model was obtained from Kaggle.
Contributing
If you'd like to contribute to this project, please open an issue or a pull request.
