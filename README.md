# 🖼️ SuperGenGAN Image Enhancer

A React-based web application that improves low-resolution or blurry images using a retrained **SuperGenGAN** (ESRGAN-based) machine learning model.  
The application allows users to upload an image, process it through the super-resolution model, and compare the Before/After results inside a clean React interface.

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

## 🚀 Getting Started

In the project directory, you can run:

---

### **npm start**


Runs the app in development mode.  
Open **http://localhost:3000** to view it in your browser.

The page will reload when you make changes.  
You may also see lint errors in the console.

---

### **npm test**




Launches the test runner in interactive watch mode.

---

### **npm run build**


Builds the app for production into the `build` folder.  
The build is minified and filenames include hashes.  
Your app is ready to be deployed!

---

### **npm run eject** (Optional)


> **Note:** This is a one-way operation. Once you eject, you cannot go back.

This command copies all configuration files (Webpack, Babel, ESLint, etc.) so you have full control over your development environment.

---

## 📚 Project Purpose

- Demonstrates how a React app can integrate with a super-resolution ML model  
- Provides a simple Before/After comparison UI  
- Uses retrained **SuperGenGAN (ESRGAN-based)** models  
- Clean structure suitable for demos, learning, or extensions

---

### ⭐ If you find this project useful, consider giving it a star!


