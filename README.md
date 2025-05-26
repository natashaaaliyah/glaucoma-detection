
# 👁️ Glaucoma Detection Using Machine Learning

This project aims to detect glaucoma using fundus images and statistical data by applying various machine learning and deep learning models. The project explores both image-based and tabular data-based approaches  know as multi-modelling for comprehensive glaucoma diagnosis.

---

## 📂 Datasets Used

- Fundus images (Healthy & Glaucoma)
- Statistical dataset with patient information

---

## 🧠 Models Implemented

### 🖼️ Image-Based Models
- Convolutional Neural Network (CNN)
- MobileNetV2 ✅ *(Best performing image model)*
- EfficientNet-B0
- ResNet
- DenseNet
- Capsule Network (planned)


### 📊 Statistical Data Models
- K-Nearest Neighbors (KNN) ✅ *(Best performing tabular model)*
- Logistic Regression
- Gradient Boosting Machine (GBM)
- Random Forest

---

## 📈 Explainability Techniques

- LIME
- Saliency Maps (image data)
- Feature Importance & Partial Dependence Plots (statistical data)

---

## 💡 Future Work


- Knowledge distillation for model compression
- Hyperparameter tuning
- Deployment as a web tool

---
## 
- Fused the probabilities of KNN and mobilenetV2
## 🧪 Results Snapshot

| Model          | Dataset Type | Accuracy |
|----------------|--------------|----------|
| MobileNetV2    | Image        | ~90%     |
| KNN            | Statistical  | ~85%     |
| CNN            | Image        | Lower    |
| GBM            | Statistical  | Lower    |

---

## 👩‍🔬 Project by: Natasha and Rinah

