# 🎬 IMDB Sentiment Analysis with RNN 💭📈

Welcome to my **first NLP project using Recurrent Neural Networks (RNN)** where I analyze 50,000 IMDB reviews to determine if they express a **positive 😊 or negative 😡 sentiment**.

This project is **deployed using Streamlit** for an interactive web experience!

---

## 🚀 Project Highlights

- 🧠 Built an RNN-based model using TensorFlow/Keras
- 📊 Trained on the IMDB dataset with **50,000** labeled reviews
- 📈 Achieved ~**80% accuracy** on the test set
- 🧼 Preprocessing included padding, tokenization, and vocabulary trimming
- 🌐 **Deployed on Streamlit** for real-time sentiment prediction!

---

## 🛠️ Tech Stack

- Python 🐍  
- TensorFlow / Keras  
- Numpy / Matplotlib / Seaborn  
- Streamlit  
- Git & GitHub  

---

## ⚙️ How to Run the App Locally

1. Clone the repo  
   ```bash
   git clone https://github.com/priya-200/IMDB-Reviews-Analysis.git
   cd IMDB-Reviews-Analysis
2. To create a Virtual environment
   ```bash
   python -m venv venv
   venv\Scripts\activate  # On Windows
3. Install the requirements
   ```bash
   pip install -r requirements.txt
4. Run Streamlit
   ```bash
   Streamlit run app.py

## ✨ Demo
Try it yourself! Paste a review like:
"This movie was a total masterpiece. The emotions, the music, everything was on point!"
…and the model will instantly predict the sentiment!

##📚 Dataset

Used the built-in IMDB dataset from TensorFlow Datasets:
25,000 training + 25,000 testing reviews

## 📌 Future Improvements

1. Try Bidirectional LSTM or GRU for better accuracy
2. Add visualizations for word embeddings
3. Deploy using Hugging Face Spaces or Docker


