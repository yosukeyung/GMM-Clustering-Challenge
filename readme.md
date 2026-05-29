# 🧬 Advanced Data Clustering with GMM 📊

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=flat&logo=numpy&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Type](https://img.shields.io/badge/Type-Group_Project-8A2BE2)

> **A sophisticated data mining project utilizing Gaussian Mixture Models (GMM) to uncover hidden patterns and segments within complex datasets.**
> _Created for a Data Science / AI Competition Challenge! 🏆_


## 📖 Project Overview

This repository contains my final submission for an AI competition. The project focuses on **unsupervised learning**, specifically using **Gaussian Mixture Models (GMM)**. Unlike standard K-Means, GMM provides a probabilistic approach to clustering, allowing for "soft" assignments and the ability to capture elliptical cluster shapes.

The workflow includes extensive data merging, preprocessing, and the implementation of a pre-trained GMM model to achieve high-precision clustering results.

## ✨ Key Features

- **Unsupervised Learning Excellence:** Implementation of Gaussian Mixture Models for robust data segmentation.
- **Data Integration Pipeline:** Seamless merging and cleaning of multiple data sources.
- **Model Persistence:** Uses serialized models (`.pkl`) for fast and efficient inference without retraining.
- **Probabilistic Insights:** Provides cluster membership probabilities, offering deeper insights than traditional hard-clustering methods.

## 🤝 My Role & Contributions

During this competition, my core responsibility was leading the **Modeling** phase. My specific contributions include:
- **Algorithm Design & Implementation:** Selecting and implementing the **Gaussian Mixture Model (GMM)** to effectively capture complex, non-linear relationships and overlapping segments within the dataset.
- **Model Training & Evaluation:** Fitting the model to the merged datasets, analyzing the probabilistic cluster assignments, and ensuring high-precision segmentation.
- **Model Serialization:** Exporting the finalized, trained model into a `ModelGMM.pkl` format to ensure seamless, efficient, and reproducible inference without the need for retraining during the evaluation phase.

## 🛠️ Tech Stack

- **Python** 🐍 (The core language)
- **Scikit-Learn** 🤖 (For GMM implementation and clustering metrics)
- **Pandas & NumPy** 🔢 (For advanced data manipulation)
- **Matplotlib/Seaborn** 🎨 (For data visualization)
- **Pickle** 🥒 (For model serialization/deserialization)

## 🚀 Getting Started

To explore or run this project locally, follow these steps:

### 1. Clone the Repo

```bash
git clone [https://github.com/yosukeyung/GMM-Clustering-Challenge.git](https://github.com/yosukeyung/GMM-Clustering-Challenge.git)
cd your-repo-name
```

### 2. Setup Environment

Ensure you have Python installed. Install the necessary libraries using pip:

```bash
pip install -r requirements.txt
```

### 3. Usage

1. Open the Jupyter Notebook:

```bash
jupyter notebook "main.ipynb"
```

2. Run the cells to see the data merging process, model loading, and clustering results.

3. The notebook will load ModelGMM.pkl to perform predictions on the processed dataset.

## 📂 Project Structure

- main.ipynb - Main notebook containing data preprocessing and clustering logic.

- ModelGMM.pkl - The trained Gaussian Mixture Model used for inference.

- merged_dataset_nodup_train.csv - Train Dataset

- merged_dataset_test_nodup.csv - Test Dataset

---

**Author:** Yosuke Yung
_CS Student @ BINUS UNIVERSITY_
