# Face Expression Detection using YOLOv5
IEEE Silchar Subsection Student Winter Internship Program - 2025 (IS3IP-2025)  
Mentor: Dr. Debbrota Paul Chowdhury, NIT Silchar  

## Introduction
The Face Expression Detection Model is a real-time computer vision and machine learning application designed to classify facial expressions such as happiness, sadness, anger, surprise, fear, and neutrality.  
It combines facial landmark detection with deep learning neural networks to achieve high accuracy and robustness.

---

## Use in Automobiles
Integration into automobiles can enhance safety, comfort, and driving experience:

- Driver Monitoring Systems: Detect fatigue, stress, or distraction and trigger alerts or engage safety features.  
- Emotion-Adaptive Interfaces: Adjust in-car settings (music, lighting, temperature) based on driver mood.  
- Emergency Response Assistance: Recognize distress expressions and alert emergency services.

---

## Previous Work
- Collision Avoidance Systems (radar, LiDAR, cameras)  
- Lane Departure Warning Systems  
- Driver Fatigue Detection (eye movement, head nodding, gaze tracking)  
- Adaptive Cruise Control  
- Blind Spot Monitoring  
- Emergency Braking Systems  

---

## Our Model
In the last decade, deep learning has become far more accessible.  
Using YOLOv5, even beginners can train custom object detection models in a few lines of Python code.

---

## What is YOLOv5?
YOLO (You Only Look Once) is a family of single-stage deep learning object detectors known for real-time accuracy.  
YOLOv5 is implemented in Python using PyTorch by Ultralytics.

### YOLOv5 Model Variants:
- YOLOv5n (Nano) – smallest, fastest; for IoT and edge devices  
- YOLOv5s (Small) – CPU-friendly  
- YOLOv5m (Medium) – balance between speed and accuracy  
- YOLOv5l (Large) – best for detecting small objects  
- YOLOv5x (Extra Large) – highest accuracy, largest size  

---

## Installation Requirements
```bash
# Clone YOLOv5 repository
git clone https://github.com/ultralytics/yolov5.git
cd yolov5

# Install dependencies
pip install -r requirements.txt
