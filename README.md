# 🦋 Butterfly Image Classification Final Project

A deep learning project that classifies butterfly species from images using a **Convolutional Neural Network (CNN)** built with TensorFlow and Keras. The trained model is served through a simple **Flask** web app, allowing users to upload an image and get real-time species predictions.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 📖 Overview

This project trains a CNN model to classify images of butterflies into their respective species. It covers the full pipeline — from image preprocessing and model training to serving predictions via a Flask web interface.

---

## ✨ Features

- 🖼️ Image preprocessing and augmentation
- 🧠 Custom CNN architecture for multi-class classification
- 📊 Training and validation with performance tracking
- 🔍 Prediction on new/unseen butterfly images
- 🌐 Flask-based web app for interactive predictions

---

## 🛠️ Tech Stack

| Category            | Tools                          |
|----------------------|--------------------------------|
| Language             | Python                         |
| Deep Learning        | TensorFlow, Keras              |
| Image Processing     | OpenCV                         |
| Data Handling        | NumPy, Pandas                  |
| Web Framework        | Flask                          |

---

## 📂 Project Structure

```
Butterfly_Flask_Project/
│
├── app.py                    # Flask application entry point
├── butterfly_model.keras     # Trained CNN model
├── class_indices.json        # Mapping of class labels to indices
├── requirements.txt          # Project dependencies
├── README.md                 # Project documentation
│
├── templates/
│   └── index.html            # Web app front-end
│
└── notebooks/
    └── butterfly_model.ipynb # Model training & experimentation notebook
```

---

## 📊 Dataset

The dataset used for training is sourced from Kaggle:

🔗 [Butterfly Image Classification Dataset](https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification)

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/Butterfly-Image-Classification-project.git
   cd Butterfly-Image-Classification-project
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model** *(optional — a pre-trained model is already included)*
   ```bash
   python train.py
   ```

4. **Run predictions**
   ```bash
   python predict.py
   ```

5. **Launch the web app**
   ```bash
   python app.py
   ```

---

## 🚀 Usage

- Run `train.py` to train the CNN model on the butterfly dataset.
- Run `predict.py` to classify a new butterfly image from the command line.
- Run `app.py` and open the local server URL in your browser to use the Flask web interface for image upload and prediction.

---

## 📈 Results

| Metric              | Value |
|----------------------|-------|
| Training Accuracy    | 70-80% |

---

## 🔮 Future Improvements

- Improve accuracy with transfer learning (e.g., ResNet, EfficientNet)
- Add data augmentation to reduce overfitting
- Deploy the Flask app to a cloud platform (Heroku, Render, AWS, etc.)
- Add confidence scores and top-k predictions to the UI

---

## 📄 License

Not Available
