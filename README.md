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

## 🚀 How to Run
1. Install requirements:
   pip install ultralytics

2. Run prediction:
   from ultralytics import YOLO

model = YOLO("best_weed_model.pt")
results = model.predict(source="your_video.mp4", save=True, conf=0.05)


