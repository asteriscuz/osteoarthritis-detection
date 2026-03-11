# Osteoarthritis Detection via Computer Vision

A classical computer vision project to detect and grade osteoarthritis severity from knee X-ray images.

## Overview

Osteoarthritis is a degenerative joint condition affecting millions worldwide. This project builds an image analysis pipeline that processes knee X-ray scans and classifies osteoarthritis severity across Kellgren-Lawrence grades 0 to 4 using classical computer vision techniques.

## Pipeline

Image Preprocessing → Histogram Equalisation → Filtering & Noise Reduction → Edge Detection → Feature Extraction → Classification

## Tech Stack

Python · OpenCV · Scikit-learn · NumPy · Matplotlib

## Dataset

Kaggle Knee X-Ray dataset with 5 severity grades based on the Kellgren-Lawrence grading scale.

## Project Structure
```
osteoarthritis-detection/
├── data/
│   └── README.md
├── notebooks/
│   └── exploration.ipynb
├── src/
│   ├── preprocess.py
│   ├── features.py
│   └── classify.py
└── requirements.txt
```

## Status

🚧 In Progress
