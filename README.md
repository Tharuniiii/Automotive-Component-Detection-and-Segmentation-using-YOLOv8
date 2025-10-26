# Automotive-Component-Detection-and-Segmentation-using-YOLOv8
This project focuses on automated detection and segmentation of car components using the YOLOv8 segmentation model. By leveraging deep learning and computer vision, the system can identify and outline key parts of a vehicle such as doors, headlights, bumpers, and windshields from images.


The project aims to demonstrate the potential of real-time vision-based vehicle understanding, useful in domains like:

Automotive manufacturing

Intelligent repair systems

Damage detection

Autonomous driving research
---

# 🧠 Key Features

🚘 Detects and segments multiple car parts with pixel-level precision

⚡ Powered by Ultralytics YOLOv8 segmentation

💻 Interactive Gradio web interface for real-time testing

🧾 Trained on the CarParts-Seg dataset

📦 Exports trained model to multiple formats (ONNX, TorchScript, etc)

# 🧩 Tech Stack

Framework: Ultralytics YOLOv8

Frontend: Gradio

Language: Python

Environment: Google Colab
---
# 🗂️ Dataset: CarParts-Seg

Source: https://docs.ultralytics.com/datasets/segment/carparts-seg/

Description: Contains labeled car images with segmented regions for components like bumpers, doors, headlights, mirrors, etc.

Structure:
---
carparts-seg/
├── images/
│   ├── train/
│   └── val/
├── labels/
│   ├── train/
│   └── val/
├── carparts-seg.yaml
---

# 🧩 Model Architecture

The project uses the YOLOv8-Segmentation variant, which combines:

A CSP-based backbone for feature extraction

PANet neck for multi-scale feature fusion

A segmentation head to generate precise masks
---
# 🧰 Requirements
``` pip install ultralytics gradio pillow ```
---
# 🏁 Results

Segmentation Accuracy: ~99% (custom-trained model)

Applications:

Smart vehicle inspection

Damage assessment automation

Automotive manufacturing quality control
<img width="1919" height="802" alt="image" src="https://github.com/user-attachments/assets/dcc9293c-46d2-46f3-ab5c-3d3a0e438800" />

👩‍💻 Author

Tharuni T
Graduated Researcher | Networking & AI Enthusiast
Developed using Ultralytics YOLOv8 and Gradio
