# 🌟 Exploring Hugging Face Transformers 🚀

This repository is my **first hands-on exploration** of Hugging Face’s **Transformers library** and its **tokenizers**.  
The goal is to get familiar with how modern NLP models work, try out a few popular architectures, and understand how easily Hugging Face lets us switch between tasks like **text generation, sentiment analysis, and translation/summarization**.  

---

## 📂 Contents
- `Exploring Generative AI Libraries-v2.ipynb` → Main Jupyter Notebook with all the experiments and outputs.  
- `README.md` → This documentation.  

---

## 🤖 Models Explored
I experimented with **three diverse Hugging Face models**:

1. **GPT-2 (`gpt2`)** → Text Generation  
   - Generates coherent and creative text.  
   - Example: Story continuation, creative writing, idea generation.  

2. **DistilBERT (`distilbert-base-uncased-finetuned-sst-2-english`)** → Sentiment Analysis  
   - A lightweight and fast version of BERT.  
   - Example: Detect if a sentence is **Positive** or **Negative**.  

3. **T5-small (`t5-small`)** → Translation & Summarization  
   - A sequence-to-sequence model.  
   - Example: Translate between languages or summarize long text.  

👉 Together, these models cover **generation**, **classification**, and **seq2seq** tasks, giving a broad taste of Hugging Face’s ecosystem.  

---

## ⚡ Quick Start
### 🔧 Installation
You only need two libraries:  
```bash
pip install transformers torch
