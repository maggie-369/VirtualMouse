## Virtual Mouse Control Using Hand Gestures
# Overview

This Python application allows you to control your computer's mouse cursor and perform clicks/scrolls using hand gestures captured by your webcam. It uses MediaPipe for hand tracking and PyAutoGUI for mouse control.

# Features

Cursor Movement: Move your index finger to control the mouse cursor
Left Click: Pinch thumb and index finger together
Right Click: Pinch thumb and middle finger together
Scrolling: Extend only index and middle fingers (close together) and move vertically
Requirements

Python 3.6+
OpenCV (pip install opencv-python)
MediaPipe (pip install mediapipe)
PyAutoGUI (pip install pyautogui)
NumPy (pip install numpy)
Installation

Clone or download this repository
Install the required packages using pip:
text
pip install opencv-python mediapipe pyautogui numpy
Run the script:
text
python virtual_mouse.py
Usage

Position your hand in front of your webcam
Move your index finger to control the cursor
Gestures:
Left Click: Bring thumb and index finger close together
Right Click: Bring thumb and middle finger close together
Scroll: Extend only index and middle fingers (close together) and move up/down
Press 'q' to quit the application

## Notes

Make sure your hand is well-lit and visible to the camera
The system works best with a plain background
You may need to adjust the threshold constants in the code for better performance with your hand size
Troubleshooting

If the cursor jumps around, try moving your hand more slowly
If clicks aren't registering, try decreasing the PINCH_THRESHOLD value
If scrolling is too sensitive, adjust the SCROLL_SPEED or SCROLL_DEADZONE values

## License

This project is open source and available for free use.