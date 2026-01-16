# Gesture Control System (Karthik)

## Overview
A comprehensive hand gesture recognition system designed for intuitive human-computer interaction. This project explores advanced computer vision techniques to map complex hand movements to digital actions, serving as a prototype for next-gen accessibility tools.

## Features
-   **Multi-Hand Tracking**: Simultaneous detection of both left and right hands.
-   **Custom Gestures**: definable mapping for specific programmatic actions.
-   **Low Latency**: Optimized for real-time performance on standard webcams.
-   **OS Integration**: Direct control over mouse, keyboard, and system volume.

## Technology Stack
-   **Vision**: OpenCV, MediaPipe.
-   **Automation**: PyAutoGUI.
-   **Language**: Python 3.8+.

## Usage Flow
1.  **Calibrate**: System baselines the background and lighting.
2.  **Track**: Hand skeleton is extracted from the video frame.
3.  **Classify**: Geometric analysis determines the gesture pose.
4.  **Control**: Action is dispatched to the operating system.

## Quick Start
```bash
# Clone the repository
git clone https://github.com/Nytrynox/Gesture-Control-System.git

# Install requirements
pip install -r requirements.txt

# Launch controller
python gesture_control.py
```

## License
MIT License

## Author
**Karthik Idikuda**
