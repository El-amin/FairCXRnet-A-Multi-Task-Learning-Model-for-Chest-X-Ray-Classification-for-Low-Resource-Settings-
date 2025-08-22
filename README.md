# FairCXRnet

**FairCXRnet: A Multi-Task Learning Model for Domain Adaptation in Chest X-Ray Classification for Low Resource Settings**

---

##  Overview
This repository contains the official implementation of airCXRnet, a multi-task deep learning model designed for domain adaptation in chest X-ray (CXR) classification. The model addresses challenges in low-resource settings by improving generalization, fairness, and robustness** across underrepresented populations and diverse imaging domains.

FairCXRnet integrates:
- **Multi-task learning** (classification + domain alignment tasks)
- **Domain adaptation** strategies to handle dataset shift
- **Fairness-aware components** for equity across demographic groups

This code accompanies our paper:  
> **FairCXRnet: A Multi-Task Learning Model for Domain Adaptation in Chest X-Ray Classification for Low Resource Settings**  
> *Aminu Musa, Rajesh Prasad, Mohammed Hassan, Mohamed Hamada, Saratu Yusuf Ilu*  
> (2025, ETLTC Conference, Japan)

---

## ⚙️ Features
- Multi-task training framework with **shared backbone + task-specific heads**  
- Support for **multi-label classification** (e.g., ChestMNIST, NIH CXR, local datasets)  
- Domain adaptation using **adversarial training & feature alignment**  
- Evaluation pipeline for **cross-domain generalization**  
- Fairness-aware analysis (demographic and dataset-level performance evaluation)

---

## 📂 Repository Structure

FairCXRnet/
│── data/ # Dataset loading & preprocessing scripts
│── models/ # Model architectures (FairCXRnet, DenseNet, etc.)
│── training/ # Training loops, losses, domain adaptation strategies
│── evaluation/ # Evaluation, fairness metrics, visualization
│── utils/ # Helper functions
│── configs/ # Config files for experiments
│── main.py # Entry point to train/evaluate the model
│── requirements.txt # Dependencies
│── README.md # Project documentation (this file)
FairCXRnet shows:

---

📊 Results
Improved cross-domain generalization compared to single-task baselines
Enhanced fairness performance across underrepresented groups
Robust multi-label classification on diverse datasets
(Full results and ablation studies available in the paper.)

---

**Citation**

If you use this code or our model in your research, please cite:
@article{musa2025faircxrnet,
  title={FairCXRnet: A Multi-Task Learning Model for Domain Adaptation in Chest X-Ray Classification for Low Resource Settings},
  author={Musa, Aminu and Prasad, Rajesh and Hassan, Mohammed and Hamada, Mohamed and Ilu, Saratu Yusuf},
  year={2025},
  journal={EngrProc. MDPI},
}
