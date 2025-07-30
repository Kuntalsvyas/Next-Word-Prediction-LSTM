# 🧠 Next Word Prediction using LSTM (RNN)

This project demonstrates **next-word prediction** using a **Long Short-Term Memory (LSTM)** neural network — a type of Recurrent Neural Network (RNN) well-suited for sequence modeling. It learns the structure of text and predicts the most likely next word based on previous input.

---

## 📊 Features

- 🧠 Trains an LSTM-based text prediction model
- 📚 Works with any large text corpus (e.g., books, articles)
- 🔁 Processes text using tokenization and sequence generation
- 💾 Saves trained model as `next_word_lstm_model.h5`
- 📈 Displays training loss during epochs

---

## 🧰 Tech Stack

- **Python 3.10+**
- **TensorFlow / Keras**
- **NumPy / Matplotlib**
- **NLTK / re** (for tokenization and cleaning)

---

## 📂 Dataset

- Uses a raw text file (`data.txt`) as input
- Data is tokenized and split into sequences
- Target is to predict the next word given a sequence of previous words

---

## 🚀 Installation


**1. Clone the repository**
- git clone https://github.com/Kuntalsvyas/Next-Word-Prediction-LSTM.git
- cd Next-Word-Prediction-LSTM

**2. Create a virtual environment**
- python -m venv venv
- source venv/bin/activate  # For Windows: venv\Scripts\activate

**3. Install required packages**
- pip install -r requirements.txt

**4. Train the model**
- python next_word_lstm.py

---

# 🧪 How It Works
- Preprocess text using NLTK and regular expressions
- Tokenize the corpus into word sequences
- Train an LSTM model on sequences
- Predict the next word when a sentence is partially entered

---

 # 📌 Future Improvements
 - Add a GRU or Transformer version for comparison
 - Streamlit-based UI for real-time word prediction
 - Text generation with temperature control and creativity modes

---

# 🙌 Author
Made with 💬 by Kuntal Vyas
If you liked this repo, give it a ⭐ and share it!
