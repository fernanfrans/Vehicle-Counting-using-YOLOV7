# 🚗 Vehicle Counting using YOLOv7 & ByteTrack

## 📌 Overview
This project utilizes **YOLOv7** for real-time vehicle detection and **ByteTrack** for multi-object tracking. A simple algorithm is implemented for vehicle counting based on line-crossing detection.

## 🛠️ Technologies Used
- **YOLOv7** - Object detection model
- **ByteTrack** - Multi-object tracking
- **OpenCV** - Image processing
- **Python** - Main programming language

## 🏗️ Implementation
1. **Detection**: YOLOv7 identifies vehicles in each frame.
2. **Tracking**: ByteTrack assigns unique track IDs to detected vehicles.
3. **Counting**: A simple algorithm increments a counter when a vehicle crosses a predefined line.
