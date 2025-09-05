# anomaly_detection_research
Final project: research from my higher education. I aimed to determine if anomaly detectors in industrial control systems (ICSs) based on spiking neural networks (SNNs) outperform those using other machine learning (ML) and deep learning (DL) algorithms. 

Reports and presentations were created for academic evaluation purposes

# 🧠 Anomaly Detection in Industrial Control Systems (ICS) using Spiking Neural Networks (SNN)

This repository contains my **final academic project**, where I explored the use of **Spiking Neural Networks (SNNs)** for anomaly detection in Industrial Control Systems (ICS).  

The goal was to compare SNNs against traditional **Machine Learning (ML)** and **Deep Learning (DL)** models across several benchmark datasets, and to investigate whether hybrid approaches (SNN + other algorithms) can improve detection performance.

---

## 📂 Repository Structure

- **`ecg5000_simple_dataset_on_snn.ipynb`** – experiment with the ECG5000 dataset using SNN.  
- **`iso_forest_swat.ipynb`** – Isolation Forest applied to the SWaT dataset.  
- **`SVM_and_Random_Forest.ipynb`** – baseline models (Support Vector Machine & Random Forest).  
- **`wadi_snn.ipynb`** – SNN applied to the WADI dataset.  
- **`batadal_klawdii_updated.ipynb`** – experiments with the BATADAL dataset using SNN.  

Additional files (PDFs & PPTX) contain the **final report, poster, and presentation** that summarize the research and results.

---

## ⚙️ Models Compared

- **Classical ML**:  
  - Support Vector Machine (SVM)  
  - Random Forest  
  - Isolation Forest  

- **Deep Learning**:  
  - Standard neural architectures (baselines)  

- **Spiking Neural Networks (SNN)**:  
  - Implemented on multiple datasets (SWaT, WADI, BATADAL, ECG5000)  

---

## 📊 Key Findings

- **SNNs alone** face challenges due to **training complexity** and **limited available research resources**.  
- **Traditional ML models** (SVM, RF, Isolation Forest) provide strong baselines.  
- **Best results** were obtained when combining SNNs with other algorithms, leveraging the strengths of both approaches.  

---

🛠️ Technologies Used

Python

Jupyter Notebook

scikit-learn

PyTorch / SNN libraries

📚 Status

This project was completed as part of my final academic assignment.
It demonstrates the challenges and potential of SNNs for anomaly detection in ICSs and highlights promising directions for hybrid approaches.
