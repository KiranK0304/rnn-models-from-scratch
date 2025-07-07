# Multilayer GRU with Batch Normalization on Karpathy Name Dataset

This project implements a **character-level language model** trained on [Andrej Karpathy's Names Dataset](https://github.com/karpathy/char-rnn), with a strong emphasis on **manual architecture design** and **efficient computation** using only the essential components of PyTorch.

## 🚀 Key Features

- ✅ **Multilayer GRU (Gated Recurrent Unit)** network built from scratch
- ✅ **Batch Normalization inside GRU cells**, custom-implemented and deeply integrated
- ✅ Efficient **vectorized operations** for fast forward and backward passes
- ✅ Manual loop-based training with explicit tensor operations
- ✅ Uses only **PyTorch Tensors and Autograd** – *no torch.nn, no torch.optim, no high-level API*
- ✅ Trained on the real-world character-level dataset of names for sequence modeling

## 📚 Dataset

The dataset consists of thousands of human names from multiple cultures, allowing the model to learn the structure of names and generate new, realistic samples.

## 🎯 Objectives

- Build deep learning components manually to understand their inner workings
- Explore the behavior and benefits of **batch normalization inside recurrent networks**
- Learn to handle multi-layer recurrent models and custom training pipelines using only PyTorch low-level APIs
- Compare and experiment with different architectural designs from the ground up

## 🧠 Why This Project Matters

This project is a stepping stone toward truly mastering deep learning. Instead of relying on ready-made building blocks, this codebase **forces an understanding** of what actually happens under the hood when we train recurrent models.

It's also a great preparation for exploring more advanced areas like transformers, optimization tricks, and performance engineering.

## 📂 Folder Structure

