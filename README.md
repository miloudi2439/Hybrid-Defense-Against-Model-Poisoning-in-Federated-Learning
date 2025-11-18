# Hybrid Defense Against Model Poisoning in Federated Learning
*A Two-Stage Anomaly Detection + Random Partial Aggregation Framework*

This repository contains the official Jupyter notebooks accompanying the paper:

**"A Resilient Hybrid Mechanism for Protecting Healthcare Data from Model Poisoning in Federated Learning"**  
(To appear in **ICFNDS 2025**)

The method introduces a **hybrid two-layer defense** for Federated Learning (FL):

1. **Statistical Anomaly Detection** (filter out abnormal or malicious updates)  
2. **Randomized Partial Aggregation (RPA)** (minimize impact of subtle poisoning)

The approach is lightweight, model-agnostic, and designed for secure training across hospitals and medical institutions.

> 🔒 **Note:**  
> The repository is private until the paper is formally published.  
> It will be made **public immediately after publication**, in accordance with conference policies.

---

## 📁 Repository Structure

This repo is intentionally simple and contains **two primary notebooks**:

```bash
├── MNIST_Hybrid_Defense.ipynb           # Experiments on classic MNIST dataset
├── PneumoniaMNIST_Hybrid_Defense.ipynb  # Experiments on MedMNIST Pneumonia dataset
├── requirements.txt                     # (Optional) dependencies list
└── README.md
