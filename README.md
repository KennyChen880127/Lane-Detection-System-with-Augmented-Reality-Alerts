<div align="center">
<h1>
<b>
Lane Detection System with Augmented Reality Alerts
</b>
</h1>
</div>

This project utilizes OpenCV to Develop[Lane departure Warning System](https://en.wikipedia.org/wiki/Lane_departure_warning_system) and [Augmented Reality](https://en.wikipedia.org/wiki/Augmented_reality) warning. Initially, it extracts three common road colors (red, yellow, white) using OpenCV's HSV range setting. After optimizing the image through morphological operations to enhance edge contours, it draws a Region of Interest (ROI) to reduce false positives. Subsequently, Hough Transform is employed to recognize and draw road lines. The project evaluates whether the centroid of the contours exceeds a predefined safety threshold. If it does, the system triggers a warning by cropping a PNG format image and displaying it prominently in a fixed location.

## OpenCV
[OpenCV](https://opencv.org/) OpenCV, or Open Source Computer Vision Library, is an open-source computer vision and machine learning software library. It provides a comprehensive set of tools and functions designed to facilitate real-time computer vision applications. OpenCV is widely used in various domains, including image and video processing, object detection and recognition, machine learning, and robotics.

### Results
| Detect a red line. | Detect a yellow line. | Detect a white line. |
| ------------- | ------------- | ------------- |
| ![image](https://github.com/KennyChen880127/Lane-Detection-System-with-AR-Alerts/blob/main/example_1.png) | ![image](https://github.com/KennyChen880127/Lane-Detection-System-with-AR-Alerts/blob/main/example_2.png) | ![image](https://github.com/KennyChen880127/Lane-Detection-System-with-AR-Alerts/blob/main/example_3.png) |
