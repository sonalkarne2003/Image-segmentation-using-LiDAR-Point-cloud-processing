# 🌐 Image Segmentation using LiDAR Point Cloud Processing

This project implements semantic segmentation by integrating **LiDAR point cloud data** with deep learning models to enhance scene understanding. It leverages **PointNet+** for 3D point cloud feature extraction and **SqueezeNet** for lightweight semantic segmentation in 2D image space.

---

## 🚀 Objective

To improve object detection and scene segmentation in complex environments by combining 3D spatial data from LiDAR with image-based processing techniques. This fusion enables more accurate and depth-aware perception, especially for applications like autonomous driving and robotics.

---

## 🔧 Features

- 🟢 LiDAR point cloud preprocessing and filtering  
- 🔄 3D-to-2D projection for image and point cloud fusion  
- 🧠 PointNet+ for extracting features from raw point clouds  
- 🔥 SqueezeNet for fast, lightweight semantic segmentation  
- 💾 Supports KITTI and custom LiDAR datasets  
- 📊 Visualization of segmentation masks and 3D overlays  

---

## 📸 Sample Output

### 📍 Input Point Cloud Projection
<img width="1270" height="632" alt="LiDAR Projection" src="https://github.com/user-attachments/assets/d13980f1-791e-4c61-8abe-571c08aedb77" />

---

### 📈 Accuracy per Labelled Class
<img width="1230" height="684" alt="Class Accuracy Chart" src="https://github.com/user-attachments/assets/98de4844-231a-414f-9620-ead4c7e90d7f" />

---

### 📉 Training vs Validation Loss
<img width="1452" height="658" alt="Training Loss Graph" src="https://github.com/user-attachments/assets/ce6d7763-ad2b-4974-89eb-6d376444d92e" />

---

### 🧪 Segmentation Results with Labels
<img width="1185" height="632" alt="Segmentation Output" src="https://github.com/user-attachments/assets/57b0c1cc-22f9-4631-9ab0-801ed293b280" />

---

## 🧰 Requirements

- MATLAB R2023a or later  
- Computer Vision Toolbox  
- Deep Learning Toolbox  
- Lidar Toolbox  
- Image Processing Toolbox
