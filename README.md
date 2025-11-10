## WEEK -2

---

## 🧾 **Chest X-ray Classification using CNN — Week 2 Project Report**

### 🔍 **Overview**

This project aims to classify **chest X-ray images** into four categories:

* **Adenocarcinoma**
* **Large Cell Carcinoma**
* **Normal**
* **Squamous Cell Carcinoma**

A **Convolutional Neural Network (CNN)** model was built using **TensorFlow** and **Keras** to automate early detection of lung diseases from X-ray images.

---

### 🎯 **Objectives**

* Train a deep learning model for accurate chest X-ray classification.
* Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.
* Save and deploy the trained model for real-world image predictions.

---

### 🧠 **Work Done in Week 2**

In **Week 2**, the following updates and improvements were made:

1. **Model Saving & Loading**

   * Implemented model saving using both `.keras` and `.weights.h5` formats.
   * Successfully reloaded the trained model to make new predictions without retraining.

2. **Prediction Function Added**

   * Created a custom function `predict_chest_xray(img_path, model)` to classify new X-ray images.
   * Implemented image preprocessing, normalization, and softmax-based confidence scoring.

3. **Error Handling & Debug Fixes**

   * Fixed shape mismatch errors (`(1, 224, 224, 3)` input issue).
   * Resolved compatibility warnings from TensorFlow regarding legacy `.h5` format.

4. **Project Upload to GitHub**

   * Initialized Git locally and pushed the complete project to a GitHub repository.
   * Added `.gitignore`, `README.md`, and `requirements.txt` for proper version control.

5. **Repository Update**

   * Renamed repository from **Week-1 → Week-2** to reflect project progress.
   * Updated the remote URL and folder name accordingly.

---

### 🧩 **Key Learnings**

* Hands-on experience with **TensorFlow model saving/loading formats** (`.keras`, `.weights.h5`).
* Debugging practical issues like **input shape**, **Git conflicts**, and **path errors**.
* Using **GitHub effectively** for version control and collaboration.
* Gained a deeper understanding of **deep learning workflows** in medical image analysis.



