# Computer Vision-Based Eye Tracking with Head-Movement Compensation

A standard-camera eye-tracking system focused on improving gaze estimation under head movement.

The project combines iris tracking, head-pose estimation, personalized calibration, and regression-based head-motion compensation to improve the robustness of camera-based gaze estimation.

## Research Objective

Conventional camera-based gaze estimation can be affected by changes in head position and orientation.

This project focuses on estimating and compensating for head-motion-related gaze errors while comparing raw and compensated gaze outputs under different tracking conditions.

## Main Components

* Standard-camera eye and iris tracking
* Head-pose estimation using pitch, yaw, and roll
* Personalized center calibration
* Head-movement calibration and compensation
* Blink and invalid-frame detection
* Frame-level tracking quality assessment
* Raw vs. compensated gaze analysis
* Optional 9-point screen mapping
* Fixation and saccade-related event classification
* Circular target-tracking evaluation
* Experimental CSV data recording

## Analysis Outputs

The system supports quantitative and visual evaluation of gaze behavior and compensation performance, including:

* Raw vs. compensated gaze comparisons
* Gaze plots
* Heatmaps
* Scanpaths
* Eye-event counts
* Spatial tracking error
* Target hit rate
* Approximate tracking lag
* Compensation-quality summaries

## Technologies

* Python
* OpenCV
* MediaPipe
* NumPy
* Computer Vision
* Head-Pose Estimation
* Regression-Based Gaze Compensation
* Real-Time Video Processing

## Research Status

This is an ongoing independent academic research project.

Final experiments and analyses are currently being completed to evaluate the effectiveness of head-movement compensation, with the project being prepared for manuscript development.

## Source Code Availability

The complete source code, calibration implementation, experimental data, and research models are not publicly distributed at this time.

This repository is intended to provide an academic and technical overview of the research project.

© 2026 Mohammadreza Akhbari. All rights reserved.
