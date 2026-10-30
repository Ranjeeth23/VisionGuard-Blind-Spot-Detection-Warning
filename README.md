# VisionGuard: Blind Spot Detection and Warning System Using Deep Learning

**An AI-powered camera-based Advanced Driver Assistance System (ADAS) research prototype for vehicle detection, tracking, and blind-spot warning.**

---

## Abstract

Blind-spot-related road accidents remain a significant safety concern, particularly during lane changes and vehicle manoeuvres. Conventional mirror-based systems may not provide complete visibility of surrounding vehicles, creating the need for intelligent driver assistance solutions.

VisionGuard proposes a camera-based Blind Spot Detection and Warning System using deep learning and computer vision techniques. The system is designed to process road-scene video, identify surrounding vehicles, track detected objects across consecutive frames, and monitor configurable left and right blind-spot regions. When a vehicle enters a designated warning region, the system generates visual and optional audio alerts to notify the driver.

The proposed prototype integrates vehicle detection, object tracking, region-of-interest analysis, temporal warning confirmation, and event logging through an interactive dashboard. The project also explores publicly available autonomous-driving datasets, including KITTI, for vehicle detection experiments and evaluation.

The primary objective is to develop an accessible research prototype that demonstrates how computer vision and deep learning can contribute to improved driver awareness and road safety. The system is intended for academic experimentation and is not a certified automotive safety solution.

**Keywords:** Advanced Driver Assistance Systems (ADAS), Blind Spot Detection, Deep Learning, Computer Vision, Object Detection, Vehicle Tracking, Region of Interest (ROI), Road Safety.

---

## Research Papers & Literature Review

The following research publications provide the academic foundation and technical motivation for VisionGuard.

### 1. Nighttime Data Augmentation Using GAN for Improving Blind-Spot Detection

**Authors:** Hongjun Lee, Moonsoo Ra, and Whoi-Yul Kim.

**Published in:** IEEE Access, Volume 8, 2020, pp. 48049–48059.

**DOI:** [10.1109/ACCESS.2020.2979239](https://doi.org/10.1109/ACCESS.2020.2979239)

**Research Contribution:**
- Proposes a conditional GAN-based framework for generating synthetic nighttime images from daytime images.
- Uses CycleGAN-based day-to-night image translation for data augmentation.
- Investigates improving camera-based blind-spot detection under low-illumination conditions.
- Demonstrates the potential of synthetic nighttime data to improve vehicle detection performance.

**Relevance to VisionGuard:** This research provides insight into improving blind-spot detection under challenging lighting conditions and highlights the importance of diverse training data.

### 2. Blind-Spot Collision Detection System for Commercial Vehicles Using Multi Deep CNN Architecture

**Authors:** Muhammad Muzammel, Mohd Zuki Yusoff, Mohamad Naufal Mohamad Saad, Faryal Sheikh, and Muhammad Ahsan Awais.

**Published in:** Sensors, Volume 22, Article 6088, 2022.

**DOI:** [10.3390/s22166088](https://doi.org/10.3390/s22166088)

**Research Contribution:**
- Proposes a blind-spot collision detection approach using multiple deep CNN architectures integrated with Faster R-CNN.
- Investigates self-designed CNN feature descriptors and pretrained ResNet-50 and ResNet-101 networks.
- Uses feature fusion to improve vehicle detection for commercial vehicles.
- Evaluates the proposed approaches using a self-recorded bus blind-spot dataset and the LISA vehicle dataset.

**Relevance to VisionGuard:** This paper provides a foundation for understanding deep-learning-based vehicle detection, feature extraction, and blind-spot collision detection
### Dataset
- LISA Vehicle Detection Dataset: [Dataset Link]([http://cvrr.ucsd.edu/LISA/vehicledetection.html](https://www.kaggle.com/datasets/mbornoe/lisa-traffic-light-dataset))
