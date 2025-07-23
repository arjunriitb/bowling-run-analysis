# 🏏 Bowling Run Speed Analysis using YOLOv8 and MediaPipe

This project analyzes a cricket bowler’s run-up by applying computer vision techniques to track motion and compute the **speed profile** over time. It uses **YOLOv8** for detecting the bowler and **MediaPipe Pose** for extracting pose landmarks. Real-world scaling is done using fixed reference objects (like tripod and stump), enabling accurate speed estimation.

---

## 📌 Key Features

- 🎯 Detects bowler using YOLOv8 object detection
- 🧍‍♂️ Extracts body landmarks using MediaPipe Pose
- 📏 Calibrates pixel distance to real-world units using tripod and stump
- 📈 Computes frame-by-frame displacement and instantaneous speed
- 📊 Generates a smooth **speed vs time profile** of the bowler
- 📉 Visualizes motion trajectories and speed plots

---

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- Ultralytics YOLOv8
- NumPy, SciPy, Matplotlib, Pandas

---


