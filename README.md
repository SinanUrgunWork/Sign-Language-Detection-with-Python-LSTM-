# Sign Language Detection with Python and LSTM

## Overview

The **Sign Language Detection with Python and LSTM** project aims to recognize specific hand signs from American Sign Language (ASL) using computer vision and deep learning techniques. This project focuses on detecting three signs: "hello," "I love you," and "thanks." The system leverages the MediaPipe library for hand landmark detection and utilizes a Long Short-Term Memory (LSTM) network for gesture recognition.

## Features

- **Real-Time Detection**: Detects ASL signs in real-time using a webcam.
- **Customizable**: Designed to recognize specific hand signs, which can be extended to include more signs.
- **Accuracy**: High accuracy achieved with LSTM networks, offering reliable gesture recognition.
- **Visualization**: Provides visual feedback with landmarks and gesture predictions displayed on the video feed.

## Technologies Used

- **Python**: Programming language used for implementation.
- **TensorFlow/Keras**: Deep learning framework for building and training the LSTM model.
- **MediaPipe**: Library for hand and body landmark detection.
- **OpenCV**: Library for video capture and image processing.
- **NumPy**: Library for numerical operations and data handling.
- **Matplotlib**: Library for data visualization and plotting.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/pose-detection-action-recognition.git
    cd pose-detection-action-recognition
    ```

2. Install the required packages:
    ```bash
    pip install --upgrade pip
    pip install tensorflow opencv-python mediapipe sklearn matplotlib
    ```


