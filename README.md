# Cattle-Detection-From-Drone-Thermal-Data
Improve yolov7 architecture to detect cattle from drone captured thermal data. 

## Challenges
- Drone captured cattles are very small to detect (small target).
- cattles are easily occluded with each other and background (occlusions).

## Technical Contributions
- Applied transfer learning to yolov7 detector with custom cattle dataset.
- Combined yolov7 architecture and space-to-depth (SPD) and non-stride convolution module to detect
smaller and blurry cattle.
- Designed a small target layer to further resolve small cattle detection problem.

