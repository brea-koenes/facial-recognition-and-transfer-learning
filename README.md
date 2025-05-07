# 🧠 Facial Recognition & Transfer Learning

This project explores two major applications of deep learning in computer vision:

- **Facial recognition** using MTCNN for detection and VGGFace for identity recognition.
- **Image classification** using Convolutional Neural Networks (CNNs) and transfer learning with pretrained models like VGG16 and ResNet.

---

## 📚 Project Notebooks

| Notebook | Focus | Description |
|----------|-------|-------------|
| `Facial_Recognition.ipynb` | 😎 Face Detection & Recognition | Uses MTCNN to detect faces and VGGFace to match identities. Demonstrates real-world preprocessing and recognition robustness. |
| `CNNs.ipynb` | 🧠 Transfer Learning with CNNs | Trains image classifiers using transfer learning on models like VGG16 and ResNet. Evaluates performance on small custom datasets. |

---

## 🔍 Highlights

### 👤 Facial Recognition
- **Detection**: MTCNN accurately locates faces across varied lighting and angles.
- **Recognition**: VGGFace reliably matches identities even with expression and lighting differences.
- Included preprocessing: face alignment, cropping, and normalization.

### 🧪 Transfer Learning
- Used pretrained CNNs (VGG16, ResNet) with fine-tuning.
- Achieved strong classification accuracy on limited data.
- Demonstrated benefits of transfer learning in low-data scenarios.

---

## 🛠 Tech Stack

- **Python**: Core scripting language
- **Keras / TensorFlow**: Model building and training
- **MTCNN**: Face detection
- **VGGFace**: Face recognition embedding model
- **OpenCV / Matplotlib**: Visualization
- **Scikit-learn**: Evaluation tools

---

## 📁 Repo Structure

facial-recognition-and-transfer-learning/
├── Facial_Recognition.ipynb
├── CNNs.ipynb
└── README.md

---

## 🎯 Purpose

This repo demonstrates:
- The power of deep learning in facial recognition
- Practical use of transfer learning for real-world image classification tasks
- Hands-on implementation of both pretrained models and custom pipelines
