# Virtual Mouse-Hand Gesture Control
This project implements an AI-based virtual mouse that can be controlled using hand gestures. The system uses Python, OpenCV, MediaPipe, and PyAutoGUI libraries to detect hand gestures from a webcam feed and translate them into mouse movements and actions.

## Prerequisites
Make sure you have the following dependencies installed on your system:

Python (version 3.7 or higher)

OpenCV (version 4.5.1 or higher)

MediaPipe (version 0.8.7 or higher)

PyAutoGUI (version 0.9.52 or higher)



## How It Works
The virtual mouse system works in the following steps:

1.It captures frames from the webcam feed.

2.The captured frames are processed using OpenCV to detect the hand landmarks using the MediaPipe library.

3.Based on the detected hand landmarks, the system identifies the position of the index finger and the palm.

4.It calculates the distance and angle between the index finger and the palm.

5.The distance and angle are used to control the mouse movement and actions.

6.The PyAutoGUI library is used to move the mouse cursor and perform mouse actions such as left-click, right-click, etc., based on the hand gestures.

7.The process continues in real-time, allowing you to control the mouse using your hand gestures.
