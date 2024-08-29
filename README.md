# Face Recognition Attendance System

This project is a face recognition-based attendance system that detects and identifies employees in a group photo. The system uses YOLO for face detection and the `face_recognition` library for recognizing known faces based on pre-saved images.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sajithamma/face-detection/blob/main/face-detection-yellowzapp.ipynb)


## Features

- **Face Detection**: Detects faces in a group photo using YOLO.
- **Face Recognition**: Matches detected faces against pre-saved images of employees.
- **Attendance Marking**: Identifies employees and can be used to mark attendance based on the detected faces.
- **Visualization**: Displays the group photo with bounding boxes around faces and labels with employee names.

## Setup

### Prerequisites

- Python 3.x
- Google Colab (or any Python environment with a GPU)

### Required Libraries

Install the required libraries using pip:

```bash
pip install face_recognition dlib Pillow matplotlib
