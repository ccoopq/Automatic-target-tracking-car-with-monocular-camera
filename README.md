# Automatic-target-tracking-car-with-monocular-camera

## Project Overview
The project aimed to design a real-time automatic target tracking vehicle equipped with a monocular camera, focusing on cost-effective and efficient autonomous navigation and surveillance.

This is a final project of ME5400A.

## Technology and Methodology
Employed YOLOv5 for object detection due to its high efficiency and accuracy in real-time processing.

Used TrackerKCF for continuous object tracking, optimizing performance on the NVIDIA Jetson Orin Nano, a resource-limited edge computing device.

Developed a vehicle control algorithm to translate visual data into actionable navigation commands, adjusting speed and steering based on the object’s location and distance.

## Experimental Setup and Validation
Tested the system's tracking capabilities in various scenarios, including straight-line and curved paths.

Introduced a "searching mode" to re-engage tracking after losing the target, proving the system’s robustness and effectiveness.

(For more details, see the report under this project.)
