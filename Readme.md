# ECE253 Final Project: Enhancing Object Detection on Degraded Images

**A Comparative Study of Image Processing vs. Model Fine-Tuning**

## Team

- Xin Zhao
- Cheng Qian
- Pengfei Zhan

**Institution:** UC San Diego, ECE Department
 **Course:** ECE253 - Advanced Digital Image Processing

------

## Project Overview

This project compares traditional image processing methods versus deep learning fine-tuning for object detection on degraded images.

------

## Repository Structure

```
ece253-final-project/
├── ece253_final.py          # Main experiment script (Jupyter notebook)
├── requirements.txt          # Python dependencies
├── README.md                 # This file
├── data/                     # Dataset (not included - see below)
│   ├── train/                # Clean images + annotations
│   └── valid/                # Degraded images + annotations
└── paper/                    # Final report
    ├── final_report.pdf
```

------

## Quick Start

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

**Requirements:**

- Python 3.8+
- PyTorch 2.0+
- OpenCV 4.7+
- CUDA GPU (recommended) or CPU

### 2. Prepare Dataset

**Dataset Structure:**

```
data/
├── train/              # 50 clean images
│   ├── clean_001.jpg
│   ├── clean_001.xml   # PASCAL VOC format
│   └── ...
└── valid/              # 60 degraded images
    ├── dark_001.jpg    # Low-light (30 images)
    ├── dark_001.xml
    ├── blur_001.jpg    # Motion blur (30 images)
    ├── blur_001.xml
    └── ...
```

**Download Dataset:**
 [Link to dataset] (not included due to size)

### 3. Run Experiment

**Google Colab (Recommended)**

1. Upload `ece253_final.py` to Google Colab
2. Upload dataset ZIP file when prompted
3. Run all cells
4. Results will be downloaded automatically

