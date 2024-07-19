## Overview

This project implements face key points detection using machine learning. It identifies specific facial features such as eyes, nose, and mouth in real-time. This technology is crucial for applications in facial recognition, emotion detection, augmented reality, healthcare, and human-computer interaction.

## Features

- **Real-Time Detection**: Detects facial landmarks in real-time using your webcam.
- **Face Mesh**: Utilizes MediaPipe's Face Mesh model to identify key facial features.
- **Visualization**: Draws landmarks and connections on detected faces.

## Requirements

- Python 3.x
- OpenCV
- MediaPipe

Install the required libraries using pip:

```bash
pip install opencv-python mediapipe
```

## Usage

1. **Run the Script**: Execute the script to start detecting face key points using your webcam.

```bash
python face_key_points_detection.py
```

2. **Interaction**:
    - The webcam feed will display with detected facial landmarks.
    - Press 'q' to exit the application.

## Code Overview

- **Video Capture**: Captures video feed from the webcam.
- **Face Mesh Detection**: Uses MediaPipe's Face Mesh solution to detect and process facial landmarks.
- **Drawing Landmarks**: Draws facial landmarks and connections on the detected faces.
- **Real-Time Display**: Shows the video feed with annotations in a window.

## Notes

- Ensure your webcam is connected and accessible.
- The script displays detected landmarks and their connections in real-time.
- Adjust `max_num_faces`, `min_detection_confidence`, and `min_tracking_confidence` as needed for your application.
