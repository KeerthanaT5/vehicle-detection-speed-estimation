# Vehicle Detection & Speed Estimation using YOLOv8

## 📌 Project Overview
This project detects vehicles from traffic videos and estimates their speed using YOLOv8 and OpenCV.

The system performs:
- Vehicle detection using a pre-trained YOLOv8 model
- Object tracking across video frames
- Speed calculation using pixel distance and frame rate
- CSV report generation for detected vehicle speeds

---

## 🧠 Methodology
1. Load traffic video
2. Detect vehicles using YOLOv8
3. Track vehicles across frames
4. Define virtual reference lines
5. Measure time taken to cross lines
6. Calculate vehicle speed
7. Display and store results

---

## 🛠️ Technologies Used
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- Pandas

---

## 📂 Project Structure
vehicle-detection-speed-estimation/
│
├── speed_estimate.ipynb
├── tracker.py
├── requirements.txt
├── methodology_flowchart.jpg
├── output_speed_estimation.jpg
├── performance_metrics.jpg
└── README.md

---

## ▶️ How to Run

1. Install required libraries:
   pip install -r requirements.txt

2. Open the notebook:
   speed_estimate.ipynb

3. Provide a traffic video as input.

4. Run all cells to perform:
   - Vehicle detection
   - Tracking
   - Speed estimation

---

## 📊 Results
- Real-time vehicle detection
- Speed estimation displayed on video frames
- Output video with annotations
- CSV file containing detected speeds
  
## 📊 Methodology Flowchart
![Methodology](methodology_flowchart.jpg)

*Figure 1: Proposed workflow for vehicle detection, tracking, and speed estimation using YOLOv8 and OpenCV.*


## 🚗 Output Speed Estimation
![Output](output_speed_estimation.jpg)

*Figure 2: Sample output showing vehicle detection and speed estimation.*

## 📈 Performance Metrics
![Performance](performance_metrics.jpg)

*Figure 3: Performance metrics comparing predicted and actual speeds.*

---

## ⚡ Model Details
The model uses a pre-trained YOLOv8 model trained on the COCO dataset and performs real-time inference without additional training.

---

## 📹 Dataset / Input Video
The system works with any traffic surveillance video having a fixed camera view and clear road visibility.

For testing and demonstration, a publicly available traffic video was used.  
However, users can provide their own traffic videos as input without any restriction.

A stable camera angle helps improve tracking accuracy and speed estimation.

---

## 🚀 Future Improvements
- Real-world camera calibration
- Improved speed accuracy
- Multi-lane vehicle analysis
- Deployment with CCTV systems

---

## 👩‍💻 Author
Mini Project – 3rd Year BTech (Information Technology)
Gokaraju Lailavathi Engineering College

---

## 📌 Note

This project uses a pre-trained YOLOv8 model trained on the COCO dataset and performs inference only.  
No custom training was performed.

---
