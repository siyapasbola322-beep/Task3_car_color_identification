# Task 3: Car Colour Detection, Car Counting, and People Detection (YOLOv5 + GUI)

## 📌 Objective
The objective of this task is to build a complete system that:
- Detects **cars and people** in traffic images using YOLOv5
- Identifies the **color of each car**
- **Draws bounding boxes** around cars in the detected color
- **Counts** the total number of cars and people
- Displays the result using a **Tkinter GUI**

---

## 🚦 Features

- Object Detection using **YOLOv5**
- Car Color classification using **average color analysis**
- Real-time GUI using **Tkinter**
- Displays total **car and people count**
- Bounding boxes drawn in **actual car colors**

---

## 🧠 Technologies Used

- **YOLOv5** (PyTorch-based object detection)
- **OpenCV** for image processing & color detection
- **Tkinter** for GUI interface
- **Matplotlib/Numpy** for color calculation

---

## 📂 Folder Structure
---

## ▶️ How to Run

### 1. Clone YOLOv5 and install dependencies
```bash
git clone https://github.com/ultralytics/yolov5.git
cd yolov5
pip install -r requirements.txt
