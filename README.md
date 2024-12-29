# Drowsiness Detection

This project implements a **Drowsiness Detection System** to enhance safety by monitoring driver alertness. It leverages computer vision techniques to identify signs of drowsiness in real-time using facial landmarks.

## Features

- **Real-Time Monitoring**: Detects drowsiness using a webcam or video input.
- **Facial Landmark Detection**: Identifies eye, mouth, and head positions to assess alertness.
- **Alert System**: Triggers alerts when signs of drowsiness are detected.

## Workflow

1. **Facial Landmark Detection**:
   - Uses pre-trained models for detecting key facial features (e.g., eyes, nose, mouth).

2. **Eye Aspect Ratio (EAR)**:
   - Calculates EAR to determine eye closure levels, indicating drowsiness.

3. **Mouth Aspect Ratio (MAR)**:
   - Detects yawning as a sign of fatigue.

4. **Alert Mechanism**:
   - Generates an alert sound or message when drowsiness is detected.

## Technologies Used

- **Python**: For scripting and processing.
- **OpenCV**: For real-time video processing.
- **Dlib**: For facial landmark detection.

