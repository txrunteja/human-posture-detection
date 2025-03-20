# Human Posture Detection

## Overview
This project focuses on detecting human posture using OpenCV and MediaPipe. Maintaining good posture is essential for physical and mental well-being, as poor posture can lead to chronic discomfort, mobility issues, and musculoskeletal disorders.

With an increasing number of software developers and professionals working long hours at desks, posture-related problems are becoming more prevalent. This project aims to analyze and determine whether a person's posture is good or bad based on body angles calculated from tracked distance vectors.

## Features
- **Posture Classification**: Determines whether the detected posture is good or bad.
- **Real-time Pose Estimation**: Uses OpenCV and MediaPipe to track human body joints.
- **Angle Calculation**: Measures angles between key body joints to assess posture.
- **Lightweight & Efficient**: Utilizes pre-trained models for fast and accurate results.

## Technologies Used
- **Python**
- **OpenCV** - Open-source computer vision and machine learning library.
- **MediaPipe** - Google's framework for real-time pose estimation.

## How It Works
1. **Pose Detection**: MediaPipe collects 33 key body points such as shoulders, elbows, etc.
2. **Angle Calculation**: Computes angles between body joints to analyze posture.
3. **Posture Classification**: Determines whether the posture is correct or incorrect.

## Installation
### Clone the repository:
```bash
git clone https://github.com/txrunteja/human-posture-detection.git
cd human-posture-detection
