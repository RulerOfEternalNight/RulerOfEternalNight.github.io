---
title: "Sea Dragon 🐉 - Autonomous Underwater Vehicle"
excerpt: "The Sea Dragon is an advanced Autonomous Underwater Vehicle (AUV) designed for underwater exploration and data collection. Built using state-of-the-art components, including an ESP32, Raspberry Pi 4B, and a variety of sensors, the Sea Dragon is capable of executing complex missions in challenging underwater environments.

<br/><br/>
<img src='/images/fiter.png' width='450' height='660' style='margin-bottom: 20px;'>
<img src='/images/video.gif' width='450' height='330' style='margin-bottom: 20px;'>
"

collection: portfolio
---


**Overview:**
The Sea Dragon is an advanced Autonomous Underwater Vehicle (AUV) designed for underwater exploration and data collection. Built using state-of-the-art components, including an ESP32, Raspberry Pi 4B, and a variety of sensors, the Sea Dragon is capable of executing complex missions in challenging underwater environments.

**Key Features:**
- **Real-Time Data Processing:** Equipped with a Raspberry Pi 4B, the Sea Dragon processes data on-the-fly, enabling real-time decision-making and navigation adjustments.
<video width='75%' controls controlsList="nodownload" oncontextmenu="return false;">
  <source src="/images/video.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
- **Precision Control System:** Utilizes an L298N motor driver for smooth and precise control of the vehicle's thrusters, ensuring stable maneuvering.
- **High-Resolution Imaging:** Features a Microsoft LifeCam VX-2000, providing clear underwater visuals for mapping and inspection tasks.
- **Environmental Sensing:** Integrated with BMP280 and DS18B20 sensors to monitor depth, temperature, and pressure, vital for maintaining operational safety and efficiency.
- **Adaptive Algorithms:** Incorporates an Adaptive Genetic Algorithm aided Kalman Filtering (AGAKF) system, significantly enhancing the accuracy of sensor readings and overall vehicle performance.

**Project Highlights:**
- **Sensor Precision Enhancement:** Developed an innovative AGAKF system to optimize sensor accuracy, reducing error deviations by over 90% compared to traditional methods.
<div style="display: flex; justify-content: center; align-items: center; max-width: 100%;">
    <img src='/images/fiter.png' alt="Image 1" style="margin: 10px; max-width: 50%; height: auto;">
    <img src='/images/video.gif' alt="GIF 1" style="margin: 10px; max-width: 50%; height: auto;">
</div>
- **Data-Driven Development:** Leveraged real-world data from the National Institute of Ocean Technology (NIOT) to fine-tune and validate the AGAKF algorithm, ensuring robust performance in diverse underwater conditions.
- **Collaborative Effort:** The project was a collaborative endeavor with experts and academics, demonstrating the ability to work in interdisciplinary teams.
- **Practical Applications:** Sea Dragon is designed to support various applications, including environmental monitoring, underwater mapping, and resource exploration.

**Technologies Used:**
- **Microcontroller:** ESP32
- **Processing Unit:** Raspberry Pi 4B
- **Motor Control:** L298N Motor Driver
- **Imaging:** Microsoft LifeCam VX-2000
- **Sensors:** BMP280 (Pressure and Temperature), DS18B20 (Temperature)
- **Software:** Python, MATLAB Simulink (for control system and algorithm implementation)

**Outcome:**
The Sea Dragon project successfully demonstrated the potential for AUVs to perform autonomous missions with high precision and reliability. The implementation of the AGAKF system, validated with data from NIOT, marked a significant advancement in the field of underwater robotics, paving the way for more accurate and efficient data collection in aquatic environments.

**Learn More:**
[Explore the Sea Dragon Project](https://rulerofeternalnight.github.io/AUV/)
