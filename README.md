# 📰 Fake News Detection with Machine Learning

A web-based application to detect fake news using Natural Language Processing (NLP), TF-IDF vectorization, readability scores, and a Random Forest classifier. Deployed using **Streamlit**, **Gradio**, and **Flask on Render**.

---

## 🚀 Live Demo

- **🔗 Streamlit App**: [https://your-username-your-app-name.streamlit.app](https://your-username-your-app-name.streamlit.app)
- **🔗 Gradio (Hugging Face Spaces)**: [https://huggingface.co/spaces/your-username/fake-news-detector](https://huggingface.co/spaces/your-username/fake-news-detector)
- **🔗 Flask on Render**: [https://your-app-name.onrender.com](https://your-app-name.onrender.com)

---

## 📸 Screenshot

### Streamlit UI:
![Streamlit Screenshot](screenshots/streamlit_ui.png)

### Gradio UI:
![Gradio Screenshot](screenshots/gradio_ui.png)

---

## 🧠 Model Overview

- **TF-IDF Vectorization**: Extracts textual features from news content.
- **Readability Score**: Adds Flesch Reading Ease as a linguistic feature.
- **Model**: Random Forest Classifier trained on sample fake/real news articles.

---

## 🗃️ Features

- ✅ Clean and preprocess news content
- ✅ Predict whether an article is **FAKE** or **REAL**
- ✅ Web-based UI (HTML/Flask, Streamlit, and Gradio)
- ✅ Easy deployment on free platforms

---

## 🛠️ Tech Stack

| Component        | Tool                      |
|------------------|---------------------------|
| Model Training   | Scikit-learn, TextStat    |
| Feature Extraction | TF-IDF, Flesch Score     |
| Backend          | Flask / Streamlit / Gradio|
| Deployment       | Render / Streamlit Cloud / Hugging Face Spaces |
| Language         | Python 3.8+               |

---

## 🧪 Sample Prediction

**Input:**
> *"Breaking: Scientists discover cure for cancer."*

**Output:**
> Prediction: **FAKE**

---

## 📦 Setup Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/fake-news-detector.git
cd fake-news-detector
