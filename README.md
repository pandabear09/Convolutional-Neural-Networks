# Convolutional-Neural-Networks
# 🧠 CNN Architectures & Custom Experiments

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)
[![TensorFlow / Keras](https://img.shields.io/badge/TensorFlow%20%2F%20Keras-2.x-FF6F00.svg?style=flat&logo=tensorflow)](https://www.tensorflow.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C.svg?style=flat&logo=pytorch)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A curated collection of **from-scratch Jupyter Notebook (`.ipynb`) implementations** covering foundational and modern Convolutional Neural Network (CNN) architectures, alongside original custom-designed architectures.

Each notebook is self-contained—walking through the intuition behind the paper, layer-by-layer architecture code, model summary, training loop, and evaluation metrics.

---

## 🎯 Repository Goals

* **Implement From Scratch:** Build iconic CNN papers line-by-line without relying on pre-built model zoos to deeply understand tensor shapes, receptive fields, and architectural bottlenecks.
* **Experiment & Innovate:** Design, train, and benchmark custom CNN topologies and hybrid convolutional blocks in isolated, reproducible notebooks.
* **Colab & Kaggle Ready:** Every `.ipynb` file is structured to run seamlessly on Google Colab or Kaggle GPUs with minimal setup.

---

## 🏛️ Implemented Architectures

### Classic & Foundational Models
| Architecture | Year | Key Innovation | Notebook | Status |
| :--- | :---: | :--- | :---: | :---: |
| **LeNet-5** | 1998 | First successful CNN for digit recognition | `classic/LeNet5.ipynb` | 📋 Planned |
| **AlexNet** | 2012 | ReLU, Dropout, overlapping max-pooling | `classic/AlexNet.ipynb` | ✅ Done |
| **VGG-16 / VGG-19** | 2014 | Deep stacks of uniform $3\times3$ convolutions | `classic/VGG16.ipynb` | 📋 Planned |
| **GoogLeNet (Inception-v1)** | 2014 | Parallel multi-scale filters & $1\times1$ bottlenecks | `classic/InceptionV1.ipynb` | 📋 Planned |
| **ResNet (18 / 34 / 50)** | 2015 | Residual skip connections to solve vanishing gradients | `classic/ResNet.ipynb` | 📋 Planned |

### Modern & Efficiency-Focused Models
| Architecture | Year | Key Innovation | Notebook | Status |
| :--- | :---: | :--- | :---: | :---: |
| **DenseNet-121** | 2016 | Dense feature concatenation across layers | `modern/DenseNet.ipynb` | 📋 Planned |
| **MobileNet (V1 / V2)** | 2017 | Depthwise separable convolutions & inverted residuals | `modern/MobileNet.ipynb` | 📋 Planned |
| **EfficientNet-B0** | 2019 | Compound scaling across depth, width, and resolution | `modern/EfficientNet.ipynb` | 📋 Planned |
| **ConvNeXt** | 2022 | Modernized ResNet inspired by Vision Transformers | `modern/ConvNeXt.ipynb` | 📋 Planned |

---

## 🧪 Custom & Experimental Architectures

This folder houses original CNN designs combining modern techniques (residual connections, squeeze-and-excitation attention, dilated convolutions, depthwise separable blocks) tested on benchmark datasets:

| Model Name | Core Idea / Design Notes | Dataset | Notebook |
| :--- | :--- | :---: | :---: |
| **`CustomNet-v1`** *(Template)* | Lightweight residual + channel attention blocks | CIFAR-10 | `custom/CustomNet_v1.ipynb` |

---

## 📂 Repository Structure

```text
├── classic/                 # Foundational CNN papers (LeNet, AlexNet, VGG, ResNet, etc.)
│   └── AlexNet.ipynb
├── modern/                  # Efficiency & modern CNNs (DenseNet, MobileNet, ConvNeXt, etc.)
├── custom/                  # Original, experimental CNN architectures & ablation studies
├── utils/                   # Optional helper notebooks for dataset prep & visualization
├── BENCHMARKS.md            # Detailed training logs, hyperparameters, and accuracy comparisons
└── README.md
