# LV-Image Segmentation and Ejection-Fraction-Assessment
"Efficient and Accurate Automated LV Image Segmentation and Ejection Fraction Assessment"


# 🧭 Problem Statement:
Accurate and efficient left ventricular ejection fraction (LVEF) assessment is critical for the diagnosis and management of heart diseases. However, current methods for LVEF assessment can be time-consuming and prone to human error, leading to delayed or incorrect diagnoses. Therefore, there is a need for an automated and accurate LVEF assessment system to improve patient outcomes and reduce healthcare costs.

# ⛳️ The goals :
Data Collection and Exploratory Data Analysis
Preprocessing
Feature Extraction
Model Development and Training
Evaluate Model
 
 
# 🛝 Directory Structure:


CAM
└── data
    ├── testing
    │   ├── 2ch
    │   │   ├── frames
    │   │   ├── sequences
    │   │   ├── masks
    │   │   └── info
    │   └── 4ch
    │       ├── frames
    │       ├── sequences
    │       ├── masks
    │       └── info
    └── training
        ├── 2ch
        │   ├── frames
        │   ├── sequences
        │   ├── masks
        │   └── info
        └── 4ch
            ├── frames
            ├── sequences
            ├── masks
            └── info

Each subfolder contains the following:

frames: contains raw DICOM image files (.dcm)
sequences: contains preprocessed image files in MetaImage format (.mhd, .raw)
masks: contains the segmentation masks for the corresponding images (.mhd, .raw)
info: contains configuration files (.cfg) and other metadata about the images.
