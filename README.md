# 🖐️ Gesture Volume Control using OpenCV & MediaPipe

<div align="center">
  <img alt="output" src="pictures/demo.gif" />
 </div>

 Control your Windows system volume using just your hand gestures. This Python project uses your webcam to track the distance between your thumb and index finger and adjusts your computer's volume accordingly.

 ## 🚀 Features

- Real-time hand tracking using MediaPipe
- Volume control based on distance between thumb and index finger
- Clean webcam interface with on-screen volume percentage
- Smoothing to avoid jittery volume jumps
- Mirror image view for intuitive control

## 🛠️ Tech Stack

- Python 3.10
- OpenCV
- MediaPipe
- Pycaw
- NumPy

## 🔧 Installation

1. **Install Python 3.10**  

2. **Install required packages**
> pip install opencv-python mediapipe comtypes numpy pycaw

3. **Download the Python script (main.py)**

4. **Run the script:**
> python main.py

5. **Press q to exit**

## 🎯 How It Works

- MediaPipe detects your hand and identifies landmarks.
- The script calculates the distance between your thumb and index finger.
- This distance is mapped to a volume level using Pycaw.
- The longer the distance, the louder the system volume.
- Everything updates live with your webcam feed.

## ⚠️ Requirements

- Windows OS (Pycaw works only on Windows)
- A functional webcam
