# 🏍️ Helmet Detection System using YOLOv8

## 📌 Overview

Helmet Detection System is a computer vision-based safety monitoring application that detects motorcycle riders and identifies whether they are wearing helmets using the YOLOv8 object detection model.

The application is built with Streamlit and allows users to upload images and videos for real-time helmet compliance detection.

---

## 🎯 Problem Statement

Road accidents involving two-wheelers often result in severe injuries due to the absence of helmets. Manual monitoring of helmet compliance is time-consuming and inefficient.

This project automates helmet detection using Artificial Intelligence and Computer Vision techniques, helping traffic authorities improve road safety enforcement.

---

## ✨ Features

* Detects motorcycle riders in images and videos
* Identifies helmet and non-helmet riders
* Supports image upload and video upload
* User-friendly Streamlit web interface
* Real-time object detection using YOLOv8
* Displays processed output with bounding boxes and labels
* Fast and accurate inference

---

## 🛠️ Technologies Used

| Technology | Purpose                   |
| ---------- | ------------------------- |
| Python     | Backend Development       |
| YOLOv8     | Object Detection Model    |
| OpenCV     | Image & Video Processing  |
| Streamlit  | Web Application Interface |
| Pillow     | Image Handling            |
| NumPy      | Numerical Computation     |
| Pytube     | YouTube Video Support     |

---

## 🧠 Model Information

The project uses a custom-trained YOLOv8 model capable of detecting:

* Rider
* Helmet
* No Helmet

The model has been trained and optimized for helmet compliance detection in traffic scenarios.

---

## 📂 Project Structure

```text
Helmet_Detection
├── app.py
├── helper.py
├── settings.py
├── assets/
├── images/
├── runs/
├── requirements.txt
├── README.md
└── weights/
```

## 🚀 Installation & Setup

### Clone Repository

```bash
git clone https://github.com/PraveenaRajendiran/Helmet_Detection.git
cd Helmet_Detection
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
streamlit run app.py
```

---

## 📸 Sample Results

### Original Image

(Add Screenshot Here)

### Detection Result

(Add Screenshot Here)

---

## 📈 Future Enhancements

* Number Plate Detection
* Traffic Rule Violation Monitoring
* Live CCTV Integration
* Helmet Compliance Analytics Dashboard
* Cloud Deployment

---

## ⚠️ Note

Model weight files (`best.pt`, `last.pt`) and large video files are excluded from this repository to reduce repository size.

To run the project completely, download the trained model files separately and place them inside the `weights/` directory.

---

## 👩‍💻 Author

**Praveena R**

B.Tech Information Technology

Interested in:

* Artificial Intelligence
* Machine Learning
* Computer Vision
* Full Stack Development

GitHub:
https://github.com/PraveenaRajendiran
