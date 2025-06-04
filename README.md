# SightStick: A Hybrid Obstacle Avoidance System for Visually Impaired Individuals

SightStick is an assistive technology prototype designed to enhance indoor mobility for individuals with visual impairments. This device integrates **YOLOv8 object detection** and a **fuzzy logic-based navigation system** to detect and avoid obstacles in real-time, offering voice feedback to guide users safely through their environment.

## 📌 Project Summary

- **Objective:**  
  To create a smart mobility aid using a hybrid approach for obstacle detection and avoidance by combining deep learning and fuzzy logic techniques.

- **Key Features:**
  - Real-time object detection using YOLOv8
  - Fuzzy logic algorithm for navigation decisions
  - Voice synthesis module for audio instructions
  - Compact prototype built using Raspberry Pi 4, camera, and ultrasonic sensors

## 🚀 Technologies Used

- Python
- YOLOv8 (You Only Look Once – Version 8)
- Fuzzy Logic System (Rule-Based)
- Raspberry Pi 4 Model B
- Ultrasonic Sensors
- Raspberry Pi Camera V2
- Audio Module for voice output

## 🧪 Performance Metrics

- **YOLOv8 Detection Accuracy:**
  - Mean Average Precision (mAP): 86.9%
  - Precision: 84.2%
  - Recall: 80.6%
  - F1-Score: 82.36%

- **Fuzzy Logic Navigation Accuracy:** 98.6%

- **Overall Prototype Efficiency:** 72% across 10 real-world test scenarios

## 📷 System Overview

The SightStick prototype includes:
- A black cane embedded with:
  - A camera for visual input
  - Three ultrasonic sensors for distance measurement
  - A Raspberry Pi 4B for processing
  - A speaker or earphones for voice feedback

## 🧠 How It Works

1. **Detection:** YOLOv8 identifies obstacles (e.g., chairs, tables, people).
2. **Decision:** Fuzzy logic processes distance data and determines movement action.
3. **Feedback:** Audio instructions are delivered to guide the user.

## ⚠️ Limitations

- Indoor use only (currently does not support stair navigation)
- Difficulty detecting fast-moving and low-lying obstacles
- Moderate performance in dynamic environments
- Requires calibration for varying lighting and cluttered spaces

## 👥 Team Members

- **Shiella Dimanarig**  
- **Alyssa Caritos**  
- **Gracia Torallo**  
- **Adviser:** Sir Ian P. Benitez

## 📄 License

This project is for academic and research purposes. Please contact the authors for reuse or collaboration.

---

