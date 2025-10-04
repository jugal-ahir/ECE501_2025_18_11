# 💎 3D Object Reconstruction from 2D Images

## 📘 Project Overview
This project is part of our **Digital Image Processing (DIP)** course.  
Our aim is to **convert 2D diamond images into a 3D diamond model** using image processing and voxel-based reconstruction techniques.

The dataset consists of **200 BMP images** of a diamond, each taken after a small rotation (1.8° per image).  
By combining these views, we plan to **rebuild the diamond in 3D**.

---

## 🧠 Current Progress
- ✅ Collected and organized the dataset of 200 BMP images  
- ✅ Basic ROI (Region of Interest) selection for the diamond  
- 🔄 Working on image preprocessing (binarization & cleaning)  
- ⏳ Next step: 3D voxel grid construction and carving

---

## 🧩 Planned Workflow
1. **Dataset Preparation:** Organize and preprocess all 2D diamond images.  
2. **ROI Selection:** Extract only the diamond region from images.  
3. **Image Cleaning:** Convert to silhouettes and fill any gaps.  
4. **Voxel Grid Creation:** Initialize a 3D cube representing possible diamond volume.  
5. **Carving Process:** Project each 2D image to remove unnecessary voxels.  
6. **Smoothing & Export:** Refine the surface and export as a `.obj` 3D model.

---

## 🧰 Tools & Libraries
- **Python**
- **OpenCV**
- **NumPy**
- **Matplotlib**
- (More to be added as the project evolves)

---

## 🚧 Status
🚀 *Project just started — development and updates in progress.*  
The README will be expanded as new stages are completed.

---

## 🏁 Goal
To reconstruct a realistic **3D model of a diamond** using only its **2D image projections**, showcasing the power of **Digital Image Processing**.
