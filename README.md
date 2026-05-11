**Overview**

PassGuard is an AI-powered password strength prediction system that uses Deep Learning (CNN + BiLSTM hybrid model) to classify passwords into:

🔴 Weak
🟡 Medium
🟢 Strong

Unlike traditional rule-based password checkers, this system learns patterns from data and evaluates password security using contextual and structural features.

**Problem Statement**

Weak passwords are one of the leading causes of cybersecurity breaches. Traditional systems rely on simple rules (length, digits, symbols), which are not sufficient against modern attack techniques like:

Brute Force Attacks
Dictionary Attacks
Hybrid Cracking Methods

This project solves that problem using AI-based intelligent classification.

**Features**

Deep Learning Model (CNN + BiLSTM Hybrid)
Entropy-based password analysis
Handles real + synthetic dataset (RockYou + generated data)
Multi-class classification (Weak, Medium, Strong)
Real-time password prediction
Interactive Gradio Web UI
Visual training insights (accuracy/loss graphs, confusion matrix)

**Tech Stack**

Python 🐍
TensorFlow / Keras
NumPy & Pandas
Scikit-learn
Gradio UI
Matplotlib & Seaborn

**Model Architecture**

Embedding Layer
CNN (feature extraction)
BiLSTM (sequence learning)
Dense layers for classification
Softmax output (3 classes)

**Dataset**

RockYou Dataset (real-world leaked passwords)
Synthetic dataset for balancing:
Weak passwords
Medium complexity passwords
Strong generated passwords
