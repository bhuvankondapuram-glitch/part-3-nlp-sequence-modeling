# NLP and Sequence Modeling Mini Project

## Project Overview

This project focuses on building a basic Natural Language Processing (NLP) pipeline using a customer support text classification dataset. The project compares traditional text vectorization methods with sequence-based deep learning approaches.

The main objective is to understand how textual data is converted into numerical representations and how sequence models like LSTM process text data.

---

# Dataset Information

Dataset Used:
- Customer Support Text Classification Dataset

Target Column:
- `sentiment_label`

Classes:
- Positive
- Neutral
- Negative

Input Feature:
- `customer_message`

Additional Columns:
- `channel`
- `word_count`
- `urgent_flag`

---

# Tasks Completed

## Task 1: Dataset Understanding

Performed:
- Dataset loading
- Record count analysis
- Target label analysis
- Sample text inspection
- Average text length calculation
- Class distribution visualization

---

## Task 2: Text Preprocessing

Applied preprocessing techniques:
- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal
- Sequence padding for LSTM model

---

## Task 3: Text Vectorization

Used:
- TF-IDF Vectorization
- Tokenizer-based Sequences

Why vectorization is required:
Machine learning models cannot understand raw text directly. Text data must be converted into numerical vectors before training models.

---

## Task 4: Baseline Model

Model Used:
- Logistic Regression

Vectorization Method:
- TF-IDF

Evaluation Metrics:
- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Task 5: Sequence Model

Sequence Model Used:
- LSTM (Long Short-Term Memory)

Architecture:
1. Embedding Layer
2. LSTM Layer
3. Dense Hidden Layer
4. Output Layer with Softmax Activation

Loss Function:
- Sparse Categorical Crossentropy

Optimizer:
- Adam

Evaluation Metric:
- Accuracy

---

## Task 6: Attention and Transformer Reflection

Covered concepts:
- Limitations of RNNs
- Importance of LSTMs
- Role of Attention Mechanism
- Importance of Transformers in Modern NLP

---

# Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

---

# Project Structure

```text
part-3-nlp-sequence-modeling/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
│
└── results/
    ├── model_evaluation.png
    └── sample_predictions.txt