# Multimodal Analysis of Parkinson's Disease using MRI and EEG: A Deep Learning Approach

## Overview

This repository contains the source code developed for the undergraduate thesis **"Multimodal Analysis of Parkinson's Disease using MRI and EEG: A Deep Learning Approach."**

The project investigates the use of deep learning and machine learning techniques for Parkinson's disease classification using two complementary modalities:

* **MRI (Magnetic Resonance Imaging)**
* **EEG (Electroencephalography)**

Six deep learning and machine learning models were implemented and evaluated to compare their performance across these modalities.

---

## Repository Structure

```text
ResNet-18/          # MRI classification using ResNet-18
CNN/                # MRI classification using a Convolutional Neural Network
CNN-Transformer/    # MRI classification using a CNN-Transformer hybrid
EEGNet/             # EEG classification using EEGNet
Random-Forest/      # EEG feature-based classification using Random Forest
XGBoost/            # EEG feature-based classification using XGBoost
```

---

## Contributors

| Model           | Contributor             |
| --------------- | ----------------------- |
| ResNet-18       | Rekha Rawal             |
| CNN             | Priyasha Chaudhary      |
| CNN-Transformer | Dipti Sunayana Bartaula |
| EEGNet          | Khushi Barali B.K.      |
| Random Forest   | Prajwal Bhattarai       |
| XGBoost         | Samip Thapa             |

---

## Datasets

The datasets used in this project are **not included** in this repository. Please obtain them from their original sources and comply with the respective dataset licenses.

* MRI Dataset

**Parkinson's Progression Markers Initiative (PPMI)**

Website: https://www.ppmi-info.org/

* EEG Dataset (EEGNet)

**OpenNeuro – UC San Diego**

DOI: **10.18112/openneuro.ds002778.v1.0.5**

* EEG Dataset (Random Forest & XGBoost)

**OpenNeuro – University of Iowa**

DOI: **10.18112/openneuro.ds004584.v1.0.0**

---

## License

This repository contains only the implementation code developed for academic and research purposes.

The datasets used in this project are distributed under their respective licenses and are **not included** in this repository. Please refer to the original dataset providers for licensing terms and conditions.
