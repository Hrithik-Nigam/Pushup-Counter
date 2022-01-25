# Pushup-Counter
This is the code for creating a basic pushup counter using OpenCV library and python. The landmarks are extracted using mediapipe library.
The code toggles on the default device camera to start capturing. As soon as the camera turns on, the mediapipe starts observing the landmakrs of the person.
The landmarks under consideration for this exercise are elbows, joints and wrists (both left and right).
The angles between an elbows, joints and wrists, is calculated and their mean determines whether the push-up is in UP-state or DOWN-state.
