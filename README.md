# Autonomous UAV Face Recognition System

Real-time UAV-based face recognition platform using embedded AI on NVIDIA Jetson Orin Nano.

---

# Overview

This project implements a fully onboard real-time face recognition system deployed on a UAV platform for indoor and outdoor environments.

The system integrates:
- SCRFD face detection
- ArcFace face recognition
- Real-time target tracking
- Embedded GPU inference
- Live GUI visualization
- Privacy-aware face blurring
- Digital zoom
- UAV hardware integration

All AI inference runs directly onboard the UAV without cloud dependency.

---

# System Architecture

![System Architecture](images/system_architecture.png)

---

# Hardware Platform

- NVIDIA Jetson Orin Nano
- Holybro X500 V2 UAV
- Pixhawk 6C
- ELP 16MP USB Camera
- LiPo Battery Power System

---

# AI Pipeline

1. Face Detection using SCRFD
2. Face Tracking
3. Face Alignment
4. ArcFace Embedding Extraction
5. Cosine Similarity Matching

---

# Features

- Real-time onboard inference
- 35-50 FPS embedded performance
- Live GUI visualization
- Face enrollment system
- Embedded GPU acceleration
- Privacy-aware face blurring
- Digital zoom support

---

# Results

- Achieved 35-50 FPS on Jetson Orin Nano
- Successful onboard UAV deployment
- Stable real-time face recognition during flight
- Fully onboard processing without cloud services

---

# Technologies Used

## AI & Vision
- Python
- OpenCV
- PyTorch
- SCRFD
- ArcFace

## Embedded & Systems
- Jetson Orin Nano
- CUDA
- TensorRT
- Linux

## UAV Platform
- Pixhawk
- MAVLink
- QGroundControl

---

# Future Work

- Autonomous navigation
- MAVLink-based AI flight control
- Multi-target tracking
- GPS-denied navigation
- SLAM integration

---

# Documentation

Full project report available in:

```text
docs/
```

---

# Authors

Hasan Al Hussein  
Khalifa University
