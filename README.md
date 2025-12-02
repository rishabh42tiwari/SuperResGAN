# 🖼️ SuperGenGAN Image Enhancer

A React-based web application that improves low-resolution or blurry images using a retrained **SuperGenGAN** (ESRGAN-based) machine learning model.  
The application allows users to upload an image, process it through the super-resolution model, and compare the Before/After results inside a clean React interface.

---

## 🔍 Demo (Before & After)

| Before | After |
|--------|--------|
| ![](demo/before.jpg) | ![](demo/after.jpg) |


---

## 📁 Folder Structure


---

## 🤖 Machine Learning Models

Place pretrained models inside:


We provide two ESRGAN-based SuperGenGAN models:

| Model Name | Description |
|------------|-------------|
| **RRDB_ESRGAN_x4.pth** | Final ESRGAN model used in the project (high perceptual quality). |
| **RRDB_PSNR_x4.pth**  | PSNR-oriented model optimized for highest clarity and PSNR performance. |

> **Note:**  
> These models were trained using the **MATLAB bicubic downsampling kernel**.  
> If your input images come from a different kernel, the results may contain artifacts.

---

## 🚀 Getting Started

This project was built with **Create React App**.

### 1️⃣ Install Dependencies
```bash
npm install



