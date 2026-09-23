# 🔍 YOLO COCO Visual Search

An AI-powered visual search application built using **YOLO, COCO dataset concepts, OpenCV, and Streamlit**.

This project allows users to upload an image and automatically detect objects present in the image using a YOLO-based object detection pipeline. The detected objects are presented through an interactive Streamlit interface, making the system easy to use and demonstrate.

---

## 🚀 Project Overview

Visual search enables computers to understand and identify objects from images.

This project demonstrates an end-to-end **computer vision workflow** where an input image is processed by a YOLO object detection model, objects are identified, and the detection results are displayed through a user-friendly web interface.

The application is designed to provide a simple way to experiment with real-time object detection without requiring users to interact directly with complex machine-learning code.

### 🎯 Main Objective

The main objective of this project is to build an interactive visual search system capable of:

- Accepting an image as input
- Detecting objects present in the image
- Identifying detected object classes
- Displaying detection results
- Showing confidence scores
- Visualizing bounding boxes
- Providing an easy-to-use Streamlit interface

---

## ✨ Key Features

- 🖼️ Upload images through a web interface
- 🔍 AI-based object detection
- 🎯 Bounding-box visualization
- 📊 Confidence score display
- 🧠 YOLO-based computer vision pipeline
- 📦 COCO object classes
- ⚡ Fast inference
- 🌐 Interactive Streamlit interface
- 🧩 Modular project structure
- ⚙️ Configurable detection settings
- 💻 Local execution support

---

## 🧠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| YOLO | Object detection |
| COCO | Object detection classes/dataset |
| OpenCV | Image processing |
| Streamlit | Web application interface |
| NumPy | Numerical operations |
| PyTorch | Deep learning framework |
| YAML | Configuration management |

---

## 🔎 How Visual Search Works

The application follows a simple computer vision pipeline:

```text
User Uploads Image
        │
        ▼
Image Preprocessing
        │
        ▼
YOLO Object Detection
        │
        ▼
Object Classification
        │
        ▼
Bounding Boxes + Confidence Scores
        │
        ▼
Streamlit Results
