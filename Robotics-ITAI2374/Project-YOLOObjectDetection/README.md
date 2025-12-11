# License Plate Detector – YOLOv8
**Course:** ITAI-1378 – Computer Vision & Artificial Intelligence  
**Student:** SM Tawhid  

---

## Project Overview
This project implements an automated license plate detection system using a YOLOv8 object detection model.  
The model identifies license plates from vehicle images by drawing bounding boxes and evaluating performance using standard object detection metrics.

This approach is useful for parking systems, toll booths, traffic enforcement, and other real-time vehicle monitoring applications.

---

## Problem Statement
Manual license plate identification is slow and inconsistent.  
An automated tool is needed to detect plates quickly and reliably across different lighting and environments.

---

## Solution Approach
- **Model:** YOLOv8 (Ultralytics)
- **Framework:** PyTorch  
- **Technique:** Object Detection  
- **Training Environment:** Google Colab  
- **Why YOLOv8:** Fast, accurate, lightweight, easy to fine-tune

---

## Dataset
- **Source:** Roboflow Universe  
- **Dataset:** License Plate Recognition  
- **Images:** 10,125  
- **Class:** `license_plate`  
- **Link:** https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e

Dataset imported via Roboflow API for training.

---

## Metrics & Targets
| Metric | Goal |
|--------|------|
| **mAP50** | ≥ 0.85 |
| **Precision** | > 0.90 |
| **Recall** | > 0.85 |
| **Speed** | > 10 FPS (Colab GPU) |

---

## Technologies Used
- Python  
- YOLOv8 (Ultralytics)  
- PyTorch  
- OpenCV  
- Roboflow
