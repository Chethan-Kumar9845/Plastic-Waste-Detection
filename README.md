# Plastic-Waste-Detection

## Overview
This project focuses on detecting plastic waste objects using computer vision and deep learning techniques. The detection model is based on YOLOv5 and trained on a publicly available plastic object detection dataset.

---

## Dataset
The dataset used in this project for plastic waste detection is publicly available on Kaggle:  
[Plastic Object Detection Dataset on Kaggle](https://www.kaggle.com/datasets/dataclusterlabs/plastic-object-detection-dataset?resource=download)  

Please download and extract the dataset before running the notebooks.

---

## Features
- Custom YOLOv5 model training for plastic object detection  
- Conversion of dataset annotations to YOLO format  
- Interactive image upload widget for real-time inference inside the notebook  
- Visualization of detection results with bounding boxes  
- Modular code structure for easy experimentation and extension

---

## Installation and Setup

### Requirements
- Python 3.7 or higher  
- PyTorch  
- torchvision  
- numpy  
- matplotlib  
- pillow  
- ipywidgets  
- Other dependencies: see `requirements.txt` or install manually

### Install dependencies example
pip install torch torchvision matplotlib pillow ipywidgets

### Running the Project
1. Download and extract the Kaggle dataset.  
2. Run the notebook `Plastic_Waste_Detection_Using_Image_Recognition.ipynb` step-by-step.  
3. Use the provided interactive widget to upload images and get detection results in real-time.

---

## Example Output

![Detection Results](https://github.com/Chethan-Kumar9845/Plastic-Waste-Detection/blob/main/Result.png)

---

## Usage

- Train the YOLOv5 model on the prepared data.  
- Upload an image via the widget to detect plastic waste objects interactively.  
- View bounding boxes and confidence scores overlaid on input images.

---

## Acknowledgements

- Dataset provided by DataClusterLabs on Kaggle  
- YOLOv5 by Ultralytics for state-of-the-art object detection  
- Open source libraries: PyTorch, matplotlib, PIL, ipywidgets

---




