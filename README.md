# Automatic-target-tracking-car-with-monocular-camera

### Overview
The project aimed to design a real-time automatic target tracking vehicle equipped with a monocular camera, focusing on cost-effective and efficient autonomous navigation and surveillance.

This is a final project of ME5400A.

### Methodology
Employed YOLOv5 for object detection method and TrackerKCF for continuous object tracking.

Realtime performance on the NVIDIA Jetson Orin Nano, a resource-limited edge computing device.

Developed a vehicle control algorithm to translate visual data into actionable navigation commands with PWM and adjusted speed and steering based on the object’s location and distance.

### Experiments
Tested the system's tracking capabilities in various scenarios, including straight-line and curved paths.

Introduced a "searching mode" to re-engage tracking after losing the target.

(For more details, see the report under this project.)

## Hardware
![car](https://github.com/user-attachments/assets/5dd08c70-167f-402f-9a50-68895051c3d4)


## Testing
![static](https://github.com/user-attachments/assets/9f29a970-38c5-4c96-bf0c-3855edac18e8)
![t1](https://github.com/user-attachments/assets/5acb21f2-b79b-4ba4-8ff8-4d0de0e74729)
![t2](https://github.com/user-attachments/assets/29d69c87-1430-420f-a196-29686d2a69e6)
![search](https://github.com/user-attachments/assets/da403e56-aabc-48fb-b94c-22533443555a)
