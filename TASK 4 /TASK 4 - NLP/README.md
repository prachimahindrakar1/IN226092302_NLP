# BERT Fine-Tuning for Text Classification

## 📌 Project Overview
This project demonstrates fine-tuning a pre-trained BERT model (bert-base-uncased) on the IMDB movie reviews dataset for sentiment classification.

## 📊 Dataset
- IMDB Movie Reviews Dataset from Hugging Face
- Binary classification: Positive / Negative

## ⚙️ Workflow
- Data Preprocessing
- Tokenization using BERT tokenizer
- Train/Validation/Test split
- Model training using Hugging Face Trainer
- Evaluation using Accuracy, Precision, Recall, F1 Score
- Experiments:
  - Full Fine-tuning
  - Frozen BERT
  - Fine-tuning last 2 layers

## 🧪 Results Summary
- Full Fine-tuning achieved the best performance (~94% accuracy)
- Frozen BERT performed poorly due to lack of learning
- Partial fine-tuning gave a balance between performance and efficiency

## 🛠️ Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Scikit-learn
- Google Colab

## 🚀 How to Run
- Open the notebook in Colab or Jupyter
- Install required libraries
- Run cells sequentially

## 📎 Author
Your Name