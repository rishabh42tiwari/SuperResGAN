# 🖼️ SuperGenGAN Image Enhancer

This React application allows users to upload any low or degraded image and enhance it using a retrained SuperGenGAN model based on the ESRGAN architecture.
After processing, the app generates a high-resolution version of the image that the user can easily download.

---

## 🔍 Sample Enhancement Results

Below is an example showing how the SuperGenGAN model converts a low-resolution image into a high-resolution output:

| Low Resolution Input | High Resolution Output |
|----------------------|------------------------|
| ![](results/before.png) | ![](demo/after.jpg) |


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

## 🎯 Use Cases

- Enhance old, blurry, or low-resolution photos  
- Improve image quality for social media or personal use  
- Upscale images for printing or digital artwork  
- Restore clarity in screenshots or compressed images  
- Quickly generate high-resolution outputs without complex tools

---

## 🚀 Getting Started

To run this application locally:

In the project directory, run:

### **npm install**
Installs all required dependencies.

### **npm start**
Starts the app in development mode.  
Open **http://localhost:3000** in your browser.

The page reloads automatically when you make changes.


---

### ⭐ If you find this project useful, consider giving it a star!


