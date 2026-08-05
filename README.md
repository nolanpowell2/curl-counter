# MediaPipe Pose Estimation & Bicep Curl Counter Practice

A practice project built to learn computer vision basics using Python, OpenCV, and MediaPipe. 

This repository documents my implementation of real-time human pose tracking to build a basic bicep curl counter that tracks reps and calculates joint angles from a webcam feed.

## What I Learned & Built

- Set up a real-time webcam video stream using OpenCV.
- Used MediaPipe (0.10.14) to extract 3D pose landmarks (shoulders, elbows, wrists).
- Applied basic vector trigonometry with NumPy (arctan2) to dynamically calculate arm joint angles frame-by-frame.
- Built rep-counting logic to track bicep curls as the elbow angle transitions between extension and flexion.
- Visualized skeleton tracking, live angle readouts, and the rep counter directly on the video window.

## Built With

- Python 3.11
- OpenCV
- MediaPipe
- NumPy

![Demo]("curl-counter-demo.gif")