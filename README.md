# LSTM-RNN--Next-word-prediction
A Deep Learning project that predicts the next word in a sequence using LSTM (Long Short-Term Memory) Recurrent Neural Networks built with TensorFlow/Keras and deployed using Streamlit.

Project Overview:

This project trains an LSTM-based language model on text data to predict the next word given an input sequence.

Example:

Input:I love deep

Output:learning

The model learns contextual relationships between words using sequential modeling.

Tech Stack: Python 3.10+, TensorFlow / Keras, NumPy, Streamlit,Pickle

Project Structure
LSTM-RNN-Next-word-prediction/

app.py                 # Streamlit web app
model.h5               # Trained LSTM model
tokenizer.pkl          # Saved tokenizer
requirements.txt       # Dependencies
README.md
 
Model Architecture: Embedding Layer, LSTM (150 units, return_sequences=True), Dropout (0.2)
, LSTM (100 units), Dense (Softmax activation)

Loss Function: categorical_crossentropy

Optimizer: Adam

Training Process

Text preprocessing

Tokenization

Sequence generation

Padding sequences

One-hot encoding of labels

Model training

Save model + tokenizer

🚀 How to Run the Project
1️⃣ Clone Repository
git clone https://github.com/your-username/LSTM-RNN-Next-word-prediction.git
cd LSTM-RNN-Next-word-prediction
2️⃣ Create Virtual Environment
python -m venv venv
venv\Scripts\activate
3️⃣ Install Dependencies
python -m pip install -r requirements.txt
4️⃣ Run Streamlit App
python -m streamlit run app.py

Open browser:

http://localhost:8501
 Features

Interactive web interface

Real-time next word prediction

Pre-trained LSTM model

Clean UI with Streamlit

Future Improvements: Add Transformer-based model, Improve dataset size, Deploy on AWS / HuggingFace Spaces.
