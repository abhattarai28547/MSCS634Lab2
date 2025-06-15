# MSCS634Lab2 - KNN and RNN Classification on the Wine Dataset

**Name:** Avinna Bhattarai  
**Course:** MSCS 634 - Big Data and Data Mining  
**Lab Assignment:** Lab 2 - Classification Analysis  

---

##  Purpose

This lab explores two classification algorithms — **K-Nearest Neighbors (KNN)** and **Radius Neighbors (RNN)** — using the Wine dataset. It aims to understand how different values of `k` and `radius` affect classification accuracy and help in choosing optimal parameters.

---

##  Key Insights

- **KNN** performed best at `k = 1` and `k = 21`, both yielding an accuracy of **77.78%**.
- **RNN** showed its highest accuracy of **75.00%** at radius = 350, and plateaued at 72.22% for higher values.
- KNN was more sensitive to parameter changes, while RNN accuracy stabilized after a certain radius value.
- Visualizations made the performance differences clear across various parameter values.

---

##  Challenges & Decisions

- Selecting meaningful ranges for `k` and `radius` was key to capturing performance patterns.
- RadiusNeighborsClassifier needed careful parameter tuning to avoid empty neighbor sets.
- Feature scaling wasn’t critical here due to the dataset’s natural structure, but could benefit larger or noisier datasets.

---

##  Files Included

- `Lab2.ipynb`: Complete Jupyter Notebook with code, accuracy outputs, and plots.
- `README.md`: Overview and key takeaways from the lab.
- `screenshots/`: Folder containing output screenshots and accuracy plots:
  - Dataset overview and class distribution
  - Accuracy results from KNN and RNN
  - Comparison plots for KNN and RNN

---