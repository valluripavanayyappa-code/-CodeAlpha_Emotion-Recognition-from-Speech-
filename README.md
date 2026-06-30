# -CodeAlpha_Emotion-Recognition-from-Speech-
# 🎙️ Emotion Recognition from Speech using Deep Learning

## 📌 Project Overview

This project focuses on **Speech Emotion Recognition (SER)** using Deep Learning techniques. The objective is to automatically identify the emotional state of a speaker from speech audio by extracting **Mel-Frequency Cepstral Coefficients (MFCCs)** and training a **CNN + BiLSTM** model.

The model is trained on publicly available emotional speech datasets and classifies speech into multiple emotion categories such as Happy, Sad, Angry, Fear, Neutral, Disgust, Calm, Surprise, and Boredom.

---

## 🚀 Features

* Speech Emotion Recognition using Deep Learning
* MFCC Feature Extraction
* Combined multiple speech emotion datasets
* CNN + BiLSTM Neural Network
* Data Preprocessing and Normalization
* Model Evaluation using Accuracy, Precision, Recall, and F1-Score
* Confusion Matrix Visualization
* Predict Emotion from Custom Audio Files
* Save and Reload Trained Model

---

## 📂 Dataset

This project uses the following publicly available datasets:

* **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**
* **TESS (Toronto Emotional Speech Set)**
* **EMO-DB (Berlin Database of Emotional Speech)**

These datasets contain speech samples labeled with different emotions.

---

## 😊 Emotion Classes

* Angry
* Calm
* Disgust
* Fear
* Happy
* Neutral
* Sad
* Surprise
* Boredom

---

## 🛠️ Technologies Used

* Python
* Google Colab
* TensorFlow / Keras
* Librosa
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

---

## 🧠 Model Architecture

```text
Speech Audio
      │
      ▼
MFCC Feature Extraction
      │
      ▼
Feature Normalization
      │
      ▼
CNN Layers
      │
      ▼
BiLSTM Layer
      │
      ▼
Dense Layers
      │
      ▼
Softmax Output
      │
      ▼
Predicted Emotion
```

---

## 📁 Project Structure

```text
Emotion-Recognition-from-Speech/
│
├── emotion_recognition.ipynb
├── EmotionRecognitionModel.keras
├── label_encoder.pkl
├── scaler.pkl
├── X.npy
├── y.npy
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Upload or mount the datasets (RAVDESS, TESS, and EMO-DB).
3. Install the required libraries.
4. Run all notebook cells in order.
5. Train the CNN + BiLSTM model.
6. Evaluate the model using the provided metrics.
7. Predict emotions from new `.wav` audio files.

---

## 📊 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📦 Output Files

After training, the following files are generated:

* `EmotionRecognitionModel.keras`
* `label_encoder.pkl`
* `scaler.pkl`
* `X.npy`
* `y.npy`

---

## 🔮 Future Improvements

* Use full MFCC sequences instead of averaged features.
* Add data augmentation techniques.
* Implement attention-based deep learning models.
* Deploy the model as a web application using Flask or Streamlit.
* Enable real-time emotion recognition from microphone input.

---

## 👨‍💻 Author

**Valluri Pavan Ayyappa**

GitHub: https://github.com/valluripavanayyappa-code

LinkedIn: *(Add your LinkedIn profile link here)*

---

## 📜 License

This project is developed for educational and internship purposes.
