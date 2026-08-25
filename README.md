# 🌦️ WeatherGuardNet

WeatherGuardNet is a computer vision application designed to improve object detection in videos under challenging visibility conditions.

The system enhances video frames using image processing techniques and detects objects using YOLOv8 through an interactive Streamlit interface.

---

## 🚀 Overview

Object detection can become difficult when video visibility is affected by factors such as rain, fog, glare, or low-light conditions. WeatherGuardNet addresses this by applying image enhancement techniques before running object detection.

The application allows users to upload videos, process the frames, and view detected objects with bounding boxes directly in the browser.

---

## ✨ Features

- Object detection using YOLOv8
- Video-based object detection
- Image enhancement for improved visibility
- Glare reduction and contrast enhancement
- Denoising and image sharpening
- Simple and interactive Streamlit interface
- Live processing preview
- Download processed videos
- Fast inference using a pre-trained YOLOv8 model

---

## 🏗️ Project Structure

weatherguardnet/
│
├── app.py
├── yolov8n.pt
├── requirements.txt
├── runtime.txt
└── README.md

---

## ⚙️ Installation

Install the required dependencies:

    pip install -r requirements.txt

---

## ▶️ Run the Application

    python -m streamlit run app.py

Then open in browser:

    http://localhost:8501

---

## 🧪 Usage

1. Launch the application
2. Upload a video
3. Select the required settings
4. Run the detection process
5. View detected objects with bounding boxes
6. Download the processed video

---

## 🛠️ Technologies Used

- Python
- Streamlit
- OpenCV
- NumPy
- Pillow
- YOLOv8 (Ultralytics)

---

## ⚠️ Notes

- Make sure `yolov8n.pt` is present in the project folder
- First run may take slightly longer due to model loading
- Processing speed depends on the available hardware
- The current version processes uploaded videos

---

## 🔮 Future Improvements

- Add automatic weather condition detection
- Use condition-specific image enhancement
- Support real-time webcam/video processing
- Add object tracking
- Improve detection accuracy in difficult conditions
- Add detection performance evaluation
- Deploy as a cloud-based application
