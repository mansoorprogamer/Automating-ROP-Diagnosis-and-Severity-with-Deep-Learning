# Automating ROP Diagnosis and Severity with Deep Learning  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

This project focuses on building an automated diagnostic system for Retinopathy of Prematurity (ROP) — a vision-threatening condition in premature infants. ROP remains a leading cause of childhood blindness, especially in low-resource regions where access to trained ophthalmologists is limited.

## 🚀 Project Overview

Retinopathy of Prematurity is caused by abnormal blood vessel development in the retina of premature infants. If not diagnosed and treated early, it can result in retinal detachment and permanent blindness. Early screening is critical, yet highly dependent on expert analysis of retinal images — something not widely available in many parts of the world.

This project proposes a deep learning-based solution to automate the detection and classification of ROP severity using retinal fundus images.

## 📊 Key Highlights

- Built and evaluated five deep learning models:
  - Custom CNN (achieved highest test accuracy of 98.48%)
  - ResNet (95.35%)
  - EfficientNet (96.07%)
  - Inception
  - VGG

- Used a Kaggle dataset of 6,004 fundus images, categorized into 11 ROP severity classes using expert diagnosis codes.
- Addressed severe class imbalance with data augmentation strategies to improve model generalization.
- The CNN architecture outperformed others with both high accuracy and stability across classes.
- Explored real-world use cases in telemedicine, clinical decision support, and mobile diagnostic tools.

## 💡 Why It Matters

In resource-limited or rural areas, ROP screening is often delayed or unavailable due to the lack of specialists. Our model offers a lightweight, scalable, and accessible diagnostic tool that can assist healthcare workers by providing fast and accurate predictions from retinal images — potentially preventing avoidable blindness.

## 🧠 Future Scope

- Integration of Explainable AI (XAI) for better interpretability
- Multi-modal learning with clinical features like gestational age and birth weight
- External dataset validation for robustness and real-world deployment
- Clinical Decision Support System (CDSS) integration

## 🔗 Dataset

Retinal images were sourced from a public Kaggle dataset:  
[Retinal Image Dataset of Infants and ROP](https://www.kaggle.com/datasets/jananowakova/retinal-image-dataset-of-infants-and-rop)

## 📚 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

Feel free to fork, contribute, and build on this work!
