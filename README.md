# Sentiment-Analysis-ML-model
This project classifies IMDB movie reviews as positive or negative using an LSTM model. It preprocesses text via tokenization &amp; padding, then trains an LSTM-based neural network with embedding layers. Achieves ~87% accuracy and includes a real-time prediction function. Built with TensorFlow, Keras, and Pandas. 🚀
IMDB Sentiment Analysis using LSTM
📌 Project Overview
This project implements a sentiment analysis model on the IMDB movie reviews dataset using deep learning. It utilizes LSTM (Long Short-Term Memory) networks, a type of recurrent neural network (RNN), to classify movie reviews as positive or negative. The model is built using TensorFlow & Keras, with text preprocessing done using Tokenization and Padding.

🛠️ Tech Stack
Programming Language: Python
Libraries: TensorFlow, Keras, Pandas, NumPy, Scikit-learn
Deep Learning Model: LSTM
Text Processing: Tokenization, Sequence Padding
🚀 Project Workflow
Data Loading: Load the IMDB dataset (IMDB Dataset.csv).
Preprocessing:
Convert text reviews into numerical sequences using Tokenization.
Apply sequence padding to standardize input size.
Convert labels ('positive', 'negative') to binary values (1, 0).
Splitting Dataset: Split the dataset into train and test sets using train_test_split().
Model Building:
Use an Embedding Layer to create word vector representations.
Implement an LSTM layer for capturing sequential text patterns.
Add a Dense layer with a sigmoid activation function for binary classification.
Training the Model:
Compile the model using the Adam optimizer and binary cross-entropy loss.
Train for 5 epochs with validation.
Evaluation:
Evaluate the model on the test dataset to check accuracy & loss.
Prediction Function:
Implement a function to classify new reviews as positive or negative.
📊 Model Performance
Achieved ~87% accuracy on the test set.
Successfully predicts sentiment for new reviews.
💡 Key Features
✅ Deep Learning-based Sentiment Analysis
✅ LSTM model for handling sequential text data
✅ Preprocessing with Tokenization & Padding
✅ Efficient training with TensorFlow/Keras
✅ Real-time prediction of movie review sentiment
