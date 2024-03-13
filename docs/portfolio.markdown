---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: "Portfolio"
layout: page
permalink: /portfolio/
---

Given below are some of my completed projects. Not all of them are on GitHub (locally stored on an external "park" disk), and some of them are privately shared with the client or their organization. If you wish to learn more about these projects, however, feel free to reach out to me and I will be happy to discuss them with you.

### Tribal Village Detection In Satellite Imagery

Developed an efficient pipeline to download satellite images from a certain map polygon in Google Maps using Google Maps Platform’s Maps Static API, annotated and augmented samples on RoboFlow, and trained a YOLOv8n model to detect tribal areas over the complete region and return their latitude-longitude coordinates. Further trained a ResNet-18 classifier on a subset of manually labeled cropped detector predictions to help remove false positives.

### Age Bias Mitigation To Improve Age Estimation

Mitigated age-distribution bias in age-estimation datasets with a self-modified statistical balancing approach from a recent academic paper (no augmentations involved) to improve both the real and apparent Mean Absolute Errors (RMAE and AMAE) of the age-estimation model on the test sets by 1.12 and 1.5 respectively.

### Mirror-Assisted 3D Reconstruction Toolbox

Developed a reconstruction toolbox in MATLAB that uses a single high-speed camera with at least one mirror to act as a virtual camera to allow reconstructing insects (or any other objects) moving at extreme speeds. The MATLAB tracking application used as part of the toolbox was DLTdv8a, and Bouget’s MATLAB Calibration Toolbox was used to calibrate the actual camera and mirrors.

### Depth-Aware Human Segmentation

Setup a depth-aware human segmentation pipeline where the color and depth feeds were read in via a USB-connected Microsoft Kinect v1 and the segmentation masks were generated using Mask-RCNN (MRCNN). The extracted subjects from the live depth feed were then placed in a custom background whose depth was previously known, which could then be manipulated to allow the subjects to “act” in their occupied space and transfer convincingly to a completely different scene.

### Verification of Game Engine Poses With Epipolar Geometry

Developed an epipolar pose verification pipeline that utilized the calibrated first person GTA V camera and the ScriptHook mod engine to extract game pose. The approach was unique in that it could successfully verify the pose accuracy without knowledge of the necessary order of rotations or brute-forcing through all of the possibilities.

### Object Detection and Tracking Using Multiple Webcams

Developed a multi-processing based pool-ball detection and tracking system using OpenCV and YOLOv4 with manual synchronization via queues and events for real-time game analysis over Android phones streaming video through the IP Webcam app.

## Tech Stack

---

### Programming Languages

- Python: Proficient in using Python for data analysis, deep/machine learning, and computer vision tasks.
- MATLAB: Experienced in developing computer vision applications and various optimization approaches.

### Platforms, Modules, and Libraries

#### Computer Vision

- `OpenCV`: Strong skills in computer vision tasks such as image processing and object detection.
- `Pillow`: Proficient with Pillow as a more lightweight image processing alternative to OpenCV.
- Deep Learning for Computer Vision: Experience in implementing and fine-tuning convolutional neural networks for image detection, classification, and segmentation.

#### Data Manipulation and Analysis

- `Pandas`: Experienced in data manipulation and analysis using Pandas library.
- `NumPy`: Proficient in numerical computing and array operations with NumPy.

#### Deep/Machine Learning

- `Scikit-Learn`: Extensive experience in building and evaluating machine learning models.
- `TensorFlow`, `PyTorch`: Proficient in deep learning frameworks for neural network development.

#### Version Control

- `Git/GitHub`: Experienced in version control for collaborative development and project management.

## Currently Learning

- Theory and practical applications for Natural Language Processing and Large Language Models.
- Django for building functional REST APIs and some elements of web development with slight HTML and CSS.
- CI/CD, specifically with GitHub Actions and Docker.
