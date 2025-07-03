# 🤖 Closed-Loop ADAS for a Wheeled Robot

**Incorporating Computer Vision-Driven Lane Keeping Assist (LKAS) and Collision Avoidance**

This project implements a real-time Advanced Driver Assistance System (ADAS) for a wheeled robot, using **OpenCV**, **YOLOv8**, **Model Predictive Control (MPC)**, and **Quadratic Programming (QP)**. It combines lane detection, object detection, steering control, and collision warnings to simulate self-driving behavior in a constrained environment.

## 📸 Hardware Requirements

> A working camera must be connected before running the code.

## 🧠 Features

- 🔍 **Lane Detection** using edge detection and Hough Transform
- 🧭 **MPC Steering Control** with real-time deviation correction
- 🚗 **YOLOv8-based Object Detection**
- 🛑 **Collision Detection** with distance & speed estimation
- 📐 **QP-based Optimization** for steering adjustments
- 📹 Real-time video overlay with road center, camera center, and steering direction

## Results

Some glimpse's

![Lane Detection](https://github.com/Poornima855/Closed-loop-ADAS-for-a-wheeled-robot/blob/main/Resulting_Frames.png)

![Lane Detection and Object Warning](https://github.com/Poornima855/Closed-loop-ADAS-for-a-wheeled-robot/blob/main/Realtime_ResultFrame.png)

We tested on tracks since we couldn't find white lanes which are this much clear

## 📌 Notes & Limitations

- Camera calibration is approximate – for real deployment, use proper calibration matrices.
- Depth estimation is based on monocular cues; for higher accuracy, stereo vision is recommended.
- Real-time performance may vary based on hardware (especially on Raspberry Pi).

## 🤝 Contributions

Feel free to open issues or submit pull requests if you'd like to contribute!

## 📄 How to Contact?

Reach out at 📧 poornimakatgi855@gmail.com
