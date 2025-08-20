# CodeAlpha-topic-4
YOLOv8-based object detection + tracking on video with summary table 
# 🚦 Object Detection and Tracking with YOLOv8  
**CodeAlpha AI Internship – Task 4**

This project implements **Object Detection and Tracking** using [YOLOv8](https://github.com/ultralytics/ultralytics) on video input.  
It detects objects frame-by-frame, assigns them unique IDs, and saves an annotated video.  
Additionally, it generates a **tabular summary of detected objects** with counts (CSV format).

---

## 📌 **Problem Statement**
Develop a system that can detect and track objects in real-time using computer vision:
- Accept video as input.
- Detect multiple objects per frame using a pre-trained YOLO model.
- Track them across frames using ByteTrack.
- Save annotated video with bounding boxes + IDs.
- Provide a summary table of detected objects.

---

## 🚀 **Features**
- Uses **YOLOv8n** (lightweight, fast model).  
- Detects 80 COCO classes (person, car, bus, dog, etc.).  
- **Tracking with IDs** (ByteTrack).  
- Saves processed video (`output.mp4`).  
- Generates detection summary (`detections.csv`).  

---

## 🛠️ **Requirements**
Install dependencies:
```bash
pip install -r requirements.txt
