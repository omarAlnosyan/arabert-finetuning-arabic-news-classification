# AraBERT Arabic News Classifier

Fine-tuned AraBERT model for classifying Arabic news articles into 7 categories with 95%+ accuracy.

---

## 🎯 Overview

Classifies Arabic news into:
- Sports
- Politics  
- Finance
- Medical
- Tech
- Culture
- Religion

---

## 📊 Performance

- **Accuracy**: 95%+
- **Dataset**: 45,500 Arabic articles
- **Training Time**: 35 minutes (T4 GPU)
- **Epochs**: 3

---

## 📦 Requirements

- Python 3.8+
- PyTorch
- Transformers
- Datasets

---

## 📂 Files

- `fine-tuning-news_classfction.ipynb` - Complete training notebook
- `best_arabert_model.pt` - Trained model weights
- `README.md` - Documentation

---

## 🚀 How to Use

1. Install dependencies
2. Load the notebook in Google Colab
3. Run all cells
4. Use the model for predictions

Full instructions in the notebook.

---

## 🙏 Acknowledgments

- **Model**: [AraBERT v2](https://github.com/aub-mind/arabert)
- **Dataset**: [SANAD Arabic News](https://huggingface.co/datasets/Hamza1001/sanad)
- **Framework**: Hugging Face Transformers

