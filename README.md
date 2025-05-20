# Emergency Vehicle Detection using YOLOv5

This repository contains the implementation for a real-time emergency vehicle detection system developed as part of a university research project. The model is based on YOLOv5s and is optimized for edge deployment on devices like Raspberry Pi 4.

## 📂 Project Structure
- `data.yaml`: Dataset configuration file
- `train.py`: Training script (YOLOv5 training logic)
- `runs/`: Output directory with trained weights and results
- `images/`: Sample images from dataset

## ⚙️ Model Details
- Model used: YOLOv5s
- Image size: 416 × 416
- Epochs: 50
- Batch size: 16
- Optimizer: SGD

## 🖼️ Dataset
The dataset consists of 1000 manually captured and annotated images simulating real-world traffic conditions using toy vehicles in a miniature environment. It includes:
- Emergency vehicles: Ambulance, fire truck, police car
- Non-emergency vehicles

## 🚀 Edge Deployment (Future Work)
The system is designed for deployment on Raspberry Pi 4 using a Pi Camera module to detect emergency vehicles and communicate with smart traffic lights for real-time prioritization.

## 👩‍💻 Authors
- Raneem Alrumaihi  
- Maha Alharbi   
