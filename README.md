# VisDrone Object Detection using YOLOv8

This project focuses on object detection in aerial drone imagery using the **VisDrone2019 dataset**. The main objective is to detect small, dense, and overlapping objects in complex urban environments captured from drone viewpoints.

The system is being actively developed and experiments are ongoing to improve detection accuracy, especially for small objects under challenging conditions.

---

## Dataset

**VisDrone2019 Object Detection Dataset**

- Source: Drone-captured urban and suburban scenes  
- Scale: ~10,000+ images  
- Total Annotations: ~343,000+ object instances (approx.)  
- Task: Multi-class Object Detection  
- Format: YOLO-style annotations (converted from original dataset format)

---

## Object Classes (10 total)

- pedestrian  
- people  
- bicycle  
- car  
- van  
- truck  
- tricycle  
- awning-tricycle  
- bus  
- motor  

---

## Approach (Work in Progress)

The project explores different strategies for improving detection performance on small and densely packed objects:

- Baseline training using YOLO-based object detection
- Data augmentation and resolution tuning
- Evaluation under standard inference settings
- Experimental inference enhancement using **SAHI (Slicing Aided Hyper Inference)** for improved small-object detection

---

## Current Status

- Model training and experimentation is ongoing  
- Performance tuning and inference optimization are actively being tested  
- Focus is on improving detection of small and occluded objects (e.g., bicycles, tricycles, awning-tricycles)

---

## Goal

To build a robust object detection pipeline capable of:

- Handling dense urban drone imagery  
- Improving recall for small objects  
- Maintaining real-time inference feasibility  
- Exploring inference-time optimization techniques like SAHI  

---

## Notes

This project is in active development. Metrics, configurations, and results may change as experiments continue.
