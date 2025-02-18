
# Real-Time Face Detection using OpenCV and SSD

## 📌 Overview

This script demonstrates real-time face detection using OpenCV and a pre-trained SSD (Single Shot MultiBox Detector) model. It captures video from a camera, detects faces, and displays the results with bounding boxes and confidence scores.

## ⚠️ Disclaimer

**This project is intended for educational purposes only. The author is not responsible for any misuse.**

## 🚀 Features

- Real-time face detection using a pre-trained SSD model.
- Displays bounding boxes and confidence scores for detected faces.
- Option to download and extract required assets automatically.

## 📂 Requirements

- Python 3.x
- OpenCV (`cv2`)
- `requests` library for downloading assets

## 🔧 Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/
Navigate to the project folder:
shCopy
cd face-detection
Install dependencies:
shCopy
pip install opencv-python requests
⚙️ Usage
Downloading Assets
The script will automatically download and extract the required assets if they are not found in the current directory. The assets include a pre-trained SSD model and its configuration file.
Running the Script
Run the script:
shCopy
python 1.py
The script will open a window displaying the camera feed with detected faces highlighted by bounding boxes and confidence scores.
Press ESC to exit the application.
Command-Line Arguments
You can specify the camera source as a command-line argument. For example:
shCopy
python 1.py 1
This will use the second camera (index 1) instead of the default camera (index 0).
