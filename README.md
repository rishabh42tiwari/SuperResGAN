# 🖼️ SuperGenGAN Image Enhancer

A React-based web application that enhances low-resolution or blurry images using a retrained **SuperGenGAN** (ESRGAN-based) super-resolution model.

---

## 🔍 Demo

| Before | After |
|--------|--------|
| ![](demo/before.jpg) | ![](demo/after.jpg) |

Place your demo images in:


---

## 🚀 Features

- Upload low-quality or blurry images  
- Generate high-resolution outputs using SuperGenGAN  
- Side-by-side Before/After comparison  
- Clean and modern React interface  
- Fast inference via backend API or local model setup  

---

## 📦 Pretrained Models

Place pretrained models inside:


Available models:

| Model Name | Description |
|------------|-------------|
| **RRDB_ESRGAN_x4.pth** | Final ESRGAN model used in the project. |
| **RRDB_PSNR_x4.pth**  | PSNR-oriented model optimized for high PSNR performance. |

> **Note:** Models were trained using the **MATLAB bicubic downsampling kernel**.  
Different kernels may introduce artifacts.

---

## 🛠️ Getting Started

This project was bootstrapped with **Create React App**.

### Install Dependencies
```bash
npm install
