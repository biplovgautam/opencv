# Getting Started – OpenCV Projects Collection

This repository contains practical mini-projects using OpenCV to explore core computer vision techniques.

---

## ✅ Step 1: Panorama from 3 Images

- Loaded images: `1.jpeg`, `2.jpeg`, `3.jpeg`  
- Created panorama using `cv2.Stitcher_create()`  
- Output saved as `stitchedpanorama.jpeg`

### 🖼️ Output:  
![stitchedpanorama](stitchedpanorama.jpeg)

---

## ✅ Step 2: HDR Imaging

- Loaded multiple exposure images  
- Created HDR image using OpenCV HDR algorithms  
- Output saved as `hdr.png`

### 🖼️ Output:  
![hdr](hdr.png)

---

## ✅ Step 3: Real-Time Face Detection

- Used pre-trained SSD ResNet-10 model for face detection  
- Captured video from webcam (`/dev/video2`)  
- Detected faces with bounding boxes and confidence scores  
- Displayed detection results live in window

### 🖼️ Output:  
![face_detection](face_detection_screenshot.png)

---

## ✅ Step 4: Object Tracking

- Explored multiple OpenCV tracker algorithms (e.g., CSRT, KCF, MOSSE, etc.)  
- Initialized tracker with bounding box and tracked object across video frames  
- Visualized tracking results and saved output video

### 🖼️ Output:  
![object_tracking](object_tracking_screenshot.png)

---

## ✅ Step 5: Deep Learning Object Detection

- Utilized TensorFlow-based SSD MobileNet v2 model  
- Detected multiple object classes (people, cars, bicycles, etc.)  
- Applied confidence threshold to filter detections  
- Visualized bounding boxes with class labels

### 🖼️ Output:  
![object_detection](object_detection.png)

---

## 🛠️ Upcoming Steps

- Keypoint visualization  
- Perspective transforms

---
