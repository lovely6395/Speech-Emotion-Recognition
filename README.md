# Speech Emotion Recognition using Machine Learning

## 📌 Project Overview
This project focuses on **Speech Emotion Recognition (SER)**, which aims to identify and classify human emotions from speech signals using machine learning techniques.  
It can be useful in applications such as human-computer interaction, virtual assistants, customer support systems, and mental health monitoring.

---

## Dataset
- **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**
- Contains professionally recorded speech data
- Covers **8 different emotions**
- Audio format: `.wav`

---

## Feature Extraction
The following audio features are extracted from each speech file:
- MFCC (Mel Frequency Cepstral Coefficients)
- Zero Crossing Rate (ZCR)
- Chroma Features
- Spectral Contrast
- Harmonic-to-Noise Ratio (HNR)

---

## Machine Learning Model
- **Support Vector Machine (SVM)**
- Hyperparameter tuning using **GridSearchCV**
- Feature scaling using **StandardScaler**

---

## Results
- Achieved **high accuracy** on the test dataset
- Model performance evaluated using:
  - Accuracy score
  - Classification report
  - Confusion matrix

---

## Technologies Used
- Python
- NumPy
- Librosa
- SoundFile
- Praat-Parselmouth
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

---

## Project Structure
Speech_Emotion_Recognition/
│
├── data/               # Dataset directory (not included in repo)

├── features/           # Extracted audio features (MFCC, ZCR, HNR, Spectral Contrast)

├── models/             # Trained model files or scripts

├── main.py             # Main script for training, testing, and evaluation

├── requirements.txt    # Required Python libraries

├── README.md           # Project documentation

└── .gitignore


**Note:** The data/ folder is not included in the repository. Please download the dataset manually from the official source.
**License:** This project is private and not open for reuse.

   pip install librosa numpy soundfile scikit-learn praat-parselmouth

