# 👁️ Computer Vision Group Project - Waste Classification System

## 📌 Overview
This project builds an image classification system to classify waste into three categories: **Plastic, Paper, and Organic**. It compares traditional machine learning and deep learning approaches.

---

## 👥 Group Members
* SEE CHWAN KAI (242UT2449P)
* KHO WEI CONG (242UT2449Z)
* TEO JING AN (242UT24490)
* Kerk Yi (1211203133)

---

## 🧠 Models Implemented
### 1. HOG + SVM
* Feature extraction using HOG
* Classification using SVM
* Tested with and without preprocessing
### 2. ResNet50
* Pretrained on ImageNet
* Transfer learning with frozen base layers
### 3. VGG16
* Pretrained CNN model
* Custom classification head

---

## ⚙️ Dataset
* Input folder: `/content/drive/MyDrive/Dataset`
* Classes:
  * Plastic
  * Paper
  * Organic
### Data Split
* Train: 70%
* Validation: 15%
* Test: 15%

Output structure:
```
Dataset_Split/
  ├── train/
  ├── val/
  └── test/
```

---

## 🧪 Preprocessing
### Image Enhancement
* CLAHE
* Gaussian Blur
* Sharpening
### Deep Learning Preprocessing
* Normalization (0–1)
* ImageNet preprocessing

---

## 📏 Evaluation Metrics
* Accuracy
* Precision
* Recall
* F1-Score

---

## 📊 Results
* Deep learning models (ResNet50, VGG16) outperform HOG + SVM
* Preprocessing improves traditional model performance
* Transfer learning provides strong classification accuracy

---

## 🚀 How to Run
### 1. Install dependencies
```bash
pip install numpy pandas matplotlib opencv-python tensorflow scikit-learn scikit-image
```
### 2. Prepare dataset
Place dataset in:
```
/content/drive/MyDrive/Dataset
```
### 3. Run notebook
```bash
jupyter notebook
```
Open the notebook and run all cells.

---

## 🔍 Key Insights
* Transfer learning models perform best
* Preprocessing is important for traditional methods
* Deep learning models are more robust

---

## 🔮 Future Improvements
* Add more waste categories
* Apply data augmentation
* Fine-tune pretrained models
* Use advanced architectures like EfficientNet

---

## 📚 Conclusion
This project shows that deep learning models significantly outperform traditional methods in image classification tasks, especially when using transfer learning.
