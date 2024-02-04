# Hand Tracking Module with MediaPipe and OpenCV

This repository contains a Python implementation of a hand tracking module using the MediaPipe library and OpenCV. The module provides real-time hand tracking, allowing you to detect and visualize hand landmarks on the video feed from your camera.

## Compatibility

- **Python Versions:** Compatible with Python versions 3.6 to 3.10.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Devk077/hand-tracking-
   ```

2. **Install Dependencies:**
   - Navigate to the project directory.
   - Install the required dependencies using the provided `requirements.txt` file.
   ```bash
   pip install -r requirements.txt
   ```

   - Execute the provided Python script.
   ```bash
   python run.py
   ```

3. **Explore the Features:**
   - The module tracks hand landmarks in real-time and displays them on the video feed.
   - The frames per second (fps) are also calculated and shown on the screen.
   - Customize the tracking behavior by adjusting parameters in the `handDetector` class.

## Code Overview

### `run.py`

This script initializes the hand tracking module using the `HandDetector` class and captures video from the default camera. It continuously processes frames, detects hands, and visualizes landmarks. The frame rate is calculated and displayed on the screen.

### `HandTrackingModule.py`

This module encapsulates the hand tracking functionality. It includes a `handDetector` class with methods to find hands and their positions. The `mediapipe` library is utilized for hand tracking, and OpenCV is used for drawing and visualization.

## Dependencies

- [OpenCV](https://opencv.org/): A powerful computer vision library.
- [MediaPipe](https://mediapipe.dev/): A library by Google for building perception pipelines.

## Acknowledgments

- This module is built using the capabilities of the MediaPipe library, demonstrating the seamless integration of hand tracking in Python applications.

Feel free to explore, modify, and integrate this hand tracking module into your projects!

Happy coding! 🤖🖐️
