
# Transformer-Based Next-Token Prediction Using Self-Attention

## 📌 Project Description
This project develops a Transformer-based next-token prediction model using basic self-attention. The model is trained on a small text dataset to learn word patterns and predict the next word based on user-entered text.

## 🎯 Objectives
- Understand the basic working of self-attention.
- Prepare text data for next-token prediction.
- Build a Transformer model using TensorFlow and Keras.
- Train the model to predict the next word.
- Allow users to enter their own text and get a prediction.
- Display the predicted word and model confidence.

## 🛠️ Technologies Used
- Python
- NumPy
- TensorFlow and Keras
- Matplotlib
- IPython Widgets
- Google Colab / Jupyter Notebook

## 📊 Dataset
The model uses a small, predefined collection of text sentences related to animals, nature, programming, machine learning, and artificial intelligence.

- **Task:** Next-token prediction
- **Input:** A user-entered sentence or phrase
- **Output:** Predicted next word
- **Maximum context length:** 6 tokens
- **Embedding dimension:** 32
- **Number of attention heads:** 2

## 🧠 Model Architecture
The model consists of the following components:

1. **Tokenization:** Converts words into numerical token IDs.
2. **Training Data Preparation:** Creates input sequences and their corresponding next-token targets.
3. **Token and Position Embedding:** Represents words and their positions.
4. **Multi-Head Self-Attention:** Learns relationships between tokens using causal masking.
5. **Residual Connections and Layer Normalization:** Helps process the learned representations.
6. **Feed-Forward Network:** Learns additional patterns in the input.
7. **Output Layer:** Uses Softmax to predict the next token.

## ⚙️ Model Configuration
- **Framework:** TensorFlow / Keras
- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Cross-Entropy
- **Epochs:** 100
- **Batch Size:** 16
- **Validation Split:** 10%

## 🔄 Implementation Steps
1. Import the required libraries.
2. Define the training sentences.
3. Tokenize the text.
4. Generate input and next-token target sequences.
5. Build the Transformer model with causal self-attention.
6. Compile and train the model.
7. Visualize training and validation accuracy.
8. Accept text through an interactive input box.
9. Predict the next word using the trained model.
10. Display the predicted word and model confidence.

## 🚀 How to Run the Project

### Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `Transformer1.ipynb` notebook.
3. Run all cells in order.
4. Wait for the model training to complete.
5. Enter a sentence in the input box.
6. Click **Predict Next Word** to view the result.

### Local Installation
Install the required libraries:

```bash
pip install numpy tensorflow matplotlib ipywidgets
```

Open the notebook in Jupyter Notebook and run all cells.

## 📈 Expected Output
- Vocabulary size
- Transformer model summary
- Training progress
- Training and validation accuracy graph
- User input sentence
- Predicted next word
- Model confidence percentage

Example:

```text
Input sentence: the cat is
Predicted next word: sleeping
Model confidence: [model-generated percentage]
```

*The predicted word and confidence depend on the trained model. The example above is illustrative.*

## ⚠️ Limitations
- The model is trained on a small, predefined dataset.
- Predictions are limited by the words and patterns learned during training.
- Unknown words are ignored during prediction.
- The confidence percentage represents the model's predicted probability, not guaranteed accuracy.
- The model is intended for educational purposes and is not a production-scale language model.

## ✅ Conclusion
This project demonstrates how a basic Transformer model uses causal self-attention to learn text patterns and predict the next word. It provides practical experience in tokenization, embeddings, attention mechanisms, model training, and interactive text prediction.

## 👩‍💻 Project Information
- **Project Type:** Deep Learning / Natural Language Processing
- **Model:** Transformer
- **Core Concept:** Self-Attention
- **Task:** Next-Token Prediction
- **Framework:** TensorFlow and Keras
