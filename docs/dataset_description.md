# 🧬 Ultrasound Tumor Segmentation Dataset Description

## 📁 Dataset Structure

The dataset consists of two main folders:


- `training_data/` contains grayscale ultrasound images in `.png` format.
- `training_label/` contains corresponding binary masks for each image with a `_mask` suffix.

Each `*_mask.png` is a binary image where:
- Pixel value `0` = background
- Pixel value `1` = tumor region

## 🧠 Task Objective

Your goal is to **train a model** that learns to segment the tumor area from the ultrasound images.

Given an input image like `image_007.png`, your model should generate a corresponding mask `image_007_mask.png` of the same size.

## 🖼️ Image Information

- Format: PNG
- Channels: Grayscale (1 channel)
- Resolution: Varies (typically low-resolution)
- Bit depth: 8-bit

All images are real ultrasound scans from anonymized clinical data in Sub-Saharan Africa.

## 📏 Annotation Guidelines

All masks were annotated manually by radiologists using professional tools and cross-validated by medical physicists. Annotations capture tumor boundaries only, without surrounding artifacts.

## ⚠️ Notes

- Data has varying quality — real-world artifacts like speckle noise are present.
- Use proper normalization and preprocessing to handle image differences.
- Do not use test set data for training or tuning.

## 📥 Download Link

The dataset is hosted on Google Drive:

🔗 [Download Dataset](https://drive.google.com/...)

---

> This dataset is released for educational and research purposes only. Redistribution or commercial use is not allowed without permission.
