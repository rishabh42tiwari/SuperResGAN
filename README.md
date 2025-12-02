# 🖼️ SuperGenGAN Image Enhancer

This React application allows users to upload any low or degraded image and enhance it using a retrained SuperGenGAN model based on the ESRGAN architecture.
After processing, the app generates a high-resolution version of the image that the user can easily download.

---

## 🧩 Use Cases

SuperGenGAN Image Enhancer can be used in a variety of real-world scenarios where image clarity and resolution matter:

- **Old Photo Restoration**  
  Enhance scanned photographs, childhood pictures, or historical images.

- **Mobile Photography Upscaling**  
  Improve low-resolution or compressed mobile photos taken in poor lighting.

- **Social Media Content**  
  Convert blurry or low-quality images into sharp visuals suitable for posting.

- **Academic & Research Visuals**  
  Enhance images for reports, presentations, or datasets requiring higher clarity.

- **E-commerce & Product Images**  
  Upscale small or compressed product photos for better visual appeal.

- **Profile Pictures & Portraits**  
  Sharpen selfies or profile pictures for better online presence.

- **AI/ML Preprocessing**  
  Prepare low-quality dataset images before feeding them to machine learning models.

---

## 🔍 Sample Enhancement Results

Below is an example showing how the SuperGenGAN model converts a low-resolution image into a high-resolution output:

| Low Resolution Input | High Resolution Output |
|----------------------|------------------------|
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


