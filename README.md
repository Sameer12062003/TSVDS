# TSVDS
Traffic Signal Violation Detection System

INTRODUCTION
The Traffic Signal Violation Detection System is a computer vision-based project aimed at automatically detecting traffic signal violations at intersections. The system utilizes state-of-the-art object detection and image processing techniques to monitor vehicles' behavior and identify potential violations such as red light running and improper lane usage.

FEATURES
Real-time object detection: The system employs deep learning models to detect and track vehicles, pedestrians, and other objects on the road in real-time.

Traffic signal violation detection: Using image processing techniques, the system identifies violations, such as vehicles running red lights or making illegal turns.

Video recording: The system records videos of detected violations, providing evidence for further analysis and potential law enforcement actions.

User-friendly interface: The project comes with an intuitive web-based interface that allows users to visualize the detection results and configure system parameters easily.

WORKING
Object Detection: The system uses a pre-trained deep learning model (e.g., YOLO, SSD, or Faster R-CNN) to detect vehicles and pedestrians in the video feed.

Violation Detection: By analyzing the object positions and traffic signal status, the system determines if a vehicle has violated any traffic rules, such as running a red light or making an illegal turn.

Alerts and Video Recording: When a violation is detected, the system triggers an alert and records the video segment of the violation, including the license plate for identification.

User Interface: Users can access the system through a web-based interface, where they can view live video streams, review recorded violations, and adjust system settings

ACKNOWLEDGEMENTS
We would like to acknowledge the following resources and projects that inspired or contributed to the development of this system:

  OpenCV
  TensorFlow Object Detection API
  YOLO: Real-Time Object Detection
