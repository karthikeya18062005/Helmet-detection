# 🛡️ Helmet Detection Using YOLOv8

> A real-time AI system to detect whether motorbike riders are wearing helmets using CCTV footage and object detection.

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](#)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-red)](#)
[![OpenCV](https://img.shields.io/badge/OpenCV-RealTime-green)](#)

---

## 🚀 Project Overview

This project uses **YOLOv8** to detect **helmets on riders** in real-time or from video footage. It's a foundational module in a larger smart traffic violation system aimed at promoting road safety using AI.

---

##Output:-
<img width="960" height="924" alt="image" src="https://github.com/user-attachments/assets/62e5ccec-f3e6-48f0-baf3-ba26c5b672dc" />
<img width="958" height="930" alt="image" src="https://github.com/user-attachments/assets/1857c927-3cca-4c6a-b874-f966aa4a5350" />


## 🎯 Features

- 🔍 Detects helmet presence on riders
- 🎥 Works with both webcam and pre-recorded CCTV videos
- 🖼️ Annotated output with bounding boxes and labels
- 📁 Easy-to-extend for multiple violations (e.g., signal jumping, no-seatbelt)

---

## 🧠 Tech Stack

| Tool         | Purpose                           |
|--------------|-----------------------------------|
| YOLOv8       | Object Detection (Helmet & Rider) |
| Python       | Core language                     |
| OpenCV       | Video I/O and processing          |
| NumPy        | Array operations                  |
| Ultralytics  | Model training & inference        |

---

## 📦 Installation

git clone https://github.com/karthikeya18062005/Helmet-detection.git
cd Helmet-detection
pip install -r requirements.txt

📹 How to Use
1. Run on Webcam:
bash
Copy
Edit
python detect.py --source 0
2. Run on Video File:
bash
Copy
Edit
python detect.py --source path/to/video.mp4
📁 Folder Structure
bash
Copy
Edit
Helmet-detection/
├── detect.py           # Main script
├── helmet_model.pt     # Trained YOLOv8 model (add yours)
├── sample_video.mp4    # Test footage
├── outputs/            # Annotated output videos
├── requirements.txt
└── README.md
🔮 Demo


📈 Future Work
Add helmet violation logging (CSV)

Integrate with license plate recognition

Build end-to-end traffic violation detection suite

Deploy on edge devices (Jetson Nano, Raspberry Pi)

🤝 Contributing
Pull requests are welcome! Let’s make road safety smarter, together.

📜 License
This project is licensed under the MIT License.
