# 🖼️ SuperGenGAN Image Enhancer

A React-based web application that improves low-resolution or blurry images using a retrained **SuperGenGAN** (ESRGAN-based) machine learning model.

This project combines a modern React UI with powerful image super-resolution models to produce sharp, high-quality results from degraded images.

---

## 🚀 Features

- 📤 Upload any low-quality or blurry image  
- 🤖 Uses pretrained **SuperGenGAN** models  
- 🔄 Side-by-side Before/After comparison  
- ⚛️ Smooth and modern React interface  
- ⚡ Fast inference through model API or local setup  

---

## 📦 Pretrained Models

Place pretrained models inside:


We provide two ESRGAN models:

| Model | Description |
|-------|-------------|
| **RRDB_ESRGAN_x4.pth** | Final high-quality ESRGAN model used in our research. |
| **RRDB_PSNR_x4.pth**  | PSNR-optimized model for maximum clarity. |

> ⚠️ These models were trained using the **MATLAB bicubic downsampling kernel**.  
If your input images use a different kernel, the output may contain artifacts.

---

## 🧪 Demo Results

Below is an example of what the model can do.

| Before | After |
|--------|--------|
| ![](demo/before.jpg) | ![](demo/after.jpg) |

Add your demo images inside:

