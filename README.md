# multi-object-fashion-recognition-systemmulti-object-fashion-recognition-system
A comprehensive visual recognition system for multi-object apparel classification, detection, and instance segmentation using deep learning architectures such as ResNet, EfficientNet, YOLO, Mask R-CNN, and U-Net on the DeepFashion2 dataset.

🚀 Multi-Object Apparel Detection and Segmentation
📌 Overview
This project presents a comprehensive visual recognition system for analyzing clothing items in images. It addresses three core computer vision tasks:

Multi-label Classification – Identify all clothing categories present in an image
Object Detection – Localize clothing items using bounding boxes
Instance Segmentation – Generate pixel-level masks for each clothing item
The system is built using state-of-the-art deep learning architectures and evaluated on the DeepFashion2 dataset.

🎯 Objectives
Develop a scalable pipeline for fashion image understanding
Perform multi-object recognition in complex scenes
Compare performance of multiple deep learning models
Apply both training from scratch and transfer learning
📂 Dataset
Dataset: DeepFashion2
Contains person-centric images with:
Multiple clothing items per image
Bounding boxes
Segmentation masks
Landmark annotations
🧠 Methodology
🔹 Data Preprocessing
Selected top 5 most frequent clothing categories
Parsed JSON annotations
Handled class imbalance (resampling / augmentation)
Created train, validation, and test splits
🔹 Models Used
Classification Models
ResNet-50
EfficientNet (B0/B2)
MobileNetV3
Detection & Segmentation Models
YOLO (Detection + Segmentation)
Mask R-CNN
U-Net
⚙️ Training Strategy
Training from scratch (baseline)
Transfer learning using pretrained weights
Fine-tuning final layers
📊 Evaluation Metrics
Classification
Precision, Recall, F1-score
Macro & Micro F1-score
ROC-AUC
Detection
mAP@[0.5:0.95]
F1-score
Segmentation
Mean IoU (mIoU)
Dice Coefficient
📈 Results & Analysis
Comparative analysis of all models
Performance trade-offs between architectures
Visualization of predictions (bounding boxes & masks)
Key observations and insights
🤗 Model Deployment
Best models are uploaded to Hugging Face
Supports automated inference pipeline
📌 Key Features
End-to-end fashion AI pipeline
Multi-task learning (classification + detection + segmentation)
Efficient models for limited compute environments (Colab/Kaggle)
Clean and modular code structure
🧾 Deliverables
Data preprocessing pipeline
Training scripts for all models
Comparative analysis
Hugging Face model deployment
Final report
👨‍💻 Author
Mohit Kumar

⭐ Acknowledgment
This project is developed as part of a Visual Recognition coursework mini project.

📜 License
This project is for academic purposes.
