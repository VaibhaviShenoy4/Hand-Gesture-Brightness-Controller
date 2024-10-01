# 🔆 Hand Gesture-Based Brightness Control

This project demonstrates how to control your screen brightness using hand gestures detected through a webcam. It uses **OpenCV** and **MediaPipe** for hand detection, and **screen-brightness-control** for adjusting the brightness.

## 📸 Features
- Detects hand gestures using a webcam.
- Adjusts screen brightness by measuring the distance between your thumb and index finger.
- Real-time processing and visual feedback with OpenCV.

## 🚀 How it Works
1. The webcam captures your hand in real-time.
2. **MediaPipe** detects the hand and landmarks.
3. The distance between your thumb and index finger is calculated.
4. Based on this distance, the screen brightness is adjusted (closer = lower brightness, farther = higher brightness).
