# Pushup-Counter
This is the code for creating a basic pushup counter using OpenCV library and python. The landmarks are extracted using mediapipe library.
The code toggles on the default device camera to start capturing. As soon as the camera turns on, the mediapipe starts observing the landmakrs of the person.
The landmarks under consideration for this exercise are elbows, joints and wrists (both left and right).
The angles between an elbows, joints and wrists, is calculated and their mean determines whether the push-up is in UP-state or DOWN-state.
<img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.googblogs.com%2Ftag%2Fmachine-perception%2Fpage%2F2%2F&psig=AOvVaw27l4ZnzsKu0EgEerSlidiA&ust=1643169703126000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCJCC7rqCzPUCFQAAAAAdAAAAABAD">
