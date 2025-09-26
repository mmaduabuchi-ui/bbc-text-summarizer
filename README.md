# 📰 BBC News Text Summarization

## 📌 Project Overview
This project applies **Natural Language Processing (NLP)** techniques to generate concise summaries of BBC News articles.  
The dataset contains news titles and descriptions, and a pre-trained transformer model (`facebook/bart-large-cnn`) was used for abstractive summarization.

---

## 🚀 Features
- Loads BBC News dataset (`bbc_news.csv`)
- Applies Hugging Face's **summarization pipeline**
- Generates summaries for each article description
- Saves results into `bbc_summaries.csv`
- Evaluates sample summaries to check quality

---

## 📂 Repository Contents
- `bbc_text_summarizer.ipynb` → Jupyter/Colab notebook with full code  
- `bbc_summaries.csv` → Final dataset with generated summaries  
- `README.md` → Project documentation  

---

## ⚙️ Tech Stack
- Python 3.12  
- Hugging Face Transformers  
- PyTorch  
- Pandas  
- Google Colab  

---

## 📊 Dataset
- Original dataset: `bbc_news.csv` (~12.8 MB)  
- Columns: `title`, `description`  

---

## 🧠 Model
- **facebook/bart-large-cnn** (pretrained abstractive summarizer)  
- Summaries generated with controlled length (`min_length`, `max_length`)  

---

## 📌 Example
**Original:**  
`Many flights have been grounded, with huge queues and delays at airports all over the world.`  

**Summary:**  
`Many flights have been grounded, with huge queues and delays at airports worldwide.`  

---

## 🏗️ How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/bbc-text-summarizer.git
   cd bbc-text-summarizer
