# Weed Detection using YOLOv8 🌱🚜

This project detects weeds in farm/field videos using a trained YOLOv8 object detection model.

## Demo 🎥
✅ Here is a short demo of the model running on a video:

[Download Demo Video](demo.mp4)

## What I Built
- Trained a YOLOv8 detection model
- Tested it on new videos
- Generated detection videos with bounding boxes

## Tools Used
- Python
- Google Colab
- Ultralytics YOLOv8
- Roboflow (dataset)

## How to Run
1. Install dependencies:
```bash
pip install ultralytics
from ultralytics import YOLO

model = YOLO("best_weed_model.pt")
model.predict(source="demo.mp4", save=True, conf=0.05)

