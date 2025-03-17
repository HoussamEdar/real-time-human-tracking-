# Real-Time Human Tracking with YOLO and DeepSORT

## Overview
This project implements real-time human tracking using the YOLO (You Only Look Once) model for person detection and DeepSORT for multi-object tracking. The system processes live video streams from an RTSP camera, ensuring efficient detection and tracking of humans with optimized deep learning models.

## Features
- **Real-Time Human Detection**: Uses YOLO for fast and accurate person detection.
- **Multi-Person Tracking**: Implements DeepSORT to track multiple humans across frames.
- **Asynchronous Video Processing**: Utilizes threading to optimize video frame capture and processing.
- **GPU Acceleration**: Supports GPU-based inference for enhanced performance.

## Installation
### Prerequisites
Ensure you have Python installed (Python 3.8+ recommended). Install the required dependencies using:
```bash
pip install -r requirements.txt
```

### Required Dependencies
- OpenCV
- Ultralytics YOLO
- DeepSORT
- NumPy
- Threading (built-in Python module)

## Usage
### Running the Tracker
To start the human tracking system, run:
```bash
python tracking.py
```
Replace the `rtsp_url` in the script with your camera's RTSP stream address.

## Project Structure
```
Real-Time Human Tracking
├── tracking.py        # Main script for human tracking
├── yolo11n.pt         # YOLO model weights
├── requirements.txt   # Dependencies
└── README.md         # Project documentation
```

 
