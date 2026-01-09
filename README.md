 # 🫁 Pneumonia Detection Using Chest X-Ray Images  
### Deep Learning Project using EfficientNetV2L

![Python](https://img.shields.io/badge/Python-3.9-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Project Overview
Pneumonia is a serious lung infection that requires **early and accurate diagnosis**.  
This project uses **deep learning and transfer learning (EfficientNetV2L)** to automatically detect pneumonia from **chest X-ray images**.

The goal is to assist doctors by providing a **fast, reliable AI-based screening system**.

---

## 🎯 Objectives
1. Build a deep learning model to classify chest X-rays as **Normal** or **Pneumonia**  
2. Improve detection accuracy using **transfer learning**  
3. Evaluate performance using **medical-grade metrics**

---

## 🧠 Model Used
- **EfficientNetV2L**
- Pretrained on **ImageNet**
- Fine-tuned for **binary classification**

Why EfficientNetV2L?
- High accuracy
- Fewer parameters
- Faster training
- Works well for medical images

---

## 🗂 Dataset
**Chest X-Ray Images (Kaggle)**  
Classes:
- Normal  
- Pneumonia  

Images were preprocessed using:
- Resizing  
- Normalization  
- Data augmentation  

---

## ⚙️ System Workflow
Chest X-ray Image
↓
Image Preprocessing
↓
EfficientNetV2L Model
↓
Feature Extraction
↓
Dense Layers
↓
Prediction (Normal / Pneumonia)



---

## 🛠 Technologies Used
- Python  
- TensorFlow  
- Keras  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Jupyter Notebook  

---

## 📊 Model Evaluation
The model was evaluated using:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Curve**
- **Confusion Matrix**

These metrics ensure the model is reliable for medical diagnosis.

---

## 📁 Repository Structure
Pneumonia-Detection-Using-Chest-XRay/
│
├── Pneumonia_Detection_code.ipynb # Main training & evaluation notebook
├── README.md # Project documentation


---

## ▶️ How to Run

1. Clone the repository  
```bash
git clone https://github.com/paavanikondeti/Pneumonia-Detection-Using-Chest-XRay.git
2.Open Jupyter Notebook
jupyter notebook
3.Run
Pneumonia_Detection_code.ipynb

📈 Results

The trained EfficientNetV2L model achieves strong performance in detecting pneumonia from chest X-rays, demonstrating the effectiveness of transfer learning for medical imaging tasks.

👩‍💻 Author

Paavani Kondeti
Deep Learning Project
Pneumonia Detection using Chest X-ray Images

If you find this project useful,Please give it a ⭐ on GitHub
