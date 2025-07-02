# 🤖 Streamlit NLP Chatbot

A simple NLP-based chatbot built using TensorFlow, NLTK, and Streamlit. It classifies user input into predefined intents and returns an appropriate response.

---

## 🔧 Tools Used

- Python
- Streamlit
- TensorFlow
- NLTK
- NumPy
- Pickle
- JSON

---

## ✨ Features

- Intent-based NLP chatbot
- Tokenization and lemmatization using NLTK
- Deep learning model with TensorFlow
- Clean and simple UI using Streamlit
- Commands supported:
  - `time` → Show current time
  - `search <query>` → Google search
  - `exit`, `quit`, `bye` → End the conversation

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

> ⚠️ **Note**: If you face errors related to TensorFlow version, ensure your Python version is compatible (e.g., Python 3.10 for TensorFlow 2.19).

### 3. Train the Model (if not already trained)

```bash
python train_chatbot.py
```

This will create:
- `chatbot_model.h5`
- `words.pkl`
- `classes.pkl`

### 4. Run the Streamlit App

```bash
streamlit run gui2.py
```

The chatbot will open in your browser at `http://localhost:8501`

---

## 📁 Project Structure

```
.
├── gui2.py               # Streamlit app
├── train_chatbot.py      # Model training script
├── intents.json          # Intent dataset
├── words.pkl             # Vocabulary file
├── classes.pkl           # Output labels
├── chatbot_model.h5      # Trained model
├── requirements.txt
└── README.md
```

---

## 🌐 Deploy on Render

- **Start Command**: `streamlit run gui2.py`
- **Build Command**: *(leave blank or)* `pip install -r requirements.txt`
- **Python Version**: Add `runtime.txt` with `python-3.10`
- **Environment Variables**: Not required

---

