# Vision Transformer (ViT) from Scratch on CIFAR-10 🔥

This repository contains a **from-scratch PyTorch implementation of a Vision Transformer (ViT)** trained on the **CIFAR-10** dataset.  
All core components of ViT — including **patch embedding, multi-head self-attention, transformer encoder blocks, and class token** — are implemented manually without using high-level ViT libraries.

---

## 🚀 Project Highlights

- ✅ Vision Transformer implemented **from scratch**
- ✅ Custom **Patch Embedding** using Conv2D
- ✅ Multi-Head Self-Attention (MHSA)
- ✅ Pre-Norm Transformer Encoder Blocks
- ✅ Truncated Normal weight initialization (ViT-style)
- ✅ Cosine Annealing Learning Rate Scheduler
- ✅ Data augmentation for CIFAR-10
- ✅ Training & evaluation pipeline
- ✅ Visualization of predictions vs ground truth

---

## 🧠 Model Architecture

- **Input Image Size:** 32×32 (CIFAR-10)
- **Patch Size:** 4×4 → 64 patches
- **Embedding Dimension:** 192
- **Transformer Depth:** 6 blocks
- **Attention Heads:** 6
- **MLP Ratio:** 4
- **Classifier Token:** ✔️
- **Positional Embedding:** Learnable

---

## 📊 Training Results

| Epochs | Best Test Accuracy |
|------|--------------------|
| 5    | **56.86%** |

> ⚠️ Note: This accuracy is achieved with a **small ViT trained for only 5 epochs**.  
> Higher accuracy can be obtained by increasing depth, embedding size, epochs, or using longer training schedules.

---

## 🖼️ Sample Prediction

The model correctly predicts the class of unseen test images:
Ground Truth: frog
Prediction: frog


