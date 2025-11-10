# Demo Thesis  
**One-dimensional magnetic SLAM with loop closures to reduce accumulated error in smartphone PDR for indoor localization.**

---

### 🎥 Demo Video  
https://github.com/user-attachments/assets/9e5de699-908d-4d78-9c0d-1e6c278a6cac  

---

### Short Description  

This video shows a walkthrough of the Applied Physics faculty at TU Delft, demonstrating one of the most promising results from my thesis project.  

Inside buildings, GPS signals are unavailable, so alternative methods are needed to determine position.  
This project leverages the magnetic field to achieve indoor localization using the accelerometer, gyroscope, and magnetometer measurements of a smartphone (iPhone 15).  

The goal was to improve existing Pedestrian Dead Reckoning (PDR) algorithms, which typically suffer from accumulated drift over time.  
By integrating the PDR trajectory (shown in red in the video) with a Kalman Filter and adding loop closures based on magnetic field signatures, the system significantly reduces positional error.  

The resulting SLAM algorithm (shown in blue) demonstrates how magnetic-based loop closures can effectively improve indoor localization performance.  

---

### Figure Explanation  

- The top-left figure shows the magnetometer measurements over time, illustrating how the magnetic field varies along the trajectory.  
- The bottom-left figure visualizes the loop closure likelihoods, indicated with weights, based on the similarity of magnetic field patterns. These weights represent how likely it is that the pedestrian is revisiting a previously visited position, which would trigger a loop closure.  
- The figure on the right shows the trajectories. The red trajectory corresponds to the standard PDR approach, while the blue trajectory represents the improved SLAM algorithm with magnetic-based loop closures.  

The detailed design and calculation of the weights will be explained soon.

---

### Report

A more detailed explanation of the algorithm, model design, and experimental setup will follow soon.


