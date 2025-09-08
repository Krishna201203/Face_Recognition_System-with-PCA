# 👤 Face Recognition System

A **machine learning project** that implements a **Face Recognition System** using **Eigenfaces (PCA)**, **Fisherfaces (LDA)**, and a **Neural Network (MLPClassifier)**.
The system identifies individuals based on facial features extracted from images.

---

## 📊 Problem Statement

Face recognition is widely used in **security systems, authentication, and surveillance**.
This project demonstrates how to:

* Preprocess facial image datasets
* Extract features using **dimensionality reduction** techniques
* Train a classifier to recognize individuals

---

## 🚀 Features

* 📷 Load custom face datasets from directories
* 🖼️ Preprocess images (resize, grayscale, flatten)
* 🧠 Apply **PCA (Eigenfaces)** for unsupervised feature extraction
* 🎭 Apply **LDA (Fisherfaces)** for supervised dimensionality reduction
* 🤖 Train a **Neural Network (MLPClassifier)** for classification
* 📊 Visualize eigenfaces and recognition results

---

## 🛠️ Tech Stack

* **Programming Language**: Python 🐍
* **Libraries**:

  * OpenCV – Image preprocessing
  * NumPy – Numerical operations
  * Matplotlib – Visualization
  * Scikit-learn – PCA, LDA, MLPClassifier, train/test split

---

## 📂 Project Structure

```bash
Face-Recognition-System/
│── Face_Recognition_System.ipynb   # Jupyter Notebook
│── dataset/                        # Folder containing face images
│   ├── person1/
│   │    ├── img1.jpg
│   │    ├── img2.jpg
│   ├── person2/
│   │    ├── img1.jpg
│   │    ├── img2.jpg
│   └── ...
│── requirements.txt                # Dependencies
│── README.md                       # Documentation
```

---

## ⚡ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Face-Recognition-System.git
cd Face-Recognition-System
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run Notebook

```bash
jupyter notebook Face_Recognition_System.ipynb
```

---

## 📊 Dataset

* Images should be organized into **folders by person name**:

  ```
  dataset/
  ├── Alice/
  │    ├── img1.jpg
  │    ├── img2.jpg
  ├── Bob/
  │    ├── img1.jpg
  │    ├── img2.jpg
  ```
* Each folder corresponds to one **class (person)**.

---

## 🧠 Models Implemented

1. **PCA (Principal Component Analysis - Eigenfaces)**

   * Extracts the most significant features from facial images.
   * Reduces dimensionality while retaining important variance.

2. **LDA (Linear Discriminant Analysis - Fisherfaces)**

   * Uses supervised labels to maximize class separability.

3. **MLPClassifier (Neural Network)**

   * Learns complex decision boundaries for classification.
   * Hidden layers: `(10, 10)` with max\_iter=1000.

---

## 📈 Results

* Successfully projects facial images onto **Eigenfaces & Fisherfaces space**.
* Neural Network achieves strong performance (exact accuracy depends on dataset).
* Eigenfaces visualization shows the most influential features used for recognition.

---

## 🔮 Future Enhancements

* Add **CNN-based models** (Deep Learning for higher accuracy).
* Build a **real-time face recognition system** using OpenCV webcam.
* Integrate with **Flask / Streamlit** for a web application.

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new branch (`git checkout -b feature-xyz`)
3. Commit changes (`git commit -m "Added new feature"`)
4. Push to branch (`git push origin feature-xyz`)
5. Open a Pull Request

---

## 👨‍💻 Author

**Krishna Kumar Ranjan**
📧 \[krishnaranjan1111@gmail.com]

---

✨ If you found this project helpful, don’t forget to **star ⭐ the repo**!
