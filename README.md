# Age_Detection-DeepLearning
<img width="478" height="327" alt="Screen Shot 2025-09-05 at 10 56 31 AM" src="https://github.com/user-attachments/assets/8f000c64-238e-48ae-a5a7-203fe4eed35b" />

## Wanna have Deep Learning guess your age??
 https://pritiks23.github.io/Age_Detection-DeepLearning/

This project demonstrates **real-time age estimation** using deep learning entirely in the browser. It leverages pre-trained models for face detection and age regression without any server-side components.

## Overview
The system uses a **client-side pipeline**:
1. **Face Detection:** Uses a TinyFaceDetector model to locate faces in the webcam feed.
2. **Age Estimation:** Predicts age using a pre-trained age regression model (`ageGenderNet`) from face-api.js.
3. **Stabilization:** Collects predictions over a 5-second window and returns the average age as the final output to reduce frame-to-frame variance.

## Features
- Real-time webcam capture and face detection.
- Stable age prediction via temporal averaging.
- Fully static and client-side; deployable on GitHub Pages.
- Professional golden-themed interface with responsive layout.

## Technologies
- **TensorFlow.js:** For running models in-browser.
- **face-api.js:** Provides pre-trained models for face detection and age/gender estimation.
- **HTML/CSS/JavaScript:** Fully static, modern front-end implementation.

## Usage
1. Open `index.html` in a modern browser or host via GitHub Pages.
2. Grant camera access.
3. The system analyzes faces for 5 seconds and outputs a stable age estimate.

## Notes
- Age prediction is a regression task; temporal averaging improves robustness.
- The system demonstrates **browser-based deep learning inference** with real-time computer vision.

## License
Open for educational and personal use.
