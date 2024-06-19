# Social-Distance-Detector

This project uses YOLO (You Only Look Once) for real-time detection and monitoring of social distancing in video feeds. The program identifies people in the frame and calculates the distance between them, flagging any cases where the distance is below a specified threshold.

Features
Real-Time Detection: Utilizes YOLOv3 to detect individuals in video streams.
Distance Calculation: Measures the distance between detected individuals.
Violation Highlighting: Marks individuals who violate the minimum distance in red.
Live Video Feed: Processes live video from a webcam or a pre-recorded video file.
Logging: Optionally records instances of social distancing violations.
How It Works
Initialization: Loads the YOLO model and sets detection parameters.
Detection: Processes each video frame to detect people.
Distance Monitoring: Computes distances between detected individuals and flags violations.
Visualization: Draws bounding boxes around detected individuals and highlights those violating social distancing.

# Requirements
1. Python 3.x
2. OpenCV
3. NumPy
4. SciPy
5. imutils

# Download Links for YOLO and COCO Files

# Download yolov3.cfg
[YOLOv3 Configuration File (yolov3.cfg)](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)

# Download yolov3.weights
COCO Class Labels
[DOWNLOAD yolov3.weights](https://github.com/AlexeyAB/darknet/releases/download/darknet_yolo_v3_optimal/yolov3.weights)

# Download coco.names
Instructions to Download
[Download yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/data/coco.names)

# Visit the link.
Click on the "Raw" button to view the raw text.
Right-click and select "Save as..." to save it as yolov3.cfg.
Download yolov3.weights
