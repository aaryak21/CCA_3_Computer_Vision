# CCA_3_Computer_Vision

# CCA 3 – Computer Vision Assignment

**Student Name:** Aarya Suhas Kudale  
**PRN:** 1272250489  
**Subject:** Computer Vision and Applications  
**Platform:** Google Colab  
**Programming Language:** Python

---

## 1. Project Overview

This repository contains the implementation of CCA 3 – Computer Vision Assignment using Python and OpenCV in Google Colab.

The assignment demonstrates various computer vision techniques, including image processing, image segmentation, feature extraction, object detection, and video analysis.

The experiments are performed using two dog photographs and a traffic video.

## 2. Objectives

- To understand and implement image processing techniques.
- To perform image segmentation using the Watershed algorithm.
- To extract image features using HOG and SIFT.
- To detect human faces using the Viola-Jones algorithm.
- To perform object detection using YOLOv8.
- To extract video frames and analyze motion.
- To implement frame differencing, optical flow, and background subtraction.

## 3. Technologies Used

- Python
- Google Colab
- OpenCV
- NumPy
- Matplotlib
- Scikit-image
- Ultralytics YOLOv8

## 4. Assignment Tasks

### Task 1: Image Processing and Segmentation

This task involves loading and processing images using OpenCV.

Techniques implemented:
- Image loading and display
- Image resizing and comparison
- Watershed segmentation
- Foreground mask generation
- Image segmentation visualization

### Task 2: Feature Extraction

This task focuses on extracting important visual features from images.

Techniques implemented:
- Histogram of Oriented Gradients (HOG)
- Scale-Invariant Feature Transform (SIFT)
- Keypoint detection
- Feature matching
- Image matching after rotation and resizing

### Task 3: Object Detection

This task demonstrates object detection using different approaches.

Algorithms implemented:
- Viola-Jones face detection using Haar Cascade
- YOLOv8 object detection
- Comparison of traditional machine learning and deep learning approaches

### Task 4: Video Processing and Motion Analysis

This task focuses on analyzing traffic video frames.

Techniques implemented:
- Video loading and information extraction
- Frame extraction
- Frame differencing
- Lucas-Kanade Optical Flow
- Gaussian Mixture Model (GMM) Background Subtraction

## 5. Input Files

The following input files are used in the assignment:

- `photo_original.jpg` – Original dog photograph.
- `photo_second.jpg` – Second dog photograph used for image comparison and feature matching.
- `traffic_video.mp4` – Traffic video used for video processing and motion analysis.

## 6. Output Files

The generated outputs are stored in the `outputs` directory.

These include:
- Processed images
- Watershed segmentation results
- HOG feature visualizations
- SIFT feature matching results
- Face detection results
- YOLOv8 object detection results
- Extracted video frames
- Frame differencing masks
- Optical flow visualizations
- Background subtraction results

## 7. Repository Structure

```text
CCA_3_Computer_Vision/
│
├── README.md
├── CV_Aarya.ipynb
│
├── inputs/
│   ├── photo_original.jpg
│   ├── photo_second.jpg
│   └── traffic_video.mp4
│
├── outputs/
│   ├── Task 1/
│   ├── Task 2/
│   ├── Task 3/
│   └── Task 4/
│
└── CCA3_Computer_Vision_Assignment_Aarya_Suhas_Kudale.docx
```

## 8. How to Run the Project

1. Clone or download this repository.
2. Open `CV_Aarya.ipynb` in Google Colab.
3. Upload the required input images and traffic video.
4. Ensure that the input file paths in the notebook are correct.
5. Run the notebook cells sequentially.
6. Observe the generated outputs and visualizations.
7. Check the `outputs` directory for saved results.

## 9. Conclusion

This assignment provides practical experience with various computer vision techniques using Python and OpenCV.

It demonstrates image segmentation, feature extraction, object detection, and video motion analysis. Through these experiments, different computer vision algorithms and their applications are understood and implemented.

---

**Submitted by:**  
**Aarya Suhas Kudale**  
**PRN: 1272250489**
