YOLOv8 Object Detection – Bus & People

Object detection using YOLOv8 and Python.

This project demonstrates detecting buses and people in an image using a pre-trained YOLOv8 model with the Ultralytics framework. The implementation is done in Google Colab.

Tech Stack

Python

YOLOv8 (Ultralytics)

OpenCV

Google Colab

Files
detect.py
requirements.txt
results.jpg
README.md

Run the Project
pip install -r requirements.txt
python detect.py

Detection Code
from ultralytics import YOLO

model = YOLO("yolov8n.pt")
model("https://ultralytics.com/images/bus.jpg", save=True)

Output

Detects bus and people

Saves output with bounding boxes as results.jpg

Reference

https://docs.ultralytics.com

Author

Academic & portfolio project using YOLOv8
