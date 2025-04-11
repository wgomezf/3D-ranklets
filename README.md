# 3-D ranklet transform applied to breast DCE-MRI volumes

We propose a 3-D ranklet transform method to extract texture features invariant to gray-scale image transformations. The ranklet transform performs a non-parametric, multi-resolution, and orientation-selective analysis initially proposed for 2-D images, and we extend it to the 3-D case. Texture features based on the 3-D gray-level co-occurrence matrix (GLCM) are calculated from ranklet images, giving a full 3-D description of volumes. The proposed method is applied to Dynamic Contrast-Enhanced Magnetic Resonance Imaging (DCE-MRI) sequences of the breast to differentiate benign from malignant tumors.

![picture alt](https://github.com/wgomezf/3D-ranklets/blob/main/abstract0.jpg "3D-ranklet")

The evaluation was performed on the public BreastDM dataset (https://github.com/smallboy-code/Breast-cancer-dataset). In this demo, we use one case to show the computation of the 3-D ranklet transform and the extraction of GLCM-based texture features. This DCE-MRI case (BreaDM-Ma-1802) was taken from the “...\BreaDM\seg\train” folder, although this code can be easily generalized to the rest of the cases in the dataset. Also, we provide the source codes to reproduce the results reported in our paper; the texture features data and the MLP models can be downloaded from [drive.google.com](https://drive.google.com/drive/folders/11VUle3VQeu8MpUfe2AHHRkVKS_wK3dlx?usp=sharing). Copy and paste these folders into the unzipped main directory.

Any use of our codes, please cite:

Wilfrido Gomez-Flores, Elisa Scalco, and Fernando Arce, "A 3-D Ranklet-based Texture Analysis Approach to Classify Breast Tumors in DCE-MRI Volumes", Biomedical Signal Processing & Control, 2024 (in revision).
