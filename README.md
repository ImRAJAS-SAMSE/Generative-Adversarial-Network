# 🧠 GAN-04-085: Comparative Study of GAN Variants on Medical Imaging (PathMNIST)

This project implements and compares the performance of **Vanilla GAN**, **Least Squares GAN (LSGAN)**, and **Wasserstein GAN (WGAN)** on the [PathMNIST](https://medmnist.com/) dataset, a benchmark medical image dataset from the **MedMNIST** collection.

The goal is to understand how different loss functions influence the generation quality of synthetic pathology images. The **Frechet Inception Distance (FID)** is used to evaluate the realism of generated images.

---

## 🧪 Features
- Uses **PyTorch** and **TorchMetrics** for building and training GANs.
- Implements:
  - **Vanilla GAN** using Binary Cross-Entropy Loss
  - **LSGAN** using Mean Squared Error Loss
  - **WGAN** using Wasserstein Loss
- Evaluates with **FID score** for each epoch
- Logs training with **TensorBoard**
- Trains on **PathMNIST**, a subset of MedMNIST

---


---

## ⚙️ Requirements

Install dependencies via:

```bash
pip install torch torchvision medmnist torchmetrics tensorboard
```

🚀 Running the Code
Option 1: Run in Google Colab (Recommended)
Run on Colab

Option 2: Run Locally
```bash
git clone https://github.com/KunalChitroda/gan-04.git
cd gan-04
jupyter notebook gan4-085.ipynb
```
