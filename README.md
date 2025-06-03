# 🚁 Drone Detection Using YOLOv11n

This project is a real-time object detection system focused on detecting **drones** using the **YOLOv11n** model. Built and trained as part of my internship at **AIMERS Society**, this project demonstrates practical applications of computer vision in aerial surveillance and security.

## 📌 Project Overview

The goal of this project is to accurately detect drones using a lightweight and efficient deep learning model, capable of operating in real-time scenarios.

### 🔍 Key Features
- ✅ **Model Used**: YOLOv11n (Ultralytics)
- 🧠 **Training Platform**: [Ultralytics Hub](https://hub.ultralytics.com/)
- 🌐 **Dataset Source**: [Roboflow Universe](https://universe.roboflow.com)
- 🧪 **Training Epochs**: 100
- 📊 **Optimized for**: Small object detection, real-time use cases

## 📊 Model Performance

- Trained for 100 epochs
- Achieved high confidence levels and precision scores
- Evaluated with drone images in various backgrounds and lighting conditions

### 🔗 View Model:
[Ultralytics Hub Model Link](https://hub.ultralytics.com/models/fFfxfvXIkpfcoCObTjbY)

## 🧰 Tech Stack

| Tool/Framework      | Purpose                          |
|---------------------|----------------------------------|
| YOLOv11n (Ultralytics) | Object Detection Model         |
| Roboflow            | Dataset preprocessing & labeling |
| Ultralytics Hub     | Model training & deployment      |
| Python              | Scripting and integration        |

## 🚀 Installation & Usage

> _Note: Since the model is trained and hosted on Ultralytics Hub, you can deploy it directly from the platform or export it for custom use._

To run YOLOv11n locally:

```bash
# Clone Ultralytics YOLO repo (optional if not using Hub)
git clone https://github.com/ultralytics/ultralytics
cd ultralytics

# Install requirements
pip install -r requirements.txt

# Run inference (example)
yolo task=detect mode=predict model=path/to/best.pt source=path/to/video_or_image
