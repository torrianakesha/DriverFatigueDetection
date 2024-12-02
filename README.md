# Drowsy Driver Detection System

This project is a **real-time driver fatigue detection system** that uses **machine learning** and **temporal analysis** to identify signs of drowsiness in drivers. The system leverages the YOLOv5 model for object detection and processes live video from a camera feed to monitor driver behavior.

---

## Features
- **Real-Time Video Processing**: Captures live video feed from the camera.
- **YOLOv5 Integration**: Utilizes a pre-trained YOLOv5 model to analyze frames for signs of drowsiness.
- **Dark Mode Interface**: A user-friendly GUI designed with `customtkinter`.
- **Cross-Platform**: Works on major operating systems with Python and OpenCV support.

---

## Installation

### Prerequisites
- Python 3.8+
- pip (Python package installer)
- Git

### Clone the Repository wqdas
```bash 
git clone https://github.com/yourusername/DrowsyDriverDetection.git
cd DrowsyDriverDetection
```

### Install Required Packages
```bash 
pip install -r requirements.txt
```

### Ensure you have the following packages in your requirements.txt:
- torch
- numpy
- opencv-python
- Pillow
- customtkinter
