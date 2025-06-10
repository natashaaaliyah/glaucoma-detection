
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

| Model                    | Accuracy  | Precision | Recall     | F1-score  |
| ------------------------ | --------- | --------- | ---------- | --------- |
| Logistic Regression      | 0.599     | 0.600     | 0.607      | 0.6035    |
| Decision Tree            | 0.590     | 0.591     | 0.601      | 0.596     |
| Random Forest            | 0.585     | 0.586     | 0.574      | 0.580     |
| SVM                      | 0.706     | 0.707     | 0.684      | 0.695     |
| KNN                      | **0.780** | **0.750** | 0.690      | **0.719** |
| XGBoost                  | 0.714     | 0.716     | 0.691      | 0.703     |
| GBM                      | 0.702     | 0.703     | 0.695      | 0.699     |
| Neural Network           | 0.620     | 0.622     | 0.610      | 0.616     |
| Self-Supervised KD Model | 0.7065    | 0.7065    | **0.7065** | 0.7052    |
## Image-based models
| Model               | Accuracy | Precision | Recall   | F1-score |
| ------------------- | -------- | --------- | -------- | -------- |
| Logistic Regression | 0.70     | 0.75      | 0.75     | 0.67     |
| Random Forest       | 0.67     | 0.75      | 0.75     | 0.67     |
| **MobileNet**       | **0.83** | **0.88**  | **0.83** | **0.83** |
| EfficientNet        | 0.75     | 0.72      | 0.72     | 0.72     |
| ResNet50            | 0.679    | 0.69      | 0.70     | 0.67     |
| DenseNet            | 0.74     | 0.70      | 0.70     | 0.70     |
| CNN                 | 0.33     | 0.33      | 0.33     | 0.33     |



---

## 👩‍🔬 Project by: Natasha and Rinah

