# **Bharatanatyam Mudra Classifier using VGG19**

A deep learning project that recognizes **Bharatanatyam one-hand mudras (Asamyukta Hastas)** using **VGG19**, **TensorFlow/Keras**, and a **custom curated dataset**.

This repository now includes **two versions** of the classifier:

---

# 🔄 **📌 Model Versions**

| Version                                        | Description                                                                                                 | File                                                                                       |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **V1 – Right-Hand Mudras Only**                | Original model trained only on *correct/valid* one-hand mudras                                              | [`vgg19_bharatnatyam_mudra_classifier.py`](./vgg19_bharatnatyam_mudra_classifier.py)       |
| **V2 – Right + Wrong Mudras (Improved Model)** | Updated Kaggle notebook trained on *both correct and incorrect* mudras for better classification robustness | [`VGG19_MudraClassifier_RightAndWrong.ipynb`](./VGG19_MudraClassifier_RightAndWrong.ipynb) |

---

# 🚀 **Open the Notebooks**

### **V2 – Latest Notebook (Recommended)**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/VGG19_MudraClassifier_RightAndWrong.ipynb)

### **V1 – Older Notebook (Right-Hand Mudras Only)**

*(Optional)*
[Open V1 Notebook](https://colab.research.google.com/github/ketkimohite/BharatNatyam-Mudra-classifier/blob/main/Vgg19_BharatNatyam_Mudra_Classifier.ipynb)

---

# 🧠 **Project Overview**

This model classifies **Bharatanatyam Asamyukta Hasta mudras** using deep learning.

* **V1:** Focused purely on **correct right-hand mudras**, trained for high precision.
* **V2:** Enhanced version that includes **both correct + incorrect mudras**, enabling:

  * Better generalization
  * Error detection
  * More robust real-world performance

---

# ⚙️ **Tech Stack**

* **Languages:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Matplotlib
* **Model:** VGG19 (fine-tuned)
* **Platforms:** Google Colab · Kaggle

---

# 📊 **Model Performance**

### **V1 Accuracy:** ~98% (Right-hand mudras only)

### **V2 Accuracy:** *(Add your accuracy after training — optional)*

---

# 📸 **Sample Prediction (V1)**

<div align="center">
<img src="https://github.com/ketkivmohite/BharatNatyam-Mudra-classifier/blob/main/patakha%20prediction%20image%20.png" width="600"/>
</div>

✅ **Predicted Mudra:** *Pathaka(1)*
🎯 **Confidence:** *80.07%*

---

# 🎯 **Use Cases**

* Automated Bharatnatyam mudra recognition
* Dance training assistance
* Error detection (V2)
* Dataset expansion research
* Cultural AI applications

---

# 👩‍💻 **Author**

**Ketki Vijay Mohite**
📧 [ketkimohite214@gmail.com](mailto:ketkimohite214@gmail.com)
🎓 MCA Student · Bharatnatyam Teacher


