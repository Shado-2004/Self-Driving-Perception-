# End-to-End Self-Driving Perception

This repository implements a complete perception pipeline for autonomous driving using deep learning and computer vision. It includes environment setup and machine learning notebooks that demonstrate how to combine object detection, traffic light classification, and semantic segmentation into a unified workflow.

## Features
- **Environment Setup**  
  Ready-to-use setup notebook with pinned versions of `numpy`, `opencv-python`, `fastai`, `ultralytics (YOLOv8)`, and other dependencies for reproducibility.
  
- **Object Detection (YOLOv8)**  
  Detects cars, traffic lights, and other road objects with pre-trained YOLO models.

- **Traffic Light Classification**  
  Classifies cropped traffic lights into red, yellow, or green using HSV color space analysis.

- **Semantic Segmentation (SegFormer)**  
  Uses NVIDIA’s SegFormer model (fine-tuned on Cityscapes) to segment drivable areas such as roads and parking spaces.

- **Visualization**  
  Overlays bounding boxes, traffic light labels, and drivable masks onto the original images for clear perception results.

## Tech Stack
- Python, Jupyter Notebooks  
- FastAI, PyTorch, NumPy, OpenCV, Matplotlib  
- Ultralytics YOLOv8  
- HuggingFace Transformers (SegFormer)  

## Example Applications
- Autonomous driving perception research  
- Real-time traffic analysis  
- Road segmentation and traffic-light-aware navigation
