# Python Motion Tracking Script

A simple Python script that tracks motion using a camera (webcam).  
The script detects movement in the video feed and highlights the motion areas in real-time.

---

## Features
- Uses **OpenCV** for video capture and motion detection
- Detects movement and highlights moving objects
- Real-time display of camera feed with motion tracking
- Works with any connected webcam
- Fully offline

---

## Requirements
- Python 3.8 or higher
- OpenCV
- NumPy

---

## Installation

### 1. Create a Virtual Environment (Recommended)
```bash
python -m venv venv


Activate it:

Windows

venv\Scripts\activate


Linux / macOS

source venv/bin/activate

2. Upgrade pip
python -m pip install --upgrade pip setuptools wheel

3. Install Required Libraries
pip install opencv-python numpy


Optional: If you want GUI support for OpenCV windows, install:

pip install opencv-python-headless

Usage

Run the script:

python motion_tracking.py

