## 🎯 Object Detection & Distance Measurement using Python and OpenCV

# 📖 Project Overview

This project focuses on real-time object detection and distance estimation using computer vision techniques in Python. Using a calibrated camera and known object dimensions, it calculates how far an object is from the camera in real-world units. It simulates real-life applications like robotics, autonomous vehicles, and smart surveillance systems.

# 🧠 Objectives

Detect objects (like bottles, faces, or custom items) in live video feed using OpenCV
Calibrate the camera to estimate distance accurately using object width and focal length
Display real-time bounding boxes and distance on screen
Use mathematical estimation to calculate object distance from camera
Create a flexible setup to detect any object with known dimensions

# 📌 Dataset / Inputs

This project uses real-time camera feed (webcam or external video) and:
🔍 Reference Object (e.g. bottle of known width)
🎥 Live or Static Images/Videos for detection
📐 Focal Length Calibration Images for accuracy
🛠️ Technologies Used
Technology	Purpose
Python	Core programming language
OpenCV	Image processing and object detection
NumPy	Array operations and mathematical calculations
Jupyter Notebook	Exploratory testing and prototyping
Webcam / USB Cam	Real-time image feed
Haar Cascade / Manual Detection	Pre-trained models or color filters for detection

# 📈 Key Highlights

📏 Distance Formula Used:
Distance
=
Known Width
×
Focal Length
Perceived Width in Pixels
Distance= 
Perceived Width in Pixels
Known Width×Focal Length
​🎯 Real-time Video Feed:
Detects objects live and overlays bounding boxes and distance in cm/inches
🔍 Calibration Process:
Uses an image at a known distance to calculate focal length
Achieves higher accuracy with consistent lighting and clear contours
🔄 Flexible for Any Object:
Works with bottles, books, mobile phones, or any object with known width

# 🧪 How It Works

Step 1 – Calibrate Camera:
Use distance_config.py with a known object at a known distance to calculate focal length
Step 2 – Object Detection:
Run ObjectDetection.py to detect objects using contours or Haar cascades
Step 3 – Distance Calculation:
Distance is computed based on the width of the object in pixels
Step 4 – Display:
Real-time overlay on video stream with object name and distance

# 🧩 Future Scope

Integrate YOLOv8 or SSD MobileNet for enhanced detection
Deploy to Raspberry Pi or Jetson Nano for IoT/robotics use
Build a web interface with Flask/Streamlit for visual output
Extend to multiple object distance tracking simultaneously

# 👨‍💻 Author
Manthan Jatte
Exploring Python | OpenCV | AI | Computer Vision | Data Analytics

