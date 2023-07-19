# computer-vision-projects
This repo is a documentation for computer vision mini-project developed at Computer Vision Course at UMD.

# Repository Overview 

This repository documents the journey through a series of image processing, computer vision and machine learning tasks, encapsulated within six homework assignments and a final project. Each piece of work introduces unique concepts and employs various algorithms and techniques, providing a comprehensive view of the evolving capabilities learned over the course. 

The following summarizes the content of this repository:

## Homework Assignments 

### Homework 1: Hybrid and Pyramid Images 

The first homework introduces two image processing techniques: Hybrid Image creation and Pyramid Image construction. 

- **Hybrid Image**: Combines two images by applying low-pass filtering to one and high-pass filtering to the other. The hybrid image appears to be one picture when viewed up close and another when viewed from afar. This task leverages several Python libraries such as cv2, numpy, pandas, skimage, PIL, matplotlib, and scipy.
- **Pyramid Image**: Constructs Gaussian and Laplacian pyramids from an image. Each level of the pyramid has half the resolution of its predecessor. The pyramids are then visualized both as intensity images and as the log magnitude of their Fast Fourier Transform (FFT).

### Homework 2: Keypoint Selection and Feature Tracking 

The second homework deals with tracking features in an image sequence using Harris corner detection for keypoint selection and the Kanade-Lucas-Tomasi (KLT) algorithm for feature tracking.

### Homework 3: Shape Alignment and Object Instance Recognition 

The third homework assignment focuses on the alignment of two sets of points using the Iterative Closest Point (ICP) algorithm and object instance recognition using the Lowe's Scale Invariant Feature Transform (SIFT) algorithm.

### Homework 4: Epipolar Geometry and Image Stitching 

In this assignment, the focus is on epipolar geometry and the application of the Normalized 8-point algorithm with RANSAC to estimate the Fundamental Matrix. It also involves image stitching, a technique to combine multiple images with overlapping fields of view to create a wide-angle panorama.

### Homework 5: Affine Structure from Motion 

The fifth homework explores the topic of Structure from Motion (SfM), a technique for estimating 3D structures from 2D image sequences. The task was to recover a 3D point cloud from an image sequence using the Affine Structure from Motion algorithm.

### Homework 6: Image Classification and Semantic Segmentation 

The sixth homework is divided into two parts:
- **Part 1**: Involves training an image classifier using the CIFAR-10 dataset and the PyTorch library. The classifier is trained to correctly identify images across 10 different classes.
- **Part 2**: Implements a semantic segmentation model that assigns a class to each pixel in an image. This part introduces the concepts of semantic segmentation in computer vision.

## Final Project: Visual Odometry 

The final project focuses on implementing visual odometry to reconstruct the 3D trajectory of a camera mounted on a vehicle. The project employs various computer vision techniques, such as keypoint detection, fundamental and essential matrix estimation, and decomposition into translation and rotation parameters. Two distinct approaches are implemented: one that leverages built-in functions provided by OpenCV and a custom approach. The final product is a 3D plot visualizing the trajectory of the camera.

This repository showcases a wide range of image processing, computer vision, and machine learning techniques, making it a comprehensive overview of these fascinating domains. The implementation details, results, and lessons learned in each assignment and project will provide insights into these areas of study. 
