# NLP-Model-Sentiment-Analysis-using-LSTM

Project Objective

Build a Deep Learning NLP model using LSTM (Long Short-Term Memory) to classify movie reviews as:

Positive Sentiment (1)
Negative Sentiment (0)

using the IMDB dataset.


Performance Analysis

1. Impact of Sequence Length
Short sequence length may truncate important information.
Very long sequences increase training time.
200 words provided a good balance between performance and computation.
2. Importance of Embedding Layer
Converts words into dense vectors.
Captures semantic relationships.
Improves contextual understanding compared with BoW and TF-IDF.
3. Effect of LSTM Memory Cells
Stores long-term dependencies.
Understands context across lengthy reviews.
Handles sequential text better than basic RNN.
4. Overfitting and Solutions

Possible Solutions:

Dropout Layers
Early Stopping
More Training Data
L2 Regularization
Reduce Model Complexity

5. Limitations
Training takes longer than traditional ML models.
Performance depends on sequence length.
Vocabulary size restricts unseen words.
Large memory usage for long reviews.
