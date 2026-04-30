# Transformer-Based German to English Language Translator

This project implements a Neural Machine Translation (NMT) system that translates German text into English using the full Transformer architecture, as introduced in the landmark paper Attention Is All You Need.

Unlike traditional sequence models (RNNs/LSTMs), this model relies entirely on self-attention mechanisms to capture contextual relationships between words, enabling more efficient parallelization and improved translation quality.

🔍 Key Features:

Complete encoder-decoder Transformer architecture
Multi-head self-attention for capturing semantic relationships
Positional encoding to retain sequence order information
Scaled dot-product attention implementation
Custom tokenization and vocabulary pipeline
Training with teacher forcing and masked attention
Evaluation using translation quality metrics (e.g., BLEU score)

⚙️ Tech Stack:

Python
PyTorch
NumPy
NLP preprocessing tools

📊 Objective:
To deeply understand and implement modern NLP architectures by building a translation model from scratch, demonstrating how attention mechanisms outperform traditional sequential models in language translation tasks.

💡 Learning Outcomes:

In-depth understanding of attention mechanisms and Transformer internals
Hands-on experience with sequence-to-sequence modeling
Practical knowledge of machine translation workflows
