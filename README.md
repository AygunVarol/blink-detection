# Blink Detection with Eye Aspect Ratio (EAR) and SQLite Logging
This repository detects blinks and counts them in the upper left of the video frame.

This is a example of a frame
![resim](https://github.com/AygunVarol/Blink/assets/55206464/1a4f5c0c-5cd5-4191-bbff-ee361387485b)

This project uses OpenCV and MediaPipe to detect blinks by calculating the Eye Aspect Ratio (EAR). Detected blinks are logged with timestamps into a SQLite database.

## Requirements

Make sure you have Python installed (preferably version 3.7 or above). You will need the following Python libraries:

- OpenCV
- NumPy
- SciPy
- MediaPipe
- SQLite3 (standard library, no need to install)

## Installation

You can install the required libraries using pip. Simply run:

```bash
pip install opencv-python numpy scipy mediapipe
