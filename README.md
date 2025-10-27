# 💎 3D Object Reconstruction from 2D Images

## 📘 Project Overview
This project is part of our **Digital Image Processing (DIP)** course.  
Our objective is to **reconstruct a 3D diamond model from multiple 2D images** using voxel-based visual hull techniques.  

The dataset contains **200 BMP images** of a diamond, each captured after a small angular rotation (~1.8° per frame).  
By combining these silhouette views, we aim to **generate a volumetric 3D diamond model**.

---

## 🧠 Current Progress
- ✅ Collected and organized the dataset of 200 BMP diamond images  
- ✅ Implemented **voxel grid creation and 3D visualization** using NumPy and Matplotlib  
- ✅ Developed **dummy silhouette generation** to test visual hull carving  
- ✅ Successfully reconstructed a **dummy 3D sphere model** using multiple silhouettes  
- 🔄 Next step: Apply the same voxel carving pipeline to **actual diamond silhouette images**

---

## 🧩 Workflow Pipeline
1. **Dataset Preparation:** Organize and preprocess all diamond images.  
2. **ROI Extraction:** Isolate only the diamond region from each image.  
3. **Silhouette Generation:** Convert ROI to binary silhouettes for carving.  
4. **Voxel Grid Creation:** Build a 3D voxel grid (e.g., 64×64×64).  
5. **Visual Hull Carving:** Use multi-view silhouettes to remove voxels outside the diamond shape.  
6. **3D Model Visualization:** Display the carved voxel structure.  
7. **Surface Refinement:** Smooth and export the reconstructed model (future stage).

---

## 🧪 Current Implementation Highlights
- Implemented voxel grid creation using:
  ```python
  X, Y, Z = np.meshgrid(x, y, z, indexing='ij')
- Created dummy circular silhouettes to simulate multi-view images.

- Rotated and projected voxel grids across 20 viewpoints for carving.

- Visualized the carved 3D sphere using Matplotlib’s 3D scatter plots.

---

## 🧰 Tools & Libraries
- Python

- OpenCV

- NumPy

- Matplotlib

- (More will be added as we progress)

---

##  🚀 Upcoming Steps

- Integrate actual diamond silhouettes in place of dummy ones

- Refine carving resolution for smoother voxel output

- Export the final voxel mesh into a 3D surface model (.obj)
