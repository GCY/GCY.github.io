---
title: "Arrhythmia Electrocardiogram(ECG) Signal Process Research"
excerpt: "When I served as a graduate research assistant of National Taiwan University, I developed algorithms for software and firmware on watch type Non-Invasive Continuous Blood Pressure Monitor(NICBP) with pulsemeter and ECG.<br/><img src='/res/NTUMC/ECG/patent.png'  width='600' height='600'>"
collection: research
---

 - Develop software and firmware(MSP430, STM32F4) on wrist type Non-Invasive Continuous Blood Pressure Monitor(NICBP) and then perform experiments to verify it. Implement algorithm for ECG, Heart Sound, Lung Sound, Carotid pulse, TEB, ICG, Doppler Microwave Radar and analog signal of Near-Infrared Spectrometry(NIRS). Finally I build the system based on the Moens-Korteweg equation, including Pulse Wave Velocity(PWV), Pulse Arrival Time(PAT), Pulse Transit Time(PTT), Pre-Ejection Period(PEP), Ellipse to Fit, Linear Relationship solve and calibration.

<br/>
Watch type cuffless blood pressure monitor, combine one lead ECG and pulsemeter.
<p align="center">
    <img src="/res/NTUMC/ECG/PROTOTYPE.png" width="800" height="600">
</p>

<br/>
Pulse Arrival Time(PAT) = ΔX = ECG QRS-Complex to arterial pulse wave peak.
<p align="center">
    <img src="/res/NTUMC/ECG/real-PAT.png" width="800" height="600">
</p>

<br/>
Reduce Moens–Korteweg equation to regression model.
<p align="center">
    <img src="/res/NTUMC/ECG/PAT-EQUATION.png" width="800" height="600">
</p>

<br/>
Mean Arterial Pressure(MAP) correlation coefficient 0.713.
<p align="center">
    <img src="/res/NTUMC/ECG/map-correction.png" width="800" height="600">
</p>

<br/>
<a href="https://gcy.github.io/publication/2017-07-Thesis">My Master’s thesis Published in National Taiwan University College of Medicine, 2017: Algorithm of monitoring (detecting) electrocardiographic QRS complex occurring in arrhythmia patient</a>
<p align="center">
    <img src="/res/NTUMC/ECG/thesis.png" width="800" height="600">
</p>

<br/>
<a href="https://gcy.github.io/patents/US20190387984A1">USPTO Patent: Electrocardographic monitoring device and blood pressure monitoring system using the same</a><br/>
<a href="https://gcy.github.io/patents/US20200000349A1">USPTO Patent: Pulse detection module and use-as-you-need blood pressure measurement device comprising the same</a><br/>
<a href="https://gcy.github.io/patents/US20200000350A1">USPTO Patent: Dynamic measurement device with a blood pressure determination function</a><br/>
<p align="center">
    <img src="/res/NTUMC/ECG/patent.png" width="600" height="800">
</p>
