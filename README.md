# LSTM Next Word Prediction using PyTorch

## 📌 Project Description

This project implements **Next Word Prediction using LSTM (Long Short-Term Memory)** in PyTorch. The model is trained on sentences and learns to **predict the next word** based on previous words. LSTM is used because it can understand **sequence data and long-term dependencies** better than traditional neural networks.

Example:
Input: *the dog*
Output: *runs fast today*

---

## 🧠 What is LSTM?

LSTM (Long Short-Term Memory) is a type of **Recurrent Neural Network (RNN)** designed to remember long-term information in sequences. It maintains:

* **Hidden State (Short-term memory)** — current context
* **Cell State (Long-term memory)** — long-term knowledge

This helps the model understand sentence meaning and predict the next word.

---

## 🏗️ Model Architecture

Input Words → Embedding Layer → LSTM Layer → Linear Layer → Next Word Prediction

### Layers Used

* **Embedding Layer** — converts words into vectors
* **LSTM Layer** — learns sequence relationships
* **Linear Layer** — predicts next word

---

## ⚙️ Technologies Used

* Python
* PyTorch
* LSTM
* NLP
* Word Embedding

---

## 📂 Project Workflow

### Step 1: Data Preparation

Sentences are converted into input-target pairs:

I → love
I love → machine
I love machine → learning

---

### Step 2: Model Training

The model learns:

* Word relationships
* Sentence structure
* Next word prediction

---

### Step 3: Prediction

Input:
the dog

Predicted Output:
runs
fast
today

Final Sentence:
the dog runs fast today

---

##  Input Shape

(batch_size , sequence_length)

Example:
[[the , dog , runs]]

---

##  Output Shape

(batch_size , vocab_size)

Model predicts probability of next word.

---

##  Key Concepts

* Word Embedding
* LSTM
* Hidden State
* Cell State
* Sequence Learning
* Next Word Prediction

---

##  Applications

* Text Generation
* Chatbots
* Auto-completion
* Language Modeling
* NLP Applications

---

##  Future Improvements

* Use larger dataset
* Add GRU model
* Add Transformer model
* Use pretrained embeddings

---

##  Author

Sandy
Deep Learning | NLP | PyTorch
