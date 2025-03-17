# Liver_Disease

# 3D Medical Image Segmentation using 3D U-Net (MONAI)

This repository contains an end-to-end pipeline for **3D medical image segmentation** using the **Decathlon Liver03 dataset**. 
The project leverages the **3D U-Net architecture** from the [MONAI library](https://monai.io/) and is built using the **PyTorch framework**.

## 📌 Project Overview
- **Dataset**: [Medical Segmentation Decathlon - Task03 Liver](http://medicaldecathlon.com/)
- **Task**: Segmentation of liver and tumors from **3D volumetric medical images**.
- **Preprocessing**: Handling **DICOM** and **NIfTI** formats, normalization, and augmentation.
- **Model**: **3D U-Net** implementation using **MONAI** and **PyTorch**.
- **Training**: GPU-accelerated training with optimizations.



📂 dataset-root


 ├── 📂 TrainVolumes01
 │    ├── volume-0.nii
 │    ├── volume-1.nii
 │    ├── ...
 │

 
 ├── 📂 TrainSegmentation01
 │    ├── segmentation-0.nii
 │    ├── segmentation-1.nii
 │    ├── ...
 │

 
 ├── 📂 TestVolumes01
 │    ├── volume-0.nii
 │    ├── volume-1.nii
 │    ├── ...
 │

 
 ├── 📂 TestSegmentation01
 │    ├── segmentation-0.nii
 │    ├── segmentation-1.nii
 │    ├── ...
