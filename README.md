# Speed Estimation Project

This project focuses on estimating the speed of vehicles using computer vision techniques. The primary goal is to detect vehicles in a video stream and calculate their speeds in real-time.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Results](#results)

## Introduction

Accurate vehicle speed estimation is crucial for traffic monitoring and safety enforcement. This project utilizes object detection and tracking algorithms to estimate the speed of vehicles from video footage.

## Methodology

The project employs the following steps:

1. **Vehicle Detection**: Using a pre-trained object detection model to identify vehicles in each frame.
2. **Vehicle Tracking**: Assigning unique IDs to detected vehicles and tracking their movement across frames.
3. **Speed Calculation**: Estimating the speed of each vehicle based on the change in position over time, considering the frame rate and real-world scale.

## Results

The implemented approach successfully detects and tracks vehicles, providing real-time speed estimations. The results demonstrate the potential of computer vision techniques in traffic monitoring applications.

[![The Resulted Video](https://img.youtube.com/vi/bSXY2VK_1-A/0.jpg)](https://www.youtube.com/watch?v=bSXY2VK_1-A)
