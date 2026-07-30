# Hi, I'm Shubham Petkar 👋

**Perception ML Engineer @ ERIC Robotics** — I build real-time 3D LiDAR perception for autonomous inspection robots across railway, runway, and road.

My work lives where point clouds meet production: laser profilers streaming millions of points, registration pipelines that must answer in milliseconds, and detection systems where a 2.5 mm anomaly matters.

---

## 🔭 What I work on

- **Real-time point-cloud registration** — multi-hypothesis coarse initialization (FGR / FPFH+RANSAC), GICP refinement, and degeneracy detection; ~6 mm accuracy at 263 ms per 30 m batch (12× real-time margin)
- **Change & FOD detection** — phase-correlation registration, Z-offset normalization, and DBSCAN clustering on profiler depth maps, catching runway debris down to 2.5 mm
- **Railway track geometry** — versine (mid-chord offset) measurement on a 4× laser-profiler rig with dual-rail yaw cancellation at ~0.13 mm/profile encoder resolution
- **Production sensor pipelines** — multithreaded C++ acquisition (Mech-Eye SDK), encoder-triggered capture, parallel zstd compression, ROS 2 / Iceoryx / MCAP data flows

## 🛠️ Stack

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)
![Open3D](https://img.shields.io/badge/Open3D-1F77B4?style=flat)
![PCL](https://img.shields.io/badge/PCL-2C3E50?style=flat)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Core:** C++ · Python · Open3D · PCL · OpenCV · ROS 2 · YOLO · NumPy · laspy · Linux

## 🚧 Currently

- Driving online registration + change detection under a 500 ms/batch budget
- Evaluating TEASER++ and GPU acceleration for globally robust registration
- Going deeper on autonomy perception: SLAM, multi-sensor fusion (RTK / IMU / encoder), and learning-based detection

## 📫 Reach me

[LinkedIn](https://linkedin.com/in/shubham-p) · [petkars907@gmail.com](mailto:petkars907@gmail.com)

---

> *"Anything that can be imagined can be programmed."*
