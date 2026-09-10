# 🔐 An Explainable Hybrid Transformer-LSTM Intrusion Detection for IoT Network: A Fidelity-Aware Evaluation of GAN Augmentation and Adversarial Robustness

This project presents a hybrid DL-based intrusion detection architecture for IoT networks using Transformer and Long Short-Term Memory (LSTM) neural networks. The WGAN-GP was deployed for data augmentation and three adversarial attacks (FGSM, PGD, & C&W) for model robustness. It also utilizes **SHAP** (SHapley Additive exPlanations) to provide explanation for individual predictions and evaluate model's stability and faithfulness under different adversarial conditions.

---

## 📘 Overview

- **Objective**: Detect anomalous traffic in IoT environments using a hybrid Transformer-LSTM framework benchmarked against a standalone LSTM.
- **Optimization**: The WGAN-GP algorithm was used to augment data and improve class imbalance.
- **Robustness**: Three adversarial attacks (FGSM, PGD, C&W) were used to test model robustness.
- **Explainability**: SHAP is used to interpret model decisions on a per-instance basis.

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
- FGSM, PGD, & C&W (custom implementation)   
- SHAP  
- Google Colab

---

## 🧠 Authors

- Taiwo Blessing Ogunseyi
- Gogulakrishnan Thiyagarajan  


---

## 📄 License

This project is for academic and research purposes only. 

