# Wearable Risk Ensemble  
**Hybrid Ensemble Models for Early Risk Detection in Wearable Health Tech**  
*A research collaboration by Sonny Marmon & Harshith Guduru*

---

## Project Overview

This project leverages **hybrid ensemble machine learning models** to predict early-stage health risks using real-world data from wearable devices. By fusing biosignals such as ECG, PPG, and accelerometry from the [DREAMT Dataset (PhysioNet)](https://physionet.org/content/dreamt), we aim to build a scalable, interpretable framework for early health event detection and wellness insights.

## Dataset

We use the **DREAMT Dataset**, a publicly available multi-sensor dataset for sleep stage classification, which serves as a strong proxy for cardiovascular, metabolic, and neurological health indicators.

**Features include**:
- Electrocardiogram (ECG)
- Photoplethysmography (PPG)
- Accelerometry (x/y/z)
- Sleep stage labels

 [Access the dataset via PhysioNet](https://physionet.org/content/dreamt)

---

##  Project Structure

##  Methodology

We develop and benchmark a **hybrid ensemble learning pipeline** using:

-  Gradient Boosted Trees (XGBoost)
-  Temporal Convolutional Networks (TCNs)
-  LSTM-RNNs
-  Soft Voting / Stacked Ensemble

Each model is evaluated using:
- Accuracy
- Precision/Recall
- F1-Score
- ROC-AUC
- Class-wise confusion matrix

---

## Goals

- Detect early physiological deviations linked to potential risks
- Build a transparent and explainable ML system for wearable health insights
- Optimize for deployment on low-power edge devices (future work)

---

## Ethics & Data Privacy

This project uses **open-source, de-identified data** only. No private medical data is accessed. All experiments comply with open-data licensing and research reproducibility principles.

---

## Authors

- **Sonny Marmon**  
  Student Researcher | AI, Quantum Systems, MS&E  
  [LinkedIn](https://www.linkedin.com/in/sonnymarmon) • [Website](https://sonnymarmon.com)

- **Harshith Guduru**  
  Research Intern @ Walmart Global Tech | Published in *Science* under *Nature*  
  [LinkedIn](https://www.linkedin.com/in/harshithguduru)

---

##  License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.

---

##  Citation (APA)

Marmon, S., & Guduru, H. (2025). *Hybrid Ensemble Models for Early Risk Detection in Wearable Health Tech*. GitHub. https://github.com/sonnymarmon/wearable-risk-ensemble

---

##  Acknowledgements

- [PhysioNet / DREAMT Team](https://physionet.org)

