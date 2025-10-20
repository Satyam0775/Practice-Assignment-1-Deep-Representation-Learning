# 🧠 Practice Programming Assignment 1 — Advanced Deep Representation Learning
**Author:** Satyam Kumar  
**Instructor:** Prof. Prathosh A. P.  
**Date:** August 17, 2025  

---

## 📘 Overview
This repository contains **training outputs and final results** for Practice Programming Assignment 1, part of the *Advanced Deep Representation Learning* course under **Prof. Prathosh A. P.** (IISc, Bangalore).

The complete Colab notebooks and generated datasets are hosted on Google Drive due to large file sizes.

---

## 📦 Full Project Files
📂 **All Code & Outputs (Colab Notebooks, Models, and Results)**  
👉 [Google Drive Folder — Practice Assignment 1](https://drive.google.com/drive/folders/1CH1Mnb0XKZ35ViY8d6HwWZLDo2i51blg?usp=sharing)

📂 **Dataset Used (90-Class Animal Dataset)**  
👉 [Animals Dataset — 5400 Images / 90 Classes](https://drive.google.com/drive/folders/1j7PKfBHM1at2PckyFLol8WC6igD5EsTW)

---

## 🧩 Tasks Implemented

| Task | Description | Key Result |
|------|--------------|-------------|
| **1–5** | DCGAN Training, Loss Curves, FID, and Latent Traversals | FID: 186.26 |
| **6** | Conditional GAN (20 Random Classes) | Class-conditioned image generation |
| **7** | ResNet Fine-tuning (90-Class Dataset) | Accuracy: 99.78% |
| **8** | ResNet Fine-tuning (20-Class Subset) | Accuracy: 100.00% |
| **9** | Retraining on GAN-Augmented Data | Accuracy: 40.75%, F1: 0.460 |

---

## 📊 Key Results

| Metric | Task 7 | Task 8 | Task 9 |
|---------|---------|---------|---------|
| **Accuracy (%)** | 99.78 | 100.00 | 40.75 |
| **F1 Score** | 0.998 | 1.000 | 0.460 |

---

## 🎨 Visual Results
All plots and generated samples are available in the `Results/` folder:
- DCGAN Loss Curves & Grids  
- Conditional GAN 20-Class Outputs  
- Latent Space Interpolations  
- Classifier Performance Comparison  

---

## ⚙️ Environment
- **Platform:** Google Colab (Free GPU)
- **Framework:** PyTorch 2.x
- **Libraries:** Torchvision, Scikit-learn, CleanFID, Matplotlib

---

## 🚀 How to Run
1. Open the provided `.ipynb` file in **Google Colab**.  
2. Mount Google Drive and set:
   ```python
   data_dir = "/content/drive/MyDrive/TASK 1/animals"
   
Run all cells sequentially to reproduce the full experiment.

Generated results will be saved automatically to Drive.

🧑‍🎓 Author’s Note

This project demonstrates a full deep representation workflow using DCGAN, Conditional GAN, and ResNet classifiers.
It highlights how GAN-based augmentation can diversify datasets but affects accuracy depending on image fidelity.
