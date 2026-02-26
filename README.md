# 🚀 Seq2Next: Next Word Prediction using LSTM on WikiText-2 Dataset

---

<div align="center">

| **👨‍💻 Author** | **🛠️ Technology Stack** | **📚 Dataset** | **📈 Key Highlights** |  
|:---------------:|:-----------------------:|:-------------:|:--------------------:|  
| Anuj Hansda    | Python, TensorFlow, Keras, NumPy, Pandas | WikiText-2 (Raw) | Tokenization & Sequence Generation<br>LSTM-based Language Model<br>Interactive Next-Word Prediction |
</div>

---

Seq2Next is a deep learning project focused on building a **next-word predictor** trained on the **WikiText-2 raw** dataset — a large corpus of English Wikipedia articles. It uses LSTM networks to learn context and predict the most probable next word, useful for text generation and language modeling applications.

---

## ✨ Key Features

- Utilizes the **WikiText-2 raw** dataset with 2+ million tokens of natural language text  
- Converts raw text into tokenized input sequences for supervised next-word prediction  
- Designed and trained an LSTM model to capture long-term dependencies in language  
- Visualizes training progress with loss curves and prediction confidence plots  
- Implements stepwise next-word generation from seed text with padded sequences  

---

## 📸 Visual Overview

<div align="center">

| ![Seq1](https://github.com/anuj-hmm/Seq2Next/blob/main/Seq1.png) | ![Training Loss](https://github.com/anuj-hmm/Seq2Next/blob/main/seq3.png
) | ![Word Probabilities](https://github.com/anuj-hmm/Seq2Next/blob/main/seq4.png) |
|:-------------------------------------------------------------:|:------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| Dataset Sample & Tokenization                                  | Training Loss over Epochs                                           | Predicted Next Word Probability Distribution                            |

| ![Sample Predictions](https://github.com/anuj-hmm/Seq2Next/blob/main/seq5.png) | ![Model Architecture](https://github.com/anuj-hmm/Seq2Next/blob/main/seq6.png) |
|:---------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|
| Example Next-Word Predictions                                               | Model Summary and Layer Details                                              |

</div>

---

## 🏃‍♂️ How to Use

1. Download and preprocess the WikiText-2 raw dataset.  
2. Generate tokenized sequences for training the LSTM model.  
3. Train the model with your preferred hyperparameters.  
4. Use the model to predict the next word from any input text sequence.

---

## 📈 Results Summary

- Demonstrates consistent training loss decrease, confirming effective learning on WikiText-2.  
- Prediction probabilities provide meaningful and contextually relevant next word suggestions.  
- Generated text sequences showcase model’s ability to capture natural language patterns from Wikipedia articles.

---

## 🤝 Contributing

Contributions and feedback are welcome! Fork the repo, open issues, or submit pull requests.


*Thank you for exploring Seq2Next trained on WikiText-2!*  

