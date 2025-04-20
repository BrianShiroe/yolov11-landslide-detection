# 🚨 Landslide Detection/Segmentation Model using YOLOv11
This repository contains object detection models trained to detect landslide using YOLOv11.

### 🧠 Model Descriptions
- **custom.pt**: A custom YOLOv11-based model trained on 5,661 labeled images (landslide).
- **yolov11n.pt**: A pre-trained YOLOv11 nano model trained on the COCO dataset. Lightweight and optimized for general-purpose object detection with high inference speed, but not tailored for disaster-specific scenarios.

## Data Balance Summary
---------------------------------------------------------
Collision
📊 Dataset Split Summary
train data: 4528
validation data: 1133
🧮 Total: 5661 images

## 🎥 Detection Demo
<p align="center">
  <img src="1-flandslide-demo.gif" width="100%"/>
</p>