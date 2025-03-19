 # 🖼️ Optimized semantic feature extraction (OSFE) for Zero-Shot Image Classification

This repository contains the implementation of our **Zero-Shot Image Classification** model based on the Hybrid Feature Approach (HFA). The method leverages **Deep Spatial Features, Multi-Scale Texture Features, and optimized semantic embeddings (GloVe + Autoencoder)** to enhance classification performance.

---

## 🚀 Features

- Zero-shot classification using **Hybrid Feature Approach (HFA)**
- Utilizes **CNN-extracted visual features** and **optimized semantic features**
- **Autoencoder-based feature selection** for improved efficiency
- Supports datasets like **CUB-200, AwA2, and SUN Attribute Dataset**
- Efficient **training and inference** with reduced computational cost

---

## 📁 Dataset

The model supports **publicly available benchmark datasets** for Zero-Shot Learning:

1. **CUB-200-2011** - [Download](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html)
2. **Animals with Attributes 2 (AwA2)** - [Download](https://cvml.ista.ac.at/AwA2/)
3. **SUN Attribute Database** - [Download](https://cs.brown.edu/~gmpatter/sunattributes.html)

Ensure that datasets are correctly formatted before training.

---

## 🔧 Installation

### Prerequisites

- Python 3.8+
- PyTorch
- TensorFlow (optional, if using certain embeddings)
- NumPy, Pandas, Matplotlib
- Scikit-learn

### Install Dependencies

```bash
pip install -r requirements.txt
