# Portfolio
Resourceful and self-driven developer with over a decade of programming experience in
Python, C++, PHP, and HTML/CSS, along with six years of hands-on work in electronics
and embedded systems. Recently graduated with an AP degree in IT Technology and
have experience working both independently and collaboratively on a wide range of
projects. Skilled across domains including robotics, embedded systems, machine
learning, web development, and 3D modeling using Blender and Fusion 360. Known for
strong problem-solving instincts and an ability to identify subtle issues or
unconventional solutions where others may get stuck.

---

## Education
***IT-teknolog AK - UCL Erhvervsakademi og Professionshøjskole, Odense***

2023 - 2025

***Learning outcomes:*** 
***Embedded Systems & Hardware Design*** 
* Designed and built systems using microcontrollers and analog/digital electronics
* Developed reliable, testable embedded systems for data collection and device control
* Gained practical experience with IoT device design and communication protocols\
  
***Software Development & Scripting*** 
* Developed software in C for embedded and IoT systems
* Used Python for automation, scripting, and network configuration tasks
* Implemented data pipelines and cloud-based processing systems\
  
***Project Management*** 
* Led and contributed to technical projects from concept to delivery
* Applied project management tools for resource planning, risk assessment, and budgeting
* Gained hands-on experience managing people and timelines in real-world scenarios\
  
***Internet of Things (IoT) Systems*** 
* Built end-to-end IoT systems: from sensor data collection to cloud-based data processing
* Focused on IT security across the entire IoT ecosystem
* Progressed from basic component work to advanced systems integration in projects

---

## Professional experience 
***Webmaster - DanskeServiceYdelser***
2019 - 2022
***Tasks***
Development of website and platform. Daily operation of the website. Ongoing
maintenance and updating of the website.

***What did I become particularly good at***
Development of a platform that works on all devices such as PC, tablet and phones.
Front- and backend website development divided into levels

---
## Projects

### Hand Tracking and Gesture Recognition
![](assets/img/ar_interaction_img.png)

This project involved the design and implementation of a real-time hand tracking and gesture recognition system for natural interaction within a defined workspace. The system recognizes four gestures: Point, Pinch, Open Hand, and Swipe, making it suitable for applications in Augmented Reality (AR) where controller-free interaction is key.

#### Project Highlights

***System Design***
* Implemented a top-down camera setup capturing hand movements within a calibrated interaction frame.
* Built a pipeline combining Computer Vision (CV) and Machine Learning (ML) approaches for gesture recognition.

***Computer Vision Techniques***
* Applied preprocessing methods (grayscale conversion, histogram equalization, Gaussian blur, bilateral filtering) to improve robustness.
* Used Canny edge detection, contour detection, convex hull, and convexity defect analysis to isolate and analyze hand shape.
* Developed rules based on convex hull angles and line segment lengths to classify gestures (e.g., distinguishing between Open Hand and Pinch).
* Implemented gesture dynamics detection: Swipe was recognized through frame-to-frame displacement of the convex hull.

***Machine Learning Approach***
* Built and trained a Convolutional Neural Network (CNN) in TensorFlow using a custom dataset of labeled gesture images.
* Model architecture included multiple Conv2D and pooling layers, with a final dense layer for classification into Open Hand, Pinch, and Point.
* Tested different activation functions, with sigmoid performing best for multi-class gesture classification.

#### Results

***Computer Vision:*** Delivered robust gesture recognition and hand tracking, though performance was sensitive to lighting conditions.
***Machine Learning:*** Successfully classified gestures from static images but lacked temporal awareness (e.g., could not detect Swipe).
***Comparative evaluation*** showed that CV was more reliable for AR integration, while ML offered strong potential when combined with better datasets.


### LiDAR system
* ***this*** and that
* that and ***this***
