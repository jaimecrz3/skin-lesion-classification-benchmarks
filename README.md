# Skin Lesion Classification Benchmarks (Melanoma Detection)

This repository contains a comparative study of deep learning approaches for dermoscopic skin lesion classification:
**nevus / melanoma / seborrheic keratosis**.

The project includes:
- **Self-Supervised Vision Transformer (DINO)**: linear probe + fine-tuning pipeline
- **Supervised Vision Transformer baseline**
- **CNN Transfer Learning baselines** (e.g., AlexNet, EfficientNet)
- Final **project report** (memory) summarizing methodology and results

---

## Dataset

We use the Kaggle dataset:
**Skin Lesion Analysis Toward Melanoma Detection**  
(nevus / melanoma / seborrheic keratosis)

---

### Reproducibility Notes

- Results may vary slightly due to random initialization and data loader ordering.

- For reproducible runs, set seeds (PyTorch/NumPy) and fix deterministic flags where possible.
