---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Medical Devices and Imaging System, National Taiwan University, 2017
  * MDI degree from College of Medicine. My research area includes Biomedical Signal Processing, Electrocardiography, Advanced Endoscopy, Non-Invasive Continuous Blood Pressure and Biodesign. Master's thesis: **algorithm of monitoring (detecting) electrocardiographic QRS complex occurring in arrhythmia patient**.
* B.S. in Computer Science, National Taichung University of Education, 2014
  * Win many robot awards and 1st place of departmental graduate project competition: **Human Posture Recognition Based on Neural Network in Robot Controlling**, focus on Robotics, Computer Vision, Embedded Systems and Reverse Engineering.

Work experience
======
* May 2016 – Feb 2018: Consultant, R&D Center
  * **Foxconn Technology Group** - Yonglin Biotech: Taipei, Taiwan
  * Lead core RD team to develop the toolchain(a series of software) for service robots in Foxconn Group. The toolchain includes robot motion editor, communication protocol between robots, robot interactive Health Education software, multiple robots synchronization method, communication between robots and Physiological Signal device(Muse, TPR), communication between robot and server and master- slave one-to-many robot wireless control method.
  * Develop Physiological Signal sensing algorithm and firmware with Microwave Radar of Doppler, obtain TW and CN patents and participate in EVT/PVT/DVT. Used algorithms and techniques include measure Breath, Heart Rate, Carotid pulse, Radial Artery pulse, Gesture detect, motion Deblur, FFT, Kalman filter, FIR and IIR.

* Jul 2015 – Jul 2017: Research Assistant, Institute of Medical Device and Imaging
  * **National Taiwan University**: Taipei, Taiwan
  * Develop software and firmware(MSP430, STM32F4) to implement the algorithm which I designed to enable wrist type blood pressure to detect Atrial Fibrillation(AF). Moreover, I join technology transfer to global companies. Implemented techniques include Systolic, Diastolic, Irregular Pulse Peak(IPP), Irregular Heart Beat(IHB), Atrial Fibrillation(AF), abnormal waveform detection, watch mode, history data, BLE4.0 communication and engineering mode.
  * Develop software and firmware(MSP430, STM32F4) on wrist type Non-Invasive Continuous Blood Pressure Monitor(NICBP) and then perform experiments to verify it. Implement algorithm for ECG, Heart Sound, Lung Sound, Carotid pulse, TEB, ICG, Doppler Microwave Radar and analog signal of Near- Infrared Spectrometry(NIRS). Finally I build the system based on the Moens-Korteweg equation, including Pulse Wave Velocity(PWV), Pulse Arrival Time(PAT), Pulse Transit Time(PTT), Pre-Ejection Period(PEP), Ellipse to Fit, Linear Relationship solve and calibration.
  * Research and develop algorithm on 3D diffraction optics endoscopy, use Hologram, grating, Diffraction Optics Element(DOE) to generate Structured Light image for measure surface depth and finally integrate algorithm and GUI into ARM Cortext-A7. Relevant techniques include Fraunhofer Diffraction, Fresnel Diffraction, Image Filter, Image Segmentation, Object Detection, Camera Calibration, Geometry Mesh and Embedded Linux.
  
* Jun 2013 – Aug 2015: Co-Founder CTO
  * **DOIT Shenlearn**: Taoyuan, Taiwan
  * I have been an entrepreneur with my classmates during college, our mission is to change traditional flow of
  education. Use digitization system on cloud server to reduce the burden on educators, focus on information management of class and student and communication between teachers and parents. I am responsible for the  direction and planning of software and hardware development, including strategy, Business Model(BM), Pitch to VCs, Fingerprint Identification, RFID reader, Mobile App and collaborate with Backend(AWS).
  
Skills
======
* Programing:
  * C++ 03
  * C++ 11/14
  * C
  * Assembly
  * Java(Android)

* Domain:
  * Robotics
  * Biomedical Signal Processing
  * Image Processing
  * Computer Vision
  * Sensors
  * Embedded System
  * Digital Holography
  
* Framework & Library:
  * wxWidgets
  * OpenCV
  * OpenNI
  * OpenGL
  * Tiny-DNN
  * OpenNN
  
Awards & Honors
======
* President **Tsai Ing-wen** reception with national representatives from CES 2019, Feb 2019
* NTCU CSIE departmental graduate project competition, first place, Dec 2013. Taiwan Intelligent Robot Contest, 2nd place, April 2013.
* Taiwan Intelligent Robot Contest, 3nd place, May 2014.
* Taiwan Student Cluster Competition, 3rd prize, May 2014.
* 2014 the 4th departmental graduate project competition in midland of Taiwan, 3nd place, May 2014. Taiwan Intelligent Robot Scientific Innovation Competition, 4nd place, Oct 2013.
* 2014 Maker Faire Taipei - International Humanoid Robot Maze Game Contest, control best award, May 2014.

Publications
======
<ul>{% for post in site.publications %}
{% include archive-single-cv.html %}
{% endfor %}</ul>
