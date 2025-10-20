# The Pitch of Sound with Motion Gesture

Control your computer’s volume using hand gestures with this fun and interactive project built using Python, OpenCV, MediaPipe, and PyAutoGUI.
Simply move your thumb and index finger apart or closer, and the system will increase or decrease the sound volume — no need to touch your keyboard or mouse!

# Project Overview

This project uses computer vision to detect hand movements through your webcam.
When the distance between your thumb and index finger changes, the program interprets that as a gesture to either increase or decrease the system volume.

# Technologies Used

Python 3.x

OpenCV – for webcam access and image processing

MediaPipe – for real-time hand tracking and landmark detection
  
PyAutoGUI – to control system volume programmatically

# How It Works

The webcam captures your hand in real time.

MediaPipe detects hand landmarks (key points like finger tips).

The program measures the distance between the index finger tip (ID 8) and thumb tip (ID 4).

If the distance is greater than 50 pixels, the system increases the volume.
If the distance is less than 50 pixels, it decreases the volume.
