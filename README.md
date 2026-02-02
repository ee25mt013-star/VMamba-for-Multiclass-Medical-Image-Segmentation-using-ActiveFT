# VMamba-for-Multiclass-Medical-Image-Segmentation-using-ActiveFT


This project explores a data-efficient deep learning approach for multiclass
medical image segmentation using a VM-UNet architecture with a VMamba-based
encoder and ActiveFT sample selection.

---

## Project Overview
Medical image segmentation often requires large annotated datasets.
This work focuses on reducing annotation effort while maintaining
segmentation performance by combining:
- VMamba-based global context modeling
- U-Net style decoder
- ActiveFT-based informative sample selection

The approach is evaluated on the ACDC cardiac MRI dataset.

---

## Key Highlights
- Integrated VMamba-Small encoder into a U-Net architecture
- Applied ActiveFT to select a diverse 20% subset of training data
- Reduced annotation effort by ~80%
- Achieved Mean Dice Score of **0.7515** on the selected subset

---

## Dataset
- ACDC (Automated Cardiac Diagnosis Challenge) dataset  
- Dataset is **not included** in this repository due to licensing constraints  
- Dataset paths can be configured inside the notebooks

---

## Tools & Frameworks
- Python
- PyTorch
- VMamba
- NumPy, Matplotlib, OpenCV
- Google Colab

---

## Results
- Mean Dice Score: **0.7515**
- Stable performance with significantly reduced training data
- Demonstrates effectiveness of ActiveFT for data-efficient training

---

## Author
Chamakuri Sowjanya  
M.Tech CSPML, IIT Dharwad
