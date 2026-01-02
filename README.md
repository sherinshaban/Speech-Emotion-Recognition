# Speech Emotion Recognition (SER) 

This project focuses on building a Deep Learning model to recognize and classify human emotions from audio speech files using the **RAVDESS** dataset.

##  Project Overview
The goal is to analyze audio signals and extract meaningful features to predict the speaker's emotion (e.g., Happy, Sad, Angry, Neutral). This is a key application in Human-Computer Interaction (HCI).

##  Dataset
**RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**
* Contains 7356 files.
* Includes 24 professional actors (12 female, 12 male).
* **Emotions classified:** Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, and Surprised.

##  Methodology & Workflow
1. **Data Loading:** Parsing audio files from the dataset.
2. **Data Augmentation:** Applying techniques like *Noise Injection* and *Time Stretching* to increase dataset variety and prevent overfitting.
3. **Feature Extraction:** Converting raw audio waves into **Log-Mel Spectrograms** using `librosa`.
4. **Model Architecture:** (Using CNN / LSTM - *Specify here if you used a specific model*) to classify emotions based on extracted features.

##  Technologies Used
* **Language:** Python 
* **Libraries:** Librosa, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn.
* **Platform:** Google Colab.

##  How to Run
1. Open the notebook `Analysis_Speech_Dataset__RAVDESS.ipynb` in Google Colab or Jupyter Notebook.
2. Ensure the dataset path is correctly set.
3. Run all cells to see the feature extraction and classification results.

---
**Developed by:** [Sherin Shabaan]
