# 🌽 Maize Leaf Disease Detection using Deep Learning

## 📌 Overview

This project presents an intelligent **machine learning–based system** for detecting and classifying maize (corn) leaf diseases using image processing and deep learning techniques.

The system analyzes leaf images and classifies them into four categories:

* 🌱 Healthy
* 🍂 Blight
* 🟠 Common Rust
* ⚫ Gray Leaf Spot

It leverages Convolutional Neural Networks (CNNs) and transfer learning models to provide accurate and automated disease detection, supporting **precision agriculture**.

---

## 🚀 Features

* Image-based disease detection
* Deep learning models:

  * Custom CNN
  * ResNet50 (Transfer Learning)
  * DenseNet121 (Transfer Learning)
* Data preprocessing & augmentation pipeline
* Model evaluation using:

  * Accuracy
  * Precision
  * Recall
  * F1 Score
* Confusion matrix & performance visualization

---

## 🧠 Models Used

| Model       | Description                               |
| ----------- | ----------------------------------------- |
| Custom CNN  | Built from scratch, optimized for dataset |
| ResNet50    | Pre-trained model using transfer learning |
| DenseNet121 | Deep architecture with dense connections  |

### 📊 Performance Summary

| Model       | Accuracy   |
| ----------- | ---------- |
| Custom CNN  | **87.62%** |
| DenseNet121 | 87.02%     |
| ResNet50    | 55.36%     |

The **Custom CNN** achieved the best overall performance.

---

## 🗂️ Dataset

* Source: Public maize leaf disease dataset (Kaggle)
* Total Images: 2,677
* Classes: 4
* Image Size: 256×256 (resized during preprocessing)

### Data Split

* Training: 64%
* Validation: 16%
* Test: 20%

---

## ⚙️ Tech Stack

* Python 3.x
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib / Seaborn
* Scikit-learn
* OpenCV / PIL

---

## 🔄 Workflow

1. Data Collection
2. Data Preprocessing

   * Resizing
   * Normalization
   * Augmentation
3. Model Training
4. Evaluation
5. Comparison of Models

---

## 🖼️ Data Augmentation Techniques

* Rotation
* Zoom
* Width & height shift
* Shear transformation
* Horizontal flipping

---

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## 💡 Key Insights

* Custom CNN outperformed transfer learning models
* DenseNet showed strong generalization
* ResNet underperformed due to limited dataset adaptation
* Class imbalance affected Gray Leaf Spot detection

---

## 🌍 Applications

* Smart farming systems
* Mobile-based crop disease detection
* Agricultural decision support tools
* Precision agriculture solutions

---

## 🔮 Future Work

* Use advanced architectures (e.g., Vision Transformers)
* Improve dataset size & diversity
* Handle class imbalance (SMOTE, weighted loss)
* Deploy as a mobile/web application
* Real-time disease detection using IoT

---

## 👨‍💻 Author

**Satya Krishna Eluri**
MSc Computer Science

---

## 📜 License

This project is for academic and research purposes.

---

If you want, I can also:

* Add **installation steps & requirements.txt**
* Customize it for **your exact GitHub repo structure**
* Or make it more **industry-level (for job portfolio)**
