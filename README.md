# 🔐 Fidelity-Gated Augmentation and Robustness-Aware Filtering for Explainable Hybrid Transformer-LSTM Intrusion Detection in IoT Networks

This project presents a secure hybrid Transformer-LSTM intrusion detection framework evaluated alongside a standalone LSTM. It introduce a fidelity-gated adaptive augmentation framework that computes a per-class fidelity score. To secure edge-deployed models, it integrate a robustness-aware synthetic filter that evaluates adversarial stability prior to training, and employ **SHAP** (SHapley Additive exPlanations) to measure explanation stability and faithfulness under attack conditions. 

---

## 📘 Overview

- **Objective**: Verify synthetic data fidelity before augmentation and examine how synthetic artifacts can degrade the adversarial robustness of lightweight hybrid models.
- **Optimization**: A fidelity-gated adaptive augmentation framework and a robustness-aware synthetic filter
- **Robustness**: Two adversarial attacks (FGSM & PGD) were used to test model robustness.
- **Explainability**: SHAP was used to interpret model decisions and measure explanation stability and faithfulness.

---

## 📂 File

- `Main.ipynb`: Jupyter Notebook containing the full model training, optimization, and explanation workflow.

---

## ▶️ Run on Google Colab

Click the badge below to open and run the full notebook in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fu4RqnIMkGZKQpFTNEPww51II3UhRJQf#scrollTo=Pp7fMWQwICvn)

> ⚠️ **Note**: GitHub’s notebook preview may not render dynamic elements like SHAP’s HTML output.  
> Please use the Colab link above to view the notebook with full code execution and interactive visualizations.

---

## 🛠️ Technologies Used

- Python 3.x  
- TensorFlow / Keras
- FGSM & PGD
- SHAP  
- Google Colab

---

## 🧠 Authors

- Taiwo Blessing Ogunseyi
- Gogulakrishnan Thiyagarajan
- Vinay Bist
- Du Zhengcong


---

## 📄 License

This project is for academic and research purposes only. 

