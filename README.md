# Virtual Keyboard

## Description
This is a pure Python project that implements a virtual keyboard controlled by hand gestures. The project utilizes `MediaPipe` for hand tracking, `OpenCV` for video processing, `NumPy` for numerical operations, and `pynput` for simulating keyboard presses. 

## Requirements
To run this project, you'll need the following Python packages:
- `mediapipe`
- `numpy`
- `opencv-python`
- `pynput`

## Usage
1. First, ensure that the Keys.py and handTracker.py files are in the same directory as the main script.
2. Run the Keys.py script and then handTracker.py to initialize the necessary components.
3. Finally, run the virtual_keyboard.py script to start the virtual keyboard.

## How It Works
1. The virtual keyboard runs for one hand.
2. You can move the cursor using one finger.
3. You can click keys on the virtual keyboard by bringing two fingers (thumb and index finger) close together.
