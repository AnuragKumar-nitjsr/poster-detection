# hand_gesture_detection

This project focuses on three functionalities:
1. Hand detection.
2. Hand gesture detection.
3. Volume control using hand gestures.

## Requirements
Python 3.8 or later with dependencies listed in [requirements.txt](https://github.com/anurag-kumar-nitjsr/hand-gesture-detection/blob/main/requirements.txt). To install run:

```bash
$ git clone https://github.com/jhan15/hand_gesture_detection.git
$ cd hand_gesture_detection
$ pip install -r requirements.txt
```

## Usage

```bash
# Hand detector
$ python3 hand.py --max_hands 2

# Gesture detector
$ python3 gesture.py --mode single # currenly only single-hand gestures are supported

# Volume controller
$ python3 vol_controller.py --control continuous # continuous control
