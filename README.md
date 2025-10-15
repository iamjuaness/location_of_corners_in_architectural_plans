🏗️ Corner Localization in Architectural Blueprints

This project focuses on corner localization in architectural blueprints using Computer Vision techniques.
Accurate detection of corners is essential for automatic structural analysis, blueprint digitization, and building modeling.

🎯 Objectives

Detect and localize corners in digital architectural blueprints.

Analyze the impact of various factors such as noise, resolution, and line thickness.

Evaluate and compare classical corner detection algorithms:

Harris Corner Detector

Shi-Tomasi (Good Features to Track)

FAST (Features from Accelerated Segment Test)

⚙️ Process Description

Preprocessing:

Convert images to grayscale.

Apply noise reduction filters to improve clarity.

Edge Detection:

Use edge detectors like Canny to emphasize structural lines.

Corner Detection Algorithms:

Implement and compare Harris, Shi-Tomasi, and FAST methods.

Post-processing & Visualization:

Remove false positives.

Visualize the detected corners on the original blueprints.

🧰 Tools & Technologies

Python

OpenCV

NumPy

Matplotlib

Dataset: Digital images of architectural blueprints
