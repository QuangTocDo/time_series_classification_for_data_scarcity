# 📘 Abnormal Heartbeat Detection Under Limited Labeled Data Conditions

This project focuses on detecting abnormal heart rhythms (arrhythmias) from ECG time series signals under limited labeled data conditions. The notebook implements and compares multiple deep learning models to evaluate their robustness when only a small number of labeled samples are available.

---

## 🧠 Models Used
The following models are implemented and compared:

- **CNN + PPSN**
- **CNN**
- **PPSN (Perceptual Position-aware Shapelet Network)**

The models are trained and evaluated on the **MIT-BIH Arrhythmia Database**, re-split into multiple experimental cases with **641, 400, and 200 samples per class** to simulate data scarcity scenarios.

---

## 📌 Dataset
- **Source:** MIT-BIH Arrhythmia Database
- **Type:** 1D ECG time series
- **Task:** Time Series Classification (Normal vs Abnormal heartbeat)
- **Challenge:** Limited labeled training samples

---

## 📂 Project Structure
├── main.ipynb # Main notebook
├── shapelet_info/ # Shapelet data
└── data/ # ECG dataset (train/test splits for each case)

---

## ⚙️ How to Run on Google Colab

### ✅ Step 1 — Open the Notebook
Click the link below to run the notebook on Google Colab:

➡️ *Open `main.ipynb` on Google Colab* (insert your link here)

### ✅ Step 2 — Update Paths
Before running the code, modify the notebook to point to the correct directories:

- `shapelet_info` folder
- `data` folder for each case

### ✅ Step 3 — Run All Cells
Press:

Ctrl + F9 (Windows / Linux)
Cmd + F9 (macOS)

to **Run All** and execute the full experiment pipeline.

---

## 📊 Expected Output
The notebook provides:

- Training and validation accuracy
- Loss curves
- Model comparison across cases
- Evaluation under different levels of data scarcity

---

## 🧪 Future Improvements
- Apply data augmentation for ECG signals
- Integrate Transformer-based time series models
- Add Explainable AI (XAI) for medical interpretation
- Extend to multi-class arrhythmia classification

---

## 📎 References
- MIT-BIH Arrhythmia Database
- *Learning Perceptual Position-aware Shapelets for Time Series Classification (PPSN)*

---

## 📄 License
This project is for educational and research purposes only.

---

If this project helps your research, please ⭐ the repository. Thank you! 😄
