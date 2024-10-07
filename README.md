**Feature Detection and Matching**

This project implements keypoint detection, feature description, and feature matching between two images using OpenCV. It is part of the Code-FDDM assignment, which involves three main tasks:

_Keypoint Detection:_

Harris Corner Detection is used to identify points of interest (corners) in the input images.

_Feature Description:_

The Scale-Invariant Feature Transform (SIFT) algorithm is applied to extract feature descriptors at each detected keypoint.

_Feature Matching:_

Keypoints between two images are matched using the Sum of Squared Differences (SSD) method. Matches are further refined by applying a ratio test, which compares the closest and second closest feature matches.

_Files:_

_Code:_ The code is implemented in S20220010192_FDDM.ipynb.

_Outputs:_
Keypoint detection results: S20220010192_FDDM_output1.png, S20220010192_FDDM_output2.png
SIFT keypoints: S20220010192_FDDM_output3.png, S20220010192_FDDM_output4.png
Feature matching results: S20220010192_FDDM_output5.png

_Requirements:_
Python
OpenCV
Numpy
Matplotlib

_Usage:_
Run the script to process the input images, detect keypoints, extract features, and match them. The number of matched keypoints will be displayed, and the visualized results will be saved as output files.
