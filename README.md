# 📚 Character-Level Text Generation using GRU

This project is part of my NLP deep learning journey where I built a character-level text generator trained on Shakespeare's works using a **GRU (Gated Recurrent Unit)** neural network. The model learns the patterns of text at the character level and generates new text that mimics Shakespearean style.

## 🚀 Project Overview

The objective is to demonstrate how recurrent neural networks can learn character sequences from scratch and generate realistic, stylistic text. This can serve as a foundation for more advanced NLP models like Transformers.

## 🛠️ Features

- Character-level text modeling using **GRU**
- Trained on the **Shakespeare corpus**
- Implemented using **TensorFlow and Keras**
- Temperature-controlled sampling for creative text generation
- Fully reproducible training and generation pipeline

## 📊 Dataset

- Source: [Shakespeare Text Dataset](https://www.kaggle.com/datasets/kingburrito666/shakespeare-plays)
- Preprocessed to create input sequences and labels at the character level

## 🧠 Model Details

- Architecture: Single-layer GRU followed by Dense layer
- Sequence length: 100 characters
- Embedding layer: Optional but used for character encoding
- Training Epochs: **50**
- Training Time: **~4 hours** on CPU
- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam

## 📝 How It Works

1. Load and preprocess the text into character sequences.
2. Vectorize the text using character-to-index mappings.
3. Train a GRU model to predict the next character given a sequence.
4. Generate text using the trained model and a temperature-based sampling technique.

## 🔥 Sample Generated Output

> “to be or not to be. my lord, i shall speak thou word with great honour and pride...”

## 🧪 Installation

```bash
git clone https://github.com/AADARSHA875/character_level_text_generation.git
cd character_level_text_generation
pip install -r requirements.txt
