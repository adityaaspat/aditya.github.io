---
title: Extended Kalman Filter and Particle Filter
subtitle: State Estimation with Extended Kalman Filter and Particle Filter
image: assets/videos/EKFvsPF.gif
alt: EKF

caption:
  title: State Estimation with Extended Kalman Filter and Particle Filter
  subtitle: Sensor Estimation
  thumbnail: assets/videos/EKFvsPF.gif
---
●Developed an Extended Kalman Filter (EKF) using only IMU data for state estimation, building on previous work that combined odometry and IMU data.
●Addressed IMU drift and bias by implementing a nonlinear model for state predictions to effectively manage the noisy nature of IMU measurements.
●Extended the work by implementing a Particle Filter to compare against the EKF, using systemic resampling to reduce particle randomness and enhance state estimation.
●Demonstrated effective state estimation with accurate predictions, highlighting the robustness of the EKF's prediction model in various dynamic conditions, while also exploring the Particle Filter’s strengths in handling non-Gaussian noise distributions and nonlinear trajectories.

{:.list-inline}
- Date: August 2024
- Course: Self
- Skills: ROS2, Python, State Estimation, Extended Kalman Filter
- GitHub link: [Extended Kalman Filter and Particle Filter](https://github.com/adityaaspat/Robotics/tree/main/kalman_filter)
  
