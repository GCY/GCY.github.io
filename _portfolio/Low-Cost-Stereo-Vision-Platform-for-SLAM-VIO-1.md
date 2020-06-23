---
title: "Low-Cost-Stereo-Vision-Platform-for-SLAM-VIO"
excerpt: "This is stereo camera project <br/> <img src='https://github.com/GCY/Low-Cost-Stereo-Vision-Platform-for-SLAM-VIO/raw/master/res/demo.gif'>"
collection: portfolio
---


![diagram](https://github.com/GCY/GCY.github.io/blob/master/res/Low-Cost-Stereo-Vision-Platform-for-SLAM-VIO/v1.3.jpg)


![diagram](https://github.com/GCY/GCY.github.io/blob/master/res/Low-Cost-Stereo-Vision-Platform-for-SLAM-VIO/diagram.png)


![demo](https://github.com/GCY/GCY.github.io/blob/master/res/Low-Cost-Stereo-Vision-Platform-for-SLAM-VIO/demo.gif) 


- 1. capture some [chessboard pattern](https://raw.githubusercontent.com/opencv/opencv/master/doc/pattern.png) picture from Left and Right Camera.
- 2. run "Stereo Camera Calibration"
- 3. calibration stereo camera phase, execute initUndistortRectifyMap with "extrinsics.yml" and "intrinsics.yml" befor cv::remap
- 4. create StereoBM or SGBM object to calculate depth map.
- 5. get point cloud from depth map and baseline.

[Github Link](https://github.com/GCY/Low-Cost-Stereo-Vision-Platform-for-SLAM-VIO)
