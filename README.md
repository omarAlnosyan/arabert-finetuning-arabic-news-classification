# AraBERT Arabic News Classifier

Fine-tuned AraBERT model for classifying Arabic news articles into 7 categories with 95%+ accuracy.

---

## 🎯 Overview

Classifies Arabic news into:
- Sports | رياضة
- Politics | سياسة
- Finance | اقتصاد
- Medical | طب
- Tech | تكنولوجيا
- Culture | ثقافة
- Religion | دين

---

## 📊 Performance

- **Accuracy**: 95%+
- **Dataset**: 45,500 Arabic articles (SANAD)
- **Training Time**: 35 minutes on T4 GPU
- **Base Model**: AraBERT v2

---

## 🚀 How to Use

### Step 1: Open in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR-USERNAME/arabert-finetuning-arabic-news/blob/main/fine-tuning-news_classfction.ipynb)

### Step 2: Run All Cells

The notebook will:
1. Download the SANAD dataset
2. Fine-tune AraBERT (3 epochs, ~35 mins)
3. Save the trained model
4. Test on example
