# **Bharatanatyam Mudra Classifier using VGG19**

A deep learning project that recognizes **Bharatanatyam one-hand mudras (Asamyukta Hastas)** using **VGG19**, **TensorFlow/Keras**, and a **custom curated dataset**.

This repository includes both the **original V1 model** and the **new, improved V2 classifier** trained on a richer dataset containing **right + wrong mudras**.

---

# 🔄 **📌 Model Versions**

| Version                                        | Description                                                                                                                   | File                                                                                       |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **V1 – Right-Hand Mudras Only**                | Original model trained only on *correct/valid* one-hand mudras. High accuracy for pure classification.                        | [`vgg19_bharatnatyam_mudra_classifier.py`](./vgg19_bharatnatyam_mudra_classifier.py)       |
| **V2 – Right + Wrong Mudras (Improved Model)** | Upgraded Kaggle notebook trained on *both correct and incorrect* mudras, improving real-world robustness and error detection. | [`VGG19_MudraClassifier_RightAndWrong.ipynb`](./VGG19_MudraClassifier_RightAndWrong.ipynb) |

---

# 🚀 **Open the Notebooks**

### **⭐ V2 – Latest Notebook (Recommended)**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/VGG19_MudraClassifier_RightAndWrong.ipynb)

### **V1 – Older Notebook (Right-Hand Mudras Only)**

(Optional)
[Open V1 Notebook](https://colab.research.google.com/github/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/Vgg19_BharatNatyam_Mudra_Classifier.ipynb)

---

# 🧠 **Project Overview**

This project classifies images of **Bharatanatyam Asamyukta Hasta mudras**.

### **V1 Highlights**

* Trained only on **correct right-hand mudras**
* Very high accuracy
* Ideal for pure classification

### **V2 Highlights (Recommended)**

* Includes **correct + incorrect mudras**
* More robust in real-world settings
* Handles diverse inputs & web images
* Better at distinguishing similar shapes

---

# ⚙️ **Tech Stack**

* **Languages:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Matplotlib
* **Model:** VGG19 (fine-tuned)
* **Platforms:** Google Colab · Kaggle

---

# 📊 **Model Performance**

### **V1 Accuracy:** ~98%

✔️ Trained on clean right-hand mudras
✔️ Excellent validation performance

### **V2 Accuracy:**

*(Add after completing training)*
Supports classification + error detection.

---

# 📸 **Sample Prediction (V1)**

<div align="center">
<img src="https://github.com/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/patakha%20prediction%20image%20.png" width="600"/>
</div>

**Predicted Mudra:** *Pathaka(1)*
🎯 **Confidence:** *80.07%*

---

# 📸 **Sample Predictions (V2 – Real-World Testing)**

These results come from **random online images**, proving that the V2 model generalizes beyond the dataset.

---

### 🔹 **Shukatundam (1)**

<div align="center">
<img src="https://github.com/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/shukatunda%20vgg19%20prediction%20(v2).jpeg" width="450"/>
</div>

**Confidence:** *100%*

---

### 🔹 **Mushti (1)**

<div align="center">
<img src="https://github.com/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/mushti%20vgg-19%20prediction%20(v2).jpeg" width="450"/>
</div>

**Confidence:** *57.19%*

---

### 🔹 **Aralam (1)**

<div align="center">
<img src="https://github.com/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/arala%20vgg-19%20prediction%20(v2).jpeg" width="450"/>
</div>

**Confidence:** *72.94%*

---

# 🎯 **Use Cases**

* Automated Bharatnatyam mudra recognition
* Digital dance-learning assistants
* Error detection (using V2)
* Cultural and heritage AI systems
* Dataset research & expansion

---

# 👩‍💻 **Author**

**Ketki Vijay Mohite**
📧 [ketkimohite214@gmail.com](mailto:ketkimohite214@gmail.com)
🎓 MCA Student · Bharatnatyam Teacher


