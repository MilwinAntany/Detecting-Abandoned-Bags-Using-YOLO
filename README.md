# 🧳 Abandoned Luggage Detection Using YOLO

This project aims to enhance public transportation safety by automatically detecting unattended or abandoned luggage using real-time video feeds and the YOLO (You Only Look Once) object detection algorithm.

## 🚀 Project Overview

- **Domain:** Computer Vision, Public Safety  
- **Technology:** YOLOv4/YOLOv5  
- **Goal:** Detect and alert when luggage remains unattended for a certain period  
- **Application:** Airports, railway stations, bus terminals, public places

## 📦 Features

- Real-time object detection with YOLO  
- Tracks movement and position of bags  
- Detects abandoned luggage based on time threshold  
- Triggers alerts via audio, image capture, and email/SMS  
- Easy integration with existing CCTV systems

## 🧠 System Modules

### 1. 🎥 Video Input Module
Captures frames from live CCTV/IP cameras or USB webcams.

### 2. 🧾 Object Detection Module
Uses YOLO to identify bags and people in each frame with bounding boxes.

### 3. ⏱️ Abandonment Detection Module
Tracks bags over time. If a bag is stationary and unaccompanied beyond a set duration, it is flagged.

### 4. 🚨 Alert Generation Module
Sends audio alerts, logs images, and sends SMS/email notifications to authorities.

## 📊 System Architecture

- Object detection via YOLO  
- Real-time frame processing  
- Object tracking (location + duration)  
- Alert system: visual + audio + message/email

## 💻 Technologies Used

| Component         | Technology          |
|------------------|---------------------|
| Programming Lang | Python              |
| Object Detection | YOLO (You Only Look Once) |
| Frontend UI      | Tkinter             |
| Notifications    | Email, SMS          |
| Backend DB       | MySQL               |
| IDE              | Python IDLE         |
| OS               | Windows             |

## ⚙️ Hardware Requirements

- 2.6 GHz Dual-core Processor  
- 4 GB RAM  
- 320 GB Hard Disk  
- Webcam or IP camera

## 🧪 Testing

- ✔️ Unit Tests for login, user registration, video modules  
- ✔️ Integration testing of alert system  
- ✔️ White box and black box testing performed  
- ✔️ Real-world validation in simulated environments

## 📈 Results

- High accuracy in detecting abandoned luggage  
- Successfully reduced false alarms using time-based tracking  
- Alerts sent within seconds of detecting a threat  
- Achieved real-time processing at ~30 FPS

## 🔮 Future Enhancements

- Use of deep learning tracking (e.g., Deep SORT)  
- Integration with drone surveillance  
- Cloud-based dashboard for multi-location monitoring  
- Multi-object and threat classification (e.g., weapons, suspicious actions)

## 📎 References

- YOLOv3, YOLOv4 research papers  
- SSD (Single Shot Multibox Detector) advancements  
- Real-time surveillance datasets  
- Security protocols in smart airports

## 👨‍💻 Developed By
 
- Contact: antanymilwin@gmail.com
