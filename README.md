# HyperTTA
# HyperTTA: Test-Time Adaptable Transformer for Hyperspectral Degradation

This repository contains the official implementation of **HyperTTA**, a unified framework designed to enhance the robustness of hyperspectral image (HSI) classification models under diverse real-world degradations, including noise, blur, compression, and atmospheric interference.

---

## 🌟 Highlights

- **Multi-Degradation Dataset**: We construct a benchmark dataset simulating 9 types of realistic HSI corruptions.
- **Spectral–Spatial Transformer Classifier (SSTC)**: A powerful backbone enhanced with multi-level receptive fields and label smoothing.
- **Confidence-aware Entropy-minimized LayerNorm Adapter (CELA)**: A lightweight test-time adaptation (TTA) module that updates only LayerNorm parameters using high-confidence target samples.

---

