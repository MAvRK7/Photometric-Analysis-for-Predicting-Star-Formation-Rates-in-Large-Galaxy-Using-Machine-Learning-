# 🌌 Advanced Photometric Analysis for Predicting Specific Star Formation Rates in Large Galaxies

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)]()
[![Framework](https://img.shields.io/badge/Framework-PyTorch%20%7C%20Scikit--Learn-orange)]()
[![Dataset](https://img.shields.io/badge/Dataset-SDSS--DR7-lightgrey)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()

---

## 📌 Overview
This project investigates the use of **Generative Adversarial Networks (GANs)**, **Conditional GANs (CGANs)**, and **Contrastive GANs (ContraGANs)** to generate synthetic astronomical data for predicting the **B‑V colour index** — a key parameter in estimating **specific star formation rates (sSFR)** in large galaxies.

Models were evaluated on:
- **Predictive Accuracy** (MSE, R²)
- **Clustering Quality** (Silhouette, Calinski‑Harabasz, Davies‑Bouldin)
- **Statistical Alignment** (Wasserstein Distance, Kolmogorov‑Smirnov)

**Key Result:**  
**ContraGAN** achieved the best performance with:
- **MSE:** 0.1294  
- **R²:** 0.7258  
- Superior clustering and statistical alignment scores

These findings highlight the advantages of **contrastive learning** and **conditional generation** for high‑fidelity synthetic data in both scientific and industrial contexts.

---

## 🛰 Data Source
- **Photometric data from over 27 million galaxies** collected by the **Sloan Digital Sky Survey – Data Release 7 (SDSS‑DR7)**

---

## ⚙️ Algorithms Implemented
In addition to adversarial models, the following regression algorithms were implemented for comparative analysis:

- Linear Regression  
- Long Short‑Term Memory (LSTM) Networks  
- Support Vector Regression (SVR)  
- Random Forest Regressor  
- Decision Tree Regressor  
- Gradient Boosting Regressor  
- Classical Deep Learning Models

---

## 📊 Performance Metrics
- **Regression:** Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score  
- **Clustering:** Silhouette Score, Calinski‑Harabasz Score, Davies‑Bouldin Score  
- **Statistical Alignment:** Wasserstein Distance, Kolmogorov‑Smirnov Statistic

---

## 🔍 Comparative Analysis
| Model       | MSE     | R²     | Clustering Quality | Statistical Alignment |
|-------------|---------|--------|--------------------|-----------------------|
| GAN         | Higher  | Lower  | Moderate           | Moderate              |
| CGAN        | Lower   | Higher | Good               | Good                  |
| **ContraGAN** | **0.1294** | **0.7258** | **Best**            | **Best**              |

---

## 🤝 Contributing
Contributions are welcome!  
- Fork the repository  
- Create a feature branch  
- Submit a pull request  
- Or open an issue for suggestions and improvements

---

## 📬 Contact
**Satvik Raghav**  
📧 [satvikraghav007@gmail.com](mailto:satvikraghav007@gmail.com)

---

## 💡 Skills Demonstrated
- Advanced deep learning (GAN, CGAN, ContraGAN)
- Regression modelling (classical + deep learning)
- Large‑scale astronomical data preprocessing
- Multi‑metric model evaluation
- Comparative research methodology
