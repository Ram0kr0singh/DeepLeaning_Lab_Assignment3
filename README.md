## Text Sentiment Classification Using RNN and LSTM Overview

This project focuses on classifying text into different sentiments (such as positive, negative, or neutral) using deep learning techniques. It uses Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models to understand and analyze text data.

## Objective

The main objective of this project is to:

Analyze text data (like reviews or comments) Predict the sentiment of the text Compare the performance of RNN and LSTM models Technologies Used Python TensorFlow / Keras NumPy Pandas Matplotlib Dataset

The dataset contains text samples along with their corresponding sentiment labels (e.g., positive or negative). Example:

"This product is amazing!" → Positive "Worst experience ever" → Negative How It Works Data Preprocessing Cleaning text (removing punctuation, stopwords, etc.) Tokenization and padding Model Building RNN model for sequential data processing LSTM model to handle long-term dependencies Training Models are trained on labeled data Evaluation Accuracy and loss are used to evaluate performance Results Both models successfully classify sentiments LSTM generally performs better than basic RNN due to its ability to remember long-term dependencies How to Run

Install required libraries:

pip install tensorflow numpy pandas matplotlib

Run the Python script:

python main.py Conclusion

This project demonstrates how deep learning models like RNN and LSTM can be used for text sentiment analysis. LSTM provides better accuracy and performance compared to a basic RNN.

Future Improvements Use larger datasets Implement GRU models Improve accuracy with hyperparameter tuning Deploy as a web application

Ram Kumar Singh 2501940002
