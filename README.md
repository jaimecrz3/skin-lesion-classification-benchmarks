# Skin Lesion Classification Benchmarks (Melanoma Detection)

This repository contains a comparative study of deep learning approaches for dermoscopic skin lesion classification:
**nevus / melanoma / seborrheic keratosis**.

---

# Abstract

Early detection of Melanoma is a critical factor in reducing skin cancer mortality rates. While Deep Learning has shown promise in automated diagnosis, achieving a balance between high sensitivity and specificity remains a challenge due to class imbalance and the visual similarity between malignant and benign lesions. In this work, we present a comprehensive comparative study between **Convolutional Neural Network models** (EfficientNetB4, Inception-ResNet-v2) and **Transformer-based architectures** (ViT, ViT+DINO) using the **ISIC 2017 dataset**. We employ a rigorous training protocol utilizing the One Cycle Policy and data augmentation. Our experiments reveal a distinct trade-off: while ViT-based models demonstrate superior global performance (Accuracy: 76.67\%, ROC-AUC: 0.8268) and robustness against class imbalance, traditional CNNs like Inception-ResNet-v2 achieve higher raw sensitivity (Recall: 0.70) at the cost of increased false positive rates. Furthermore, we analyze the impact of self-supervised learning (DINO) and decision thresholds, providing insights into the optimal operating points for clinical decision support.

---

### Reproducibility Notes

- Results may vary slightly due to random initialization and data loader ordering.

- For reproducible runs, set seeds (PyTorch/NumPy) and fix deterministic flags where possible.
