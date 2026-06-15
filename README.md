# Computer Vision & Image Processing Projects

This repository contains a collection of Computer Vision and Image Processing projects implemented using classical image processing techniques in Python and OpenCV.

The projects focus on:

- Medical image preprocessing
- Brain tumor detection without deep learning
- Feature extraction and matching
- Image alignment and homography
- Cartoonification and sketch effects
- Face blurring in images and videos
- Template matching and image similarity
- Real-time webcam processing

---

# Repository Overview

This repository includes multiple practical projects related to image processing and computer vision using traditional algorithms instead of machine learning or deep learning methods.

---

# Brain Tumor Detection (Without Deep Learning)

One of the main projects in this repository focuses on detecting brain tumors in MRI images using classical image processing methods only.

Techniques used include:

- Image filtering
- Thresholding
- Edge detection
- Morphological operations
- Noise reduction
- Contrast enhancement

The goal is to locate suspicious tumor regions in MRI scans through preprocessing and segmentation techniques.

---

# Pencil Sketch Effect

The `sketch_image` function converts a normal image into a pencil sketch using several image processing steps:

1. Convert image from BGR to RGB
2. Convert image to grayscale
3. Invert grayscale image
4. Apply Gaussian Blur
5. Invert blurred image
6. Blend images using `cv2.divide`

This creates a smooth pencil sketch effect.

---

# FPS Visualization

The `visualize_fps` function overlays FPS (Frames Per Second) information onto images or video frames.

Features:
- Supports grayscale and color images
- Displays FPS dynamically
- Useful for real-time video processing

---

# Real-Time Webcam Processing

The webcam module:

- Captures live video using OpenCV
- Detects and blurs faces
- Calculates FPS in real time
- Maintains stable frame rates

---

# Video Face Blurring

The video processing pipeline:

- Loads video files frame-by-frame
- Detects faces
- Applies blur effects
- Displays FPS information
- Shows processed video output

---

# ORB Feature Detection & Matching

This project includes feature matching using:

- ORB (Oriented FAST and Rotated BRIEF)
- BFMatcher (Brute Force Matcher)

Main steps:
- Detect key points
- Extract descriptors
- Match descriptors between images
- Sort matches by similarity

Applications:
- Object recognition
- Image matching
- Image registration
- Alignment

---

# Image Alignment Using Homography

Using matched key points, the project aligns images captured from different perspectives.

Methods used:
- `cv2.findHomography`
- `cv2.warpPerspective`

Applications:
- Perspective correction
- Panorama stitching
- Image registration

---

# Cartoonify Filter

The `cartoonify` function transforms images into cartoon-like artwork.

Techniques:
- Grayscale conversion
- Median blur
- Adaptive thresholding
- Bilateral filtering
- Edge masking

The result preserves edges while smoothing colors for a stylized appearance.

---

# Template Matching & Image Similarity

The repository also explores:

- Histogram analysis
- Template matching
- Image similarity
- Multi-angle image comparison

The goal is to compare images with similar content captured under different conditions or viewpoints.

---

# Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

---

# Applications

These projects are useful for:

- Medical image preprocessing
- Educational computer vision demonstrations
- Real-time video processing
- Feature extraction research
- Image enhancement experiments
