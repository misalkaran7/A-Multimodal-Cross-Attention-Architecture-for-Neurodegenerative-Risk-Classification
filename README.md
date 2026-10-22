# A-Multimodal-Cross-Attention-Architecture-for-Neurodegenerative-Risk-Classification
Multimodal deep learning for neurodegenerative risk classification using brain MRI-derived features and clinical biomarkers. This project uses a cross-attention architecture and the OASIS-2 dataset, achieving 89.4% accuracy and 94.2% AUROC, with comparisons against traditional machine learning models and feature importance analysis.

# Multimodal Neurodegenerative Risk Classification

### A Cross-Attention Architecture Using Brain MRI and Clinical Biomarkers

## 📌 Overview

This project presents a multimodal deep learning framework for neurodegenerative risk classification by combining structural brain MRI-derived features with clinical and demographic biomarkers. Using the OASIS-2 dataset, the proposed cross-attention architecture aims to capture relationships between neuroimaging and clinical information to improve classification performance.

## 🎯 Objectives

- Integrate MRI-derived features with clinical and demographic data.
- Develop a cross-attention-based multimodal classification architecture.
- Compare the proposed model against traditional machine learning baselines.
- Analyze feature importance to improve model interpretability.
- Evaluate performance using standard classification metrics.

## 🧠 Methodology

1. **Data Collection:** Use the OASIS-2 dataset.
2. **Preprocessing:** Prepare and organize imaging-derived and clinical features.
3. **Feature Integration:** Combine modalities through a cross-attention architecture.
4. **Model Training:** Train the proposed model for neurodegenerative risk classification.
5. **Baseline Comparison:** Evaluate Logistic Regression and Random Forest models.
6. **Evaluation:** Measure accuracy, macro F1-score, and AUROC.
7. **Interpretability:** Analyze the contribution of clinical and neuroimaging biomarkers.

## 📊 Results

| Metric | Proposed Model |
|---|---:|
| Accuracy | 89.4% |
| Macro F1-score | 87.4% |
| AUROC | 94.2% |

The proposed model outperformed the traditional machine learning baselines evaluated in this study.

## 🛠️ Technologies

- Python
- Deep Learning
- Machine Learning
- Multimodal Learning
- Cross-Attention
- Medical Data Analysis
- Data Visualization

## 🔍 Key Findings

Feature importance analysis identified MMSE, education level (EDUC), and normalized whole-brain volume (nWBV) as influential features in the evaluated model.

## 🚀 Future Scope

- Validate performance on independent datasets.
- Explore more efficient multimodal fusion strategies.
- Improve model interpretability.
- Evaluate generalization across different patient populations.

## ⚠️ Disclaimer

This project is intended for academic research and experimentation. The model has not been clinically validated and must not be used as a standalone diagnostic tool.

## 👩‍💻 Authors

**Gargi Balamwar** and **Karan Misal**

