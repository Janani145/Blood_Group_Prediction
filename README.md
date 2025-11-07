# 🩸 Blood Group Detection using Deep Learning

## 📘 Overview
This project uses **deep learning (VGG16)** to automatically detect a person’s **blood group** (A+, A-, B+, B-, AB+, AB-, O+, O-) from microscopic image samples.  
It was trained and tested using a custom image dataset and deployed using **Streamlit** for an interactive web interface.

---

## 🧠 Key Features
- ✅ Predicts **8 blood group types**.
- 🧬 Built using **VGG16** (transfer learning).
- 📊 Achieved **71.42% validation accuracy**.
- 🖼️ Works with uploaded image files (BMP/JPG/PNG).
- 🌐 Interactive web app made using **Streamlit**.

---

## 🧰 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python 3 |
| Deep Learning | TensorFlow, Keras |
| Image Processing | NumPy, OpenCV, PIL |
| Visualization | Matplotlib, Seaborn |
| Web Framework | Streamlit |
| Model | VGG16 (Pre-trained on ImageNet) |

---

## 🗂️ Dataset
- The dataset contains **microscopic blood sample images** categorized into 8 classes:
  - `A+`, `A-`, `B+`, `B-`, `AB+`, `AB-`, `O+`, `O-`
- Each class includes around **1000 images** (augmented for better balance).
- Dataset split:
  - **Training:** 80%
  - **Testing:** 20%

---

## 🧪 Results

- Test Accuracy: 71.42%
- Loss: 1.13061
- The model performs well across all classes, with slight variations due to dataset balance.

## ✨ Future Enhancements

- Improve accuracy using ResNet50 or EfficientNet.
- Add a real-time camera input option.
- Deploy the model on the web or mobile using TensorFlow Lite.
