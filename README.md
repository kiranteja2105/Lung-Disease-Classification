
# 🫁 Lung Disease Classification System

## 🚀 Overview
This project focuses on building an AI-based system to automatically classify lung diseases from chest X-ray images. The model predicts the category of a given X-ray image into one of the following classes:

- COVID-19
- Lung Opacity
- Viral Pneumonia
- Normal

The system aims to assist in early diagnosis and reduce the workload on medical professionals.

---

## 🎯 Features
- 🖼️ Upload chest X-ray images
- 🤖 AI-based disease prediction
- ⚡ Fast and accurate classification
- 📊 Multi-class classification (4 categories)
- 🌐 Web interface using Flask
- 🔍 Real-time inference

---

## 🛠️ Tech Stack

### Programming Language
- Python

### Frameworks & Libraries
- Flask (Backend)
- PyTorch / TensorFlow (Model)
- OpenCV (Image Processing)
- NumPy, Pandas (Data Handling)
- Matplotlib (Visualization)

---

## 🧠 Model Details
- Used pre-trained deep learning models (Transfer Learning)
- Models experimented:
  - ConvNeXt
  - ResNet
  - EfficientNet

- Final model selected based on:
  - Accuracy
  - Precision & Recall
  - F1-score

---

## 📂 Dataset
- Public Chest X-ray dataset
- 4 Classes:
  - COVID-19
  - Lung Opacity
  - Viral Pneumonia
  - Normal

### Preprocessing Steps
- Image resizing
- Normalization
- Data augmentation
- Train-test split

---

## 🏗️ System Workflow

1. Upload X-ray image  
2. Preprocess image  
3. Feed into trained model  
4. Predict disease class  
5. Display result  

---

## 📸 Output Example

**Input:** Chest X-ray Image  
**Output:** `COVID-19`

---


# Install dependencies
pip install -r requirements.txt
