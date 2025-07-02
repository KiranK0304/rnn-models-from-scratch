# RNN Models from Scratch 🔁🧠

This repository explores Recurrent Neural Networks built from the ground up using Python and PyTorch.

## 🔧 Projects Included

### 1. `victor_rnn/`
An RNN implementation based on [Victor Zhou's guide](https://victorzhou.com/blog/intro-to-rnns/), used to predict sequences of characters. Demonstrates:
- Character-level RNN training
- Forward pass and backpropagation through time (BPTT)
- Manual training loop

### 2. `makemore_rnn/`
An extension of Karpathy’s "makemore" model re-implemented as a vanilla RNN:
- Handles sequences like names or words
- Manual backpropagation and hidden state update
- Trained on a `names.txt` dataset

## 🚀 Goals

- Learn the internals of RNNs without black boxes
- Practice backpropagation through time (BPTT)
- Understand sequential data modeling at a low level

## 📦 Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install torch matplotlib
