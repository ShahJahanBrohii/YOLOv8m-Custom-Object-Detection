# YOLOv8m Custom Object Detection Training

![Performance Curve](results/runs/detect/Dental_Cavity_Research/v8m_full_research/graphs/Code_Generated_Image (1).png)

This repository contains the implementation and training results for a custom object detection model based on the **YOLOv8 (Ultralytics)** architecture. The model was trained over 80 epochs to detect specific classes in a custom dataset with high precision and recall.

## 🚀 Project Overview
The goal of this project was to leverage the state-of-the-art YOLOv8 architecture to create a robust object detection system. The model utilizes Deep Functional Loss (DFL) and advanced data augmentation to achieve reliable performance across varied lighting and environmental conditions.

### Key Metrics (Final Epoch)
- **mAP@50:** 0.6523
- **mAP@50-95:** 0.3964
- **Precision:** 0.6457
- **Recall:** 0.5978
- **Total Training Time:** ~10.4 hours

## 📊 Training Performance
The following plots illustrate the convergence of the model during the training process:

![Training Summary](results_summary.png)

* **Box Loss:** Shows steady optimization of the bounding box coordinates.
* **mAP Progression:** Displays the model's increasing accuracy in object localization and classification.
* **Learning Rate:** Utilized an initial warm-up followed by a cosine decay schedule.

## 🛠️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ShahJahanBrohii/YOLOv8m-Custom-Object-Detection.git
   cd YOLOv8m-Custom-Object-Detection
