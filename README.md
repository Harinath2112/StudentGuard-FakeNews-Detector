# StudentGuard-FakeNews-Detector
A machine learning-powered tool designed for students to detect misinformation and verify the credibility of news articles using Natural Language Processing (NLP).
# Student Guardian: AI-Powered Fake News Detector

## 📌 Project Overview
Misinformation spreads quickly through online news and social media, making it difficult for students to differentiate between reliable and fake information. [cite_start]This project provides an AI solution that analyzes news articles, assesses credibility, and helps prevent the spread of false information[cite: 8, 9].

This tool uses **Machine Learning** and **Natural Language Processing (NLP)** to classify news as either **REAL** or **FAKE** based on historical patterns in journalism.

## 🛠️ Features
- **Real-time Detection:** Paste any news article and get an instant authenticity report.
- **Interactive UI:** Built using Jupyter Notebook and IPyWidgets for a user-friendly experience.
- **High Accuracy:** Trained on the ISOT Fake News Dataset (Reuters news vs. flagged misinformation).

## 🧰 Tech Stack
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** - `Pandas` (Data manipulation)
  - `Scikit-Learn` (Machine Learning)
  - `TfidfVectorizer` (Text processing)
  - `PassiveAggressiveClassifier` (Classification model)
  - `IPyWidgets` (Interactive UI)

## 🚀 How It Works
1. **Data Preprocessing:** The system merges datasets of real and fake news, cleaning the text and removing "stop words."
2. **Feature Extraction:** We use **TF-IDF (Term Frequency-Inverse Document Frequency)** to convert text into numerical vectors.
3. **Training:** The **PassiveAggressiveClassifier** is trained on thousands of articles. It is ideal for large-scale text classification because it stays passive for correct predictions but aggressively updates for incorrect ones.
4. **Interface:** A custom-built text area allows users to input news and receive a prediction.

## 📂 Dataset Information
This project utilizes the **ISOT Fake News Dataset**, which contains:
- **True.csv**: Over 12,600 factual articles from Reuters.com.
- **Fake.csv**: Over 12,600 articles flagged as misinformation by fact-checking organizations like Politifact.

## 📂 Dataset Information
Due to file size limitations (>25MB), the raw CSV files are not hosted directly in this repository. You can download the official **ISOT Fake News Dataset** from the following link:

- **Download Link:** [ISOT Fake News Dataset (Kaggle)](https://www.kaggle.com/datasets/emineyetm/fake-news-detection-datasets)
- **Files Required:** - `True.csv`: factual articles from Reuters.com.
  - `Fake.csv`: articles flagged as misinformation.

> **Note:** After downloading, please place both `.csv` files in the root directory of this project so the Jupyter Notebook can locate them.

## 📝 How to Run
1. Clone this repository.
2. Download `True.csv` and `Fake.csv` from Kaggle and place them in the project directory.
3. Open `Fake_News_Detector.ipynb` in Jupyter Notebook or VS Code.
4. Run all cells to train the model and launch the interactive checker.

---

### 👤 Developer Info
- **Name:** Harinath
- **Focus:** Data Science & Machine Learning
- **Email:** kurapatiharinath5@gmail.com
