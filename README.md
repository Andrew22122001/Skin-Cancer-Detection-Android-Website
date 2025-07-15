# 🧬 Skin Cancer Detection Web App

A full-stack web application for detecting and classifying skin cancer using deep learning models. This app allows users to upload dermoscopic images and receive predictions on possible skin lesion types, with model explanations powered by ensemble learning and segmentation.

---

## 🌐 Live Demo



https://github.com/user-attachments/assets/3008418c-0db1-4feb-96da-997783e71078



---

## 📦 Download Full Project (ZIP)

To access the entire source code including frontend, backend, and trained model files:

- [📥 Download ZIP from GitHub Releases](https://github.com/Andrew22122001/Skin-Cancer-Detection-Android-Website/releases/latest)

To extract:
**unzip SkinCancerWebApp.zip**



---

## 🚀 Features

- Upload dermoscopic images for real-time classification
- Predict 7 types of skin lesions using ensemble of CNNs (ResNet152, VGG19, DenseNet121)
- Lesion segmentation using Attention U-Net
- Model trained on the HAM10000 dataset
- RESTful API backend (Flask or Django)
- Responsive frontend (HTML/CSS/JavaScript)

---

## 🛠️ Tech Stack

### 🧩 Frontend
- HTML5, CSS3, JavaScript
- Bootstrap or custom UI

### 🔧 Backend
- Python (Flask or Django)
- REST APIs for prediction and file handling

### 🤖 Deep Learning
- PyTorch
- Models: ResNet152, VGG19, DenseNet121, Attention U-Net
- Ensemble learning for improved accuracy

---

## 🧠 Dataset

- **HAM10000:** Human Against Machine with 10,000+ dermoscopic images across 7 classes.
- **Data preprocessing:**
  - Resizing to 224x224
  - Normalization
  - Data augmentation to address class imbalance

---

## 📊 Model Performance

| Model                | Accuracy   |
|----------------------|-----------|
| ResNet-152           | 85%       |
| VGG-19               | 84%       |
| DenseNet-121         | 82%       |
| Ensemble             | 89%       |
| Attention U-Net (segmentation) | 87% IOU |

---

## 🧪 How to Run Locally

1. Clone the repo or extract the ZIP
2. Navigate to the backend directory
3. Create virtual environment (if needed):
python -m venv venv
source venv/bin/activate # macOS/Linux
venv\Scripts\activate # Windows
4. Install dependencies:
pip install -r requirements.txt
5. Start the backend server:
python app.py # or manage.py runserver if using Django

6. Open `index.html` or frontend app in browser

---

## 📎 Research Project Info

This project was part of an academic research paper titled:

**"Deep Learning-Based Skin Cancer Detection"**  
Authors: Siri Yellu, Akshay Krishna Varma Buddharaju, Andrew Bala Abhilash Polisetty  
Advisor: Dr. Sanghoon Lee

- Focused on CNNs and U-Net-based segmentation
- Used ensembling for classification robustness

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 📬 Contact

Feel free to reach out:

- **GitHub:** [Andrew22122001](https://github.com/Andrew22122001)
- **Email:** andrewbala99@gmail.com
- **LinkedIn:** www.linkedin.com/in/andrew-polisetty





