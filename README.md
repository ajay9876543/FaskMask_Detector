Face Mask Detection System

A real-time deep learning project that detects whether a person is wearing a face mask using TensorFlow, Keras, OpenCV, and MobileNetV2. The system processes live video streams or static images and classifies mask usage with high accuracy, making it suitable for public safety monitoring and workplace compliance.


Features

Real-time mask detection via webcam or video input.

High accuracy using MobileNetV2 transfer learning.

Image preprocessing and augmentation for robust model performance.

Works with both images and live video streams.

Easily extendable for deployment in security systems.

Technologies Used

Python

TensorFlow & Keras

OpenCV

MobileNetV2

NumPy, Imutils

How It Works

Preprocess input frames (resize, normalize, augment).

Pass frames through MobileNetV2-based model.

Classify as Mask or No Mask in real time.

Display results with bounding boxes on video stream.
