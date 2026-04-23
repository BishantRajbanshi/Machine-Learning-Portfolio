# Machine Learning Portfolio

> End-to-end machine learning projects — from raw data to deployed models.

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.x-orange?logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red?logo=pytorch&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

## Overview

This repository is a collection of machine learning projects that demonstrate practical skills across the full ML lifecycle — data preprocessing, feature engineering, model development, evaluation, and deployment.

Each project is self-contained with its own data pipeline, notebooks, and documented results.

---

## Projects

| Project | Domain | Techniques | Status |
|---|---|---|---|
| [Handwritten Digit Recognition](./projects/image-classification/) | Computer Vision | Keras, TensorFlow, FCN, MNIST, Devnagari | Completed |

---

## Repository Structure

```
machine-learning-portfolio/
│
├── datasets/                  # Raw and processed datasets
├── notebooks/                 # Exploratory and experimental notebooks
│
├── src/                       # Shared source code
│   ├── data/                  # Data loading and preprocessing
│   ├── models/                # Model definitions and architectures
│   ├── training/              # Training loops and pipelines
│   └── utils/                 # Helpers, metrics, visualization
│
├── projects/                  # Individual end-to-end projects
│   └── image-classification/
│
├── deployment/                # Model serving and API code
└── docs/                      # Documentation and write-ups
```

---

## Skills Demonstrated

- **Data** — Cleaning, EDA, image preprocessing, normalization
- **Modeling** — Fully Connected Networks (FCN), Keras, TensorFlow
- **Datasets** — MNIST, Devnagari Handwritten Digit
- **Evaluation** — Accuracy, categorical cross-entropy, loss analysis

---

## Setup

```bash
git clone https://github.com/BishantRajbanshi/machine-learning-portfolio.git
cd machine-learning-portfolio
pip install -r requirements.txt
```

---

## Author

**Bishant Rajbanshi**
- GitHub: [@BishantRajbanshi](https://github.com/BishantRajbanshi)
- LinkedIn: [Bishant Rajbanshi](https://linkedin.com/in/bishant-rajbanshi)

---

## License

This project is licensed under the [MIT License](./LICENSE).
