# 🚦 Real-Time Video Analysis Using YOLOv9 and OpenCV

A computer vision project for **real-time object detection and video analysis** using **YOLOv9** and Python. The project processes a road-traffic video and detects multiple objects such as **persons, cars, motorcycles, buses, trucks, bicycles, traffic lights, and other objects**.

## 📌 Project Overview

This project uses the **Ultralytics YOLOv9m model** to perform object detection on video frames. The input traffic video is processed frame-by-frame, and the detected objects are displayed with bounding boxes and labels.

The notebook uses the `ultralytics` package and YOLOv9m model for detection.

## ✨ Features

* Real-time video object detection
* YOLOv9-based detection
* Frame-by-frame video processing
* Detection of vehicles and road objects
* Bounding boxes and object labels
* Processed output video generation
* Jupyter Notebook implementation

## 🛠️ Technologies Used

* **Python**
* **YOLOv9**
* **Ultralytics**
* **OpenCV**
* **NumPy**
* **Jupyter Notebook / Google Colab**

## 🎯 Objects Detected

The model can detect objects present in the traffic video, including:

* Person
* Car
* Motorcycle
* Bus
* Truck
* Bicycle
* Traffic Light
* Stop Sign
* Bench
* Backpack
* Handbag

## 📂 Project Structure

```text
Real-Time-Video-Analysis-Using-YOLOv9-and-OpenCV/
│
├── Input/
│   └── input_video.mp4
│
├── Output/
│   └── output_video.mp4
│
├── README.md
├── requirements.txt
├── Video_Analysis_Report.pdf
└── video_Analysis.ipynb
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/afrazhussaina5/Real-Time-Video-Analysis-Using-YOLOv9-and-OpenCV.git
```

Navigate to the project directory:

```bash
cd Real-Time-Video-Analysis-Using-YOLOv9-and-OpenCV
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

1. Open `video_Analysis.ipynb`.
2. Install the required dependencies.
3. Place the input video inside the `Input/` folder.
4. Run the notebook cells.
5. YOLOv9 processes the video frame-by-frame.
6. The processed video is generated in the `Output/` folder.

## 📊 Detection Results

The YOLOv9m model successfully performs object detection on the road-traffic video.

The processed frames contain detected objects with their corresponding labels and bounding boxes.

Example detections include:

```text
Persons
Cars
Motorcycles
Buses
Trucks
Traffic Lights
Bicycles
```

## 📄 Project Report

A detailed project report is available here:

**`Video_Analysis_Report.pdf`**

## 📓 Notebook

The complete implementation is available in:

**`video_Analysis.ipynb`**

## 🚀 Future Improvements

* Improve real-time processing speed
* Add object tracking
* Add vehicle counting
* Add traffic density analysis
* Add accident detection
* Deploy the system as a real-time application

## 👨‍💻 Author

**Afraz Hussain**

B.Tech – Data Science

## ⭐ Acknowledgement

This project uses the **Ultralytics YOLO** framework for object detection and video analysis.
