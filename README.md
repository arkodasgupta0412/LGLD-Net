# LGD-Net

**LGD-Net** is a lightweight Local-Global Dual-stream neural network designed for efficient and accurate medical image classification. It combines a **Local Feature Aggregator (LFA)** for fine-grained textures, a **Global Context Encoder (GCE)** for long-range dependencies, and an **Adaptive Fusion Module**, all in just **161K parameters**, achieving state-of-the-art performance across multiple benchmark datasets.

---

## Abstract

Microscopic image analysis provides vital information at the cellular level. However, most deep learning models struggle to jointly capture fine-grained and global features and often remain computationally expensive. To this end, we propose a compactly designed **lightweight model (161K parameters)**, called **Lightweight Global and Local feature-based Dual-stream Neural Network (LGLD-Net)**. Here, we use an involution-based patch stem to capture fine-grained local textures and a Fourier-based global stream to model long-range dependencies and contextual features. Then, an adaptive fusion module is added that dynamically balances local and global features for optimal feature representations. The proposed LGLD-Net yields state-of-the-art performance on two microscopic image datasets, **Acute lymphoblastic leukemia (ALL) and Raabin-WBC**, achieving classification accuracies of **99.69%** and **96.50%**, respectively. The proposed model is evaluated on multiple hardware platforms, including the **Raspberry Pi 5** for CAD applications, achieving **17.56 FPS** with a computational cost of only **1.88 GFLOPs**.

---

## Our Contributions

– An **involution-based patch stem (IPS)** to capture fine-grained local textures.

– A **Fourier-based (FFM)** global stream to model long-range dependencies and contextual features.

– **Local Feature Aggregator (LFA)** and **Global Context Extractor (GCE)**.

– An **adaptive fusion module (LGFM)** that dynamically balances local and global features for optimal representation.

– A compactly designed lightweight model (161K parameters) that achieves notable performances across two standard datasets, namely ALL and Raabin-WBC.

– Achieves real-time inference on edge devices like **Raspberry Pi 5** with only **1.88 GFLOPs**, enabling efficient deployment in resource-constrained environments.

---

## Keywords

**Microscopic Image Classification** · **Lightweight CNN** · **Local and Global Features** · **Dual-branch Neural Network**

## Model Architecture

![Architecture](https://github.com/arkodasgupta0412/LGLD-Net/blob/main/figures/LGLDNet_pipeline.jpg)
