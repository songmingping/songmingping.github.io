---
title: Digital Twin-based Smart Building Management
summary: Leveraging Digital Twin technology, my project aims to revolutionize smart building management systems by predicting personal thermal comfort. This system integrates point cloud reconstruction, depth cameras, and IoT technologies to offer a comprehensive understanding of indoor conditions and achieve personalized thermal comfort predictions.
tags:
  - Deep Learning
  - Digital Twins
date: '2023-05-25T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

## Digital Twin-Based Smart Building Management System
*A Personalized Thermal Comfort Prediction Approach*

### Abstract

Leveraging Digital Twin technology, my project aims to revolutionize smart building management systems by predicting personal thermal comfort. This system integrates point cloud reconstruction, depth cameras, and IoT technologies to offer a comprehensive understanding of indoor conditions and achieve personalized thermal comfort predictions.

### Introduction

The project harnesses the potential of IoT and Digital Twins, underpinned by advanced technologies like deep neural networks and machine learning. These tools facilitate the creation of accurate virtual representations of physical systems, which can be utilized for predictive modeling, analysis, and optimization.

![Figure 1: The whole sysytem](whole_system.png "Figure 1: The whole sysytem")

### Framework

The system's architecture captures and visualizes real-time data, predicting personal thermal comfort through an innovative machine learning approach.

- **Data Capture**: Utilizing temperature and humidity sensors for detailed indoor data.
- **Data Transmission**: Employing IoT technology for efficient data communication.
- **Data Visualization**: Leveraging Unreal Engine for interactive UI and model visualization.

### Methodology

I've implemented an advanced back-end server using Python, with data storage managed by a MySQL cloud database. The project's core is the personalized algorithm for thermal comfort prediction, realized through PyTorch deep learning frameworks.

- **Algorithmic Innovation**: Combining Random Forest with Deep Neural Network inputs for accurate thermal comfort predictions.
- **User Interface**: Developed using Unreal Engine to facilitate user interaction.

### Model structure and performance
In terms ofgeneralizedprediction, thefine-tuned DNN has the bestperformanceover other models.
![Figure 2: Model structure and performance](model_performance.jpg "Figure 2: Model structure and performance")

### Experiment Results

In the experiment, three participants provided thermal comfort votes as ground truth.Predictions from the traditional PMV, a deep neural network, and our approach were thencompared against these ground truth values for analysis.
![Figure 3: Experiment Results](building_result.jpg "Figure 3: Experiment Results")

### Conclusion & Discussion

This innovative smart building technology marks a significant step towards real-time, personalized thermal comfort prediction. Future work includes enhancing the prediction accuracy through potential use of transfer learning and exploring multi-office system applicability.

For a more in-depth look at the algorithmic discussions and the development tasks, please refer to the accompanying documents and code samples provided.

References:
1. [ScienceDirect Article on Thermal Comfort Database](https://www.sciencedirect.com/science/article/pii/S0360132318303652)
2. [Kaggle ASHRAE Global Thermal Comfort Database II](https://www.kaggle.com/datasets/claytonmiller/ashrae-global-thermal-comfort-database-ii)


