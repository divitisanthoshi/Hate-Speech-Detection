# Hate Speech Detection

This project implements a hate speech detection system using machine learning techniques.

## 📌 Features
- **Dataset:** The dataset consists of tweets labeled as *Hate Speech*, *Offensive Language*, or *Neither*.
- **Preprocessing:** Includes text cleaning, stopword removal, stemming, and vectorization.
- **Machine Learning Model:** Uses a Decision Tree Classifier to classify tweets.
- **Evaluation:** Measures accuracy and confusion matrix for performance assessment.

## 🚀 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Hate-Speech-Detection.git
   cd Hate-Speech-Detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## 🏠 Usage
1. Run the model:
   ```sh
   python hate_speech_detection.py
   ```
2. Predict hate speech for a custom input:
   ```python
   sample = "Your custom tweet here"
   prediction = model.predict(sample)
   print(prediction)
   ```

## 📊 Results
- Achieved **88.5% accuracy** using a Decision Tree model.
- Displays a confusion matrix to visualize model performance.

