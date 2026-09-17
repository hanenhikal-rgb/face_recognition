# Real-Time Face Detection

A lightweight Python application that captures live video from your webcam and detects human faces in real time using OpenCV and the Haar Cascade classifier.

## Features

* Real-time webcam stream acquisition.
* Fast face detection using pre-trained Haar Cascades.
* Displays bounding boxes around detected faces.
* Live on-screen counter showing the number of detected faces.
* Mirrored video view for a natural user experience.

## Prerequisites

* Python 3.8+
* A working webcam
* Operating System: Windows, macOS, or Linux

## Installation

1. Clone or download this repository to your local machine.
2. Install the required dependency:

```bash
pip install -r requirements.txt
```

3. Ensure the pre-trained model file `haarcascade_frontalface_default.xml` is located in the same directory as the script.

## Usage

Run the face detection script using Python:

```bash
python face_detection.py
```

*(Replace `face_detection.py` with your actual file name if it differs).*

> **Tip:** Press the **q** key on your keyboard while focusing on the video window to close the application and release the camera.
