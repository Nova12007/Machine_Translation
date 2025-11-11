# Machine Translation — CS779 Course Project  

This repository contains my course project for **CS779**, focused on **Neural Machine Translation (NMT)** using a **Transformer-based architecture**.  
It includes the **project report** and the **code implementation** of the best-performing model, which leverages **self-attention** and **positional encoding** for efficient sequence modeling.

---

## Project Overview  
The goal of this project was to develop a deep learning model capable of translating text between languages using advanced attention mechanisms.  
Multiple models were evaluated, and the **Transformer model** achieved the **best BLEU score**, demonstrating superior ability to capture long-range dependencies without recurrence.

The project highlights how attention-only architectures outperform traditional RNN- and LSTM-based models in both accuracy and training efficiency.

---

## Model Summary: Transformer Architecture  
The **Transformer** model is built entirely on the **self-attention mechanism**, eliminating the need for recurrent or convolutional structures.  

**Key features include:**
- Multi-head self-attention for contextual representation  
- Positional encoding to retain sequence order information  
- Encoder-decoder structure for language translation  
- Layer normalization and residual connections for stable training  
- BLEU score and loss-based evaluation for translation performance  

---
