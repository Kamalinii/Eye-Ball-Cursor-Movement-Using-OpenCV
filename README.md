Eye-Ball Cursor Movement Using OpenCV

Human-Computer Interaction via Eye Tracking

This project enables controlling the computer cursor using only eye movements—no mouse or keyboard required. Designed especially for users with physical disabilities or mobility impairments, it provides a hands-free way to interact with the computer 
GitHub
.

Features:

Real-time detection of pupil position using OpenCV.

Cursor movement mapped based on the detected center of the pupil.

Fully software-based: no special hardware required—works with a standard webcam.

Empowers individuals without hand mobility for independent computer usage.

Repository Structure

-EyeBallCursorMovement.py — Main Python script that implements eye tracking and cursor control.

-gaze_tracking/ — Likely contains modules or utilities for eye gaze estimation.

-run.bat — Batch script for Windows users to launch the application easily.

Documentation files:

abstract eyeball.docx

EYE BALL CURSOR MOVEMENT USING OPENCV.docx

Eyeball based Cursor Movement Control final doc.docx

Prerequisites

Python (3.x recommended)

OpenCV for computer vision processing

PyAutoGUI (or similar) for cursor control

Additional dependencies may include:

numpy

Other standard modules—check included docs for specifics

Installation & Setup

Clone the repository:

git clone https://github.com/Kamalinii/Eye-Ball-Cursor-Movement-Using-OpenCV.git
cd Eye-Ball-Cursor-Movement-Using-OpenCV


Install required Python packages:

pip install opencv-python pyautogui numpy


(Add any other dependencies mentioned in the documentation.)

How to Run

On Windows: Double-click run.bat or run:

python EyeBallCursorMovement.py


On Mac/Linux: Execute:

python3 EyeBallCursorMovement.py
