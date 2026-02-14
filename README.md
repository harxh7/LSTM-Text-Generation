📚 Next Word Prediction using LSTM (Deep Learning)
🚀 Project Overview

This project implements a Next Word Prediction Model using Deep Learning techniques with TensorFlow and Keras. The model is trained on multiple literary text datasets to learn language patterns and predict the next word in a sequence.

The objective of this project is to build a neural network capable of understanding contextual relationships in text and generating meaningful next-word predictions.

📂 Dataset Used

The model is trained using the following text datasets:

books.veryshort.txt

pride-prejudice.txt (by Jane Austen)

the-book-thief.txt

These datasets provide diverse vocabulary and writing styles, helping the model learn broader language patterns.

🧠 Model Architecture

The model is built using a Sequential architecture with:

Embedding Layer – Converts words into dense vector representations

LSTM Layer (150 units) – Captures long-term dependencies

Dropout Layer (0.2) – Prevents overfitting

LSTM Layer (100 units) – Further sequence learning

Dense Output Layer (Softmax) – Predicts the probability of the next word

Loss Function:
sparse_categorical_crossentropy

Optimizer:
Adam

🔄 Workflow

Text preprocessing (cleaning and tokenization)

Converting text into sequences

Padding sequences to equal length

Splitting predictors (X) and label (y)

Training LSTM model

Generating next-word predictions

🛠 Technologies Used

Python

TensorFlow / Keras

NumPy

NLP preprocessing techniques

📈 Key Features

Efficient memory handling using sparse categorical crossentropy

Deep LSTM architecture for sequence modeling

Multi-dataset training for better vocabulary learning

Capable of generating human-like next word predictions

💡 Example Usage

Input:

The sun was shining


Output:

brightly

📌 Future Improvements

Add GRU layers for comparison

Implement attention mechanism

Use larger datasets

Deploy as a web application using Flask or FastAPI

🎯 Conclusion

This project demonstrates how Recurrent Neural Networks, specifically LSTMs, can effectively model sequential text data and predict the next word in a sentence. By training on multiple literary datasets, the model learns contextual relationships and language structure. This serves as a foundational step toward advanced applications like text generation, chatbots, and language modeling systems.
