# GCVM

Gesture Controlled Virtual Mouse

Gesture Controlled Virtual Mouse makes human computer interaction simple by making use of Hand Gestures. The computer requires almost no direct contact. All i/o operations can be virtually controlled by using static and dynamic hand gestures. This project makes use of the state-of-art Machine Learning and Computer Vision algorithms to recognize hand gestures, which works smoothly without any additional hardware requirements. It leverages models such as CNN implemented by MediaPipe running on top of pybind11. It consists of two modules: One which works direct on hands by making use of MediaPipe Hand detection, and other which makes use of Gloves of any uniform color. Currently it works on Windows platform.

procedure: 

*step1: conda create --name gest python=3.8.5
*step2: conda activate gest
*step3: pip install -r requirements.txt
*step4: Run Gesture_Controller.py
