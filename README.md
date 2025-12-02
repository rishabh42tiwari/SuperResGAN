# 🖼️ SuperGenGAN Image Enhancer

A React-based web application that transforms low-resolution or blurry images into high-quality outputs using a retrained SuperGenGAN (ESRGAN-based) super-resolution model.
Users can upload a degraded image, process it through the ML model, and instantly compare the Before/After results through a clean and intuitive interface.

---

## 🔍 Demo (Before & After)

| Before | After |
|--------|--------|
| ![](demo/before.jpg) | ![](demo/after.jpg) |


---

## 🤖 Machine Learning Models

We provide two ESRGAN-based SuperGenGAN models:

| Model Name | Description |
|------------|-------------|
| **RRDB_ESRGAN_x4.pth** | Final ESRGAN model used in the project (high perceptual quality). |
| **RRDB_PSNR_x4.pth**  | PSNR-oriented model optimized for highest clarity and PSNR performance. |

> **Note:**  
> These models were trained using the **MATLAB bicubic downsampling kernel**.  
> If your input images come from a different kernel, the results may contain artifacts.

---

## 📚 Project Purpose

- Demonstrates how a React app can integrate with a super-resolution ML model  
- Provides a simple Before/After comparison UI  
- Uses retrained **SuperGenGAN (ESRGAN-based)** models  
- Clean structure suitable for demos, learning, or extensions

---

### ⭐ If you find this project useful, consider giving it a star!


