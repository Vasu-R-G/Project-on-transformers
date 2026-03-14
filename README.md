# 📰 Fake News Detection in the Syrian War (FA-KES Dataset)

This project implements a **BERT-based Deep Learning model** to classify news articles as either **Reliable (0)** or **Fake (1)**. The model is specifically fine-tuned on the **FA-KES dataset**, which focuses on news reporting during the Syrian conflict.

## 🎯 Problem Statement
Misinformation during wartime can have severe real-world consequences. This project aims to build an automated system that analyzes the content and context of war-related news articles to identify fabricated reports using state-of-the-art Natural Language Processing (NLP).

## 📊 Dataset Description: FA-KES
The **FA-KES dataset** is a specialized collection of news articles concerning the Syrian war.
- **Total Samples:** ~800 labeled articles.
- **Input Features:** `article_title`, `article_content`.
- **Labels:** - `0`: Real / Reliable News
  - `1`: Fake / Unreliable News
- **Source:** Ground truth was established using the Syrian Violations Documentation Center (VDC).

## 🛠️ Tech Stack & Model
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries:** PyTorch, HuggingFace Transformers, Pandas, Scikit-learn
- **Model:** `bert-base-uncased` (Fine-tuned for Sequence Classification)
- **Deployment:** Gradio (Web Interface)

## 🚀 Key Results
| Metric | Value |
| :--- | :--- |
| **Accuracy** | [0.95] |
| **Precision** | [0.55] |
| **Recall** | [1.00] |
| **F1-Score** | [0.71] |

> **Note:** BERT's self-attention mechanism allows the model to understand the subtle linguistic patterns and propaganda techniques often found in war-related misinformation, leading to higher accuracy than traditional ML models.

## 🛠️ How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Fake-News-FAKES.git](https://github.com/YOUR_USERNAME/Fake-News-FAKES.git)
