# 🚗 Vehicle Counting System

This project implements a **real-time vehicle counting system** using **Computer Vision and Deep Learning** techniques. It detects, tracks, and counts vehicles as they cross a predefined region in a video stream.

---

## 🔍 Features

- Real-time vehicle detection using **YOLO**
- Object tracking with **SORT (Simple Online Realtime Tracking)**
- Accurate vehicle counting using a **region-based mask**
- Works on video files or live camera feed

---

## 🧠 Tech Stack

- **Python**
- **YOLO (Object Detection)**
- **SORT Algorithm (Tracking)**
- **OpenCV**
- **NumPy**

---

## 📁 Project Files

- `car.py` – Main script for detection, tracking, and counting  
- `sort.py` – SORT tracking algorithm implementation  
- `graphics.png` – UI/visual overlay assets  
- `mask.png` – Region mask for vehicle counting  

---


```bash
python car.py
