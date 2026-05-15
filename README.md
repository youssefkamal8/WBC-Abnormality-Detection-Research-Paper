# WBC Abnormality Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.14-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Status](https://img.shields.io/badge/Research-Completed-green)

A deep learning-based research project for detecting abnormal White Blood Cells (WBCs) from microscopic blood smear images using state-of-the-art Convolutional Neural Networks (CNNs).

This project evaluates multiple transfer learning architectures to improve early and reliable blood cancer diagnosis.

---

# 📌 Project Overview

White Blood Cell abnormality detection plays a critical role in the early diagnosis of blood-related diseases such as leukemia. Manual diagnosis is time-consuming, error-prone, and highly dependent on expert analysis.

This project proposes an automated deep learning pipeline capable of classifying WBC images with high accuracy using advanced CNN architectures and image augmentation techniques.

The system was trained and evaluated on the **C-NMC Leukemia Dataset**, containing more than **3,000 microscopic WBC images**.

---

# 🚀 Key Features

* Evaluated **8 state-of-the-art CNN architectures**
* Implemented **Transfer Learning**
* Applied **Data Augmentation**
* Used **Test-Time Augmentation (TTA)**
* Achieved **97.9% Accuracy** using **RegNet-X**
* Achieved **99% Recall**
* Reduced misclassification rate to **2.1%**
* Built using **Python** and **PyTorch**

---

# 🧠 Models Evaluated

The following CNN architectures were tested and compared:

* RegNet-X ✅ *(Best Performing Model)*
* ConvNeXt
* ResNet50
* VGG19
* Xception
* EfficientNet
* InceptionV3
* AlexNet

---

# 📊 Best Results

| Model    | Accuracy            | Recall             |
| -------- | ------------------- | ------------------ |
| RegNet-X | **97.9%**           | **99%**            |
| ConvNeXt | High Performance    | High Recall        |
| ResNet50 | Competitive Results | Stable Performance |

---

# 🛠️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Pandas
* OpenCV
* Matplotlib
* Scikit-learn

---

# 📂 Dataset

This project uses the **C-NMC Leukemia Dataset**, which contains microscopic blood smear images categorized into:

* Normal White Blood Cells
* Abnormal White Blood Cells

---

# ⚙️ Methodology

## 1. Data Preprocessing

* Image resizing
* Normalization
* Data augmentation
* Dataset splitting

## 2. Transfer Learning

Pretrained CNN models were fine-tuned on the WBC dataset to improve feature extraction and reduce training time.

## 3. Training

* Cross-entropy loss
* Adam optimizer
* Validation monitoring
* Learning rate scheduling

## 4. Evaluation

Performance metrics:

* Accuracy
* Recall
* Precision
* F1-score
* Confusion Matrix

## 5. Test-Time Augmentation (TTA)

Multiple augmented versions of test images were evaluated to improve prediction robustness and reduce classification errors.

---

# 📈 Performance Metrics

```text
Best Model: RegNet-X
Accuracy: 97.9%
Recall: 99%
Misclassification Rate: 2.1%
```

---

# 📁 Project Structure

```bash
WBC-Abnormality-Detection-Research-Paper/
│
├── WBC_Abnormality_Detection.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── results/
└── sample_images/
```

---

# ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/youssefkamal8/WBC-Abnormality-Detection-Research-Paper.git
cd WBC-Abnormality-Detection-Research-Paper
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Project

Launch the notebook:

```bash
jupyter notebook
```

Open:

```text
WBC_Abnormality_Detection.ipynb
```

---

# 🔬 Research Contribution

This work demonstrates how modern deep learning architectures can significantly improve automated medical image classification systems for hematological diagnosis.

The proposed approach:

* Enhances diagnostic reliability
* Reduces human error
* Supports faster clinical decision-making
* Improves early leukemia detection

---

# 📷 Workflow

```text
Microscopic WBC Image
        ↓
Preprocessing & Augmentation
        ↓
CNN Feature Extraction
        ↓
Classification
        ↓
Normal / Abnormal Prediction
```

---

# 📌 Future Improvements

* Deploy as a web-based diagnostic tool
* Integrate Explainable AI (XAI)
* Expand dataset diversity
* Optimize for real-time clinical usage

---

# 👨‍💻 Author

**Youssef Kamal**

* Deep Learning
* Computer Vision
* Medical Image Analysis
* AI Research

---

# 📜 License

This project is intended for research and educational purposes.
