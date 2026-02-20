# 🚀 Named Entity Recognition (NER) using BERT

This project implements a complete Named Entity Recognition (NER) pipeline using a transformer-based model (BERT).

The goal was to move beyond tutorials and understand the full fine-tuning process, including tokenization, label alignment, training, and evaluation.

---

## 📌 Project Overview

Named Entity Recognition (NER) is a sequence labeling task where the model identifies entities in text such as:

- Person
- Organization
- Location
- Date
- Miscellaneous entities

This project fine-tunes a pretrained BERT model for token classification.

---

## 🏗️ Pipeline Architecture

1. Load NER dataset  
2. Tokenize text using BERT tokenizer  
3. Align word-level labels to subword tokens  
4. Convert labels to token classification format  
5. Fine-tune BERT using Hugging Face Trainer  
6. Evaluate model performance  
7. Perform inference on custom sentences  

---

## 🧠 Key Technical Concepts Implemented

- Subword tokenization
- Label alignment for token classification
- Use of `DataCollatorForTokenClassification`
- Fine-tuning `bert-base-uncased`
- Trainer API for training and evaluation

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Hugging Face Transformers
- Datasets library
- Google Colab

---

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Install dependencies:
   ```
   !pip install -U transformers datasets seqeval -q
   ```
3. Run all cells sequentially.

---

## 📊 Model

Pretrained model used:
- `bert-base-uncased` (fine-tuned for token classification)

---

## 🔗 Notebook
https://colab.research.google.com/drive/1ZIGpFc7Pu6oy_MZHbQWbC1vkpCmtKWfa?usp=sharing

You can open and run the notebook directly in Google Colab.
