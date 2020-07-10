---
title: "Human Posture Recognition Based on Neural Network in Robot Controlling"
excerpt: "Undergraduate Thesis Awards, 1st place, April 2013.<BR/>NTCU Software Engineering Laboratory<br/><B>Cheng-Yan Guo</B>, Liang Hung. <br/> Advisor: Chorng-Shiuh Koong, Ph.D.<br/><br/>We study possibility to control the robot using a natural user interface(NUI) and human posture recognition based on neural network. Our humanoid robot platform is BeRobot, BeRobot is 16 degree of freedom(DOF) humanoid robot, we using the Microsoft Kinect recived skeleton, then calculate vector dot product of keypoint, input vector dot product to our posture recognition neural network(Fully Connected), output pre-define human posture, finally, transmit the posture to the robot through Bluetooth to control.<br/><img src='/res/undergraduate-research/GUI-Demo.gif'  width='800' height='600'>"
collection: research
---

We study possibility to control the robot using a natural user interface(NUI) and human posture recognition based on neural network. Our humanoid robot platform is BeRobot, BeRobot is 16 degree of freedom(DOF) humanoid robot, we using the Microsoft Kinect recived skeleton, then calculate vector dot product of keypoint, input vector dot product to our posture recognition neural network(Fully Connected), output pre-define human posture, finally, transmit the posture to the robot through Bluetooth to control.

<p align="center"><a href="https://youtu.be/mwJW_ZBdZ-g">System Demo<br/><img src="/res/undergraduate-research/GUI-Demo.gif" width="800" height="600"></a></p>


System architecture and posture recognition flow with neural network.
<p align="center">
    <img src="/res/undergraduate-research/system.png" width="800" height="600">
</p>

<p align="center">
    <img src="/res/undergraduate-research/program-arch.png" width="800" height="600">
</p>

<p align="center">
    <img src="/res/undergraduate-research/BT-control-Berobot.jpg" width="800" height="600">
</p>


Keypoint K1 to K4, for calculate vector dot product.
<p align="center">
    <img src="/res/undergraduate-research/skeleton.png" width="300" height="300">
</p>

<p align="center">
    <img src="/res/undergraduate-research/pose-calc.png" width="600" height="800">
</p>

Dataset for Back-Propagation, format Keypoint1-4 and posture 1-9.
<p align="center">
    <img src="/res/undergraduate-research/dataset-example.png" width="800" height="600">
</p>


Training program.
<p align="center">
    <img src="/res/undergraduate-research/training-program.png" width="800" height="600">
</p>


Data classification.
<p align="center">
    <img src="/res/undergraduate-research/Postures-classification.png" width="800" height="600">
</p>


Training dataset, validation dataset and test dataset result.
<p align="center">
    <img src="/res/undergraduate-research/result.png" width="800" height="600">
</p>


<p align="center"><a href="https://youtu.be/6yLbgtvzfQ4">Face identify, this is for Microsft Kinect 2Player to 6Player robot control<br/><img src="/res/undergraduate-research/FaceIdentify%20Demo.gif" width="800" height="600"></a></p>


Gesture recognition for menu selection and mouse control. <a href="https://www.youtube.com/watch?v=csUB1P2ji3c"> another example </a>
<p align="center">
    <img src="/res/undergraduate-research/hand-open.png" width="600" height="800">
</p>

<p align="center">
    <img src="/res/undergraduate-research/hand-close.png" width="600" height="800">
</p>

<p align="center"><a href="https://youtu.be/3z2oSk4kzhQ">Added x-asix, use custom Arduino servo motor controller<br/><img src="/res/undergraduate-research/kinect-track.gif" width="800" height="600"></a></p>
<p align="center">
    <img src="/res/undergraduate-research/kinect-add-x-axis.png" width="800" height="600">
</p>
