# Face Detection using OpenCV

## Overview

This project is a real-time Face Detection application developed using Python and OpenCV. It uses the Haar Cascade Classifier to detect human faces from a live webcam feed and displays bounding boxes around the detected faces.

The project demonstrates the fundamentals of computer vision, image processing, and real-time video analysis using OpenCV.

---

## Features

- Real-time face detection using a webcam
- Detects multiple faces simultaneously
- Displays bounding boxes around detected faces
- Labels detected faces
- Press **Q** to exit the application
- Beginner-friendly implementation

---

## Technologies Used

- Python
- OpenCV
- Haar Cascade Classifier

---

## Project Structure

```
Face_Detection/
│
├── main.py
├── haarcascade_frontalface_default.xml
└── README.md
```

---

## Prerequisites

- Python 3.0 or latest version
- OpenCV

---

## Installation

1. Clone the repository.

```bash
git clone https://github.com/Viransh29/Face_Detection.git
```

2. Navigate to the project directory.

```bash
cd Face_Detection
```

3. Install OpenCV.

```bash
pip install opencv-python
```

---

## How to Run

Execute the following command:

```bash
python main.py
```

A webcam window will open and begin detecting faces in real time.

Press **Q** to close the application.

---

## How It Works

1. Opens the default webcam.
2. Captures video frames continuously.
3. Converts each frame to grayscale.
4. Detects faces using the Haar Cascade classifier.
5. Draws a bounding box around each detected face.
6. Displays the number of faces detected in the camera.

---

## Learning Outcomes

This project helped in understanding:

- Image processing fundamentals
- Face detection using Haar Cascade
- OpenCV library
- Real-time webcam processing
- Drawing shapes and text on images
- Computer Vision basics
