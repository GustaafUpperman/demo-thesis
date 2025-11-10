# 🧭 Demo Thesis  
**One-dimensional magnetic SLAM with loop closures to reduce accumulated error in smartphone PDR for indoor localization.**

---

### 🎥 Demo Video  
https://github.com/user-attachments/assets/9e5de699-908d-4d78-9c0d-1e6c278a6cac  

---

### 🧪 Description  

This video shows a **walkthrough of the Applied Physics faculty at TU Delft**, demonstrating one of the most promising results from my thesis project.  

Inside buildings, **GPS signals are unavailable**, so alternative methods are needed to determine position.  
This project leverages the **magnetic field** to achieve indoor localization using only the sensors of a smartphone (**iPhone 15**):  
- **Accelerometer**  
- **Gyroscope**  
- **Magnetometer**  

The goal was to **improve existing Pedestrian Dead Reckoning (PDR)** algorithms, which typically suffer from **accumulated drift** over time.  
By integrating the PDR trajectory (shown in **red** in the video) with a **Kalman Filter** and adding **loop closures** based on magnetic field signatures, the system significantly reduces positional error.  

The resulting SLAM algorithm (shown in **blue**) demonstrates how **magnetic-based loop closures** can effectively stabilize indoor localization performance.  

---

### 📘 Further Work  

A more detailed explanation of the algorithm, model design, and experimental setup will follow soon.
