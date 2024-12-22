# Hand-Gesture-Volume-Control
Hand Gesture-Based Volume Control is a Python project that utilizes OpenCV and Mediapipe to detect hand gestures and control the system volume dynamically. This interactive system tracks specific hand landmarks and translates gestures into volume adjustment commands, offering a touchless way to control audio levels.


# Hand Gesture-Based Volume Control  

## Description  
This project implements a hand gesture-based system to control the system volume using Python, OpenCV, and Mediapipe. The application detects specific hand gestures in real-time via webcam and adjusts the system's volume accordingly.  

### Features  
- Real-time hand tracking using Mediapipe.  
- Gesture recognition to map hand gestures to volume levels.  
- Dynamic volume adjustment based on the distance between specific hand landmarks (e.g., thumb and index finger).  
- Simple and intuitive interface with a live video feed for tracking.  


## Installation  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/gauravsharma5166/Hand-Gesture-Volume-Control.git  
   cd Hand-Gesture-Volume-Control

2. Install the required dependencies:

pip install -r requirements.txt  

3. Run the application:
   python volume_control.py  


Requirements
Python 3.7+
OpenCV
Mediapipe
Pycaw (for controlling system volume)



