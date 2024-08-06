Volume Control with Hand Gestures

Welcome to my project! 🎉 This repository contains a Python-based volume control system that uses hand gestures for operation. With this project, you can adjust your system volume just by moving your hands.

Project Overview
This project leverages several powerful tools and libraries to achieve hand gesture-based volume control:

Python: The primary programming language used.
OpenCV: For capturing and processing video frames from your webcam.
MediaPipe: For accurate hand tracking and landmark detection.
pynput: To simulate keyboard actions for controlling the system volume.

How It Works
Capture Video: Uses OpenCV to access the webcam and capture live video.
Hand Tracking: MediaPipe detects hand landmarks and calculates distances between specific points.
Volume Control: Based on the distance between landmarks, pynput simulates keyboard actions to adjust the volume up or down.
Real-Time Display: Displays video with overlayed hand landmarks to show gestures being detected.

Demo
Check out my LinkedIn post for a demo video of the project in action where I control the volume of a song using hand gestures: [LinkedIn Post](https://www.linkedin.com/posts/sanket-choudhary-825078245_deeplearning-ai-machinelearning-activity-7226470871677157376--s6Y?utm_source=share&utm_medium=member_desktop)

