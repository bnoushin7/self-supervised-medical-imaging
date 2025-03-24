# SimMIM with MONAI for Self-Supervised Learning on 3D Medical Images

This repository implements [SimMIM (Simple Masked Image Modeling)](https://arxiv.org/abs/2111.09886) using [MONAI](https://monai.io/), tailored for self-supervised representation learning on 3D medical imaging data.

> ⚠️ This is a research/experimental notebook primarily run in Google Colab.

---

## 🧠 What is SimMIM?

SimMIM is a self-supervised learning method that trains a vision transformer (ViT) to reconstruct masked patches of an image. This project adapts that approach for 3D volumetric medical images using MONAI and PyTorch.

---

## 📁 Files

- `data_utils_colab_final_backup.ipynb`: Main Colab notebook with SimMIM implementation using MONAI.

---

## 🚀 Getting Started

To run this notebook:

1. Open it in **Google Colab**.
2. Make sure to enable GPU runtime.
3. Install MONAI and dependencies:
   ```bash
   pip install monai[all] torch torchvision
