# 🌟 Exploring Hugging Face Transformers 🚀

This repository marks my **first hands-on exploration** of Hugging Face’s **Transformers library** and its **tokenizers**. The goal is to understand modern NLP workflows, experiment with popular architectures, and leverage high-level APIs to switch between tasks like generation, classification, and translation.

---

## 📂 Contents
- `Exploring Generative AI Libraries-v2.ipynb`: Main Jupyter Notebook containing all experiments, code, and model outputs.
- `README.md`: Project documentation and overview.

---

## ⚡ Key Feature: The Pipeline API
The core of this exploration focuses on the **Pipeline API**. It abstracts the complexity of the NLP pipeline, allowing for efficient model loading and inference. By using `pipeline()`, the following steps are handled automatically:
1. **Tokenization:** Converting raw text into input IDs.
2. **Model Inference:** Passing inputs through the neural network.
3. **Post-processing:** Converting logits/tensors back into human-readable text.

---

## 🤖 Models Explored
I experimented with four diverse models to cover a broad range of NLP tasks:

### 1. GPT-2 (`gpt2`) — Text Generation
* **Task:** Predicting the next word in a sequence to generate creative text.
* **Usage:** Leveraged for story continuation and idea generation.

### 2. DistilBERT — Sentiment Analysis
* **Model:** `distilbert-base-uncased-finetuned-sst-2-english`
* **Task:** Binary classification to detect if a sentence is **Positive** or **Negative**.
* **Why:** A distilled, lightweight version of BERT that offers high performance with lower latency.

### 3. BERT (`bert-base-uncased`) — Fill-Mask
* **Task:** Predicting "masked" (hidden) words within a sentence.
* **Insight:** This was used to explore how bi-directional context helps models understand the relationship between words in a sentence.

### 4. T5-small (`t5-small`) — Translation & Summarization
* **Task:** A **Sequence-to-Sequence (Seq2Seq)** approach that treats every NLP task as a "text-to-text" problem.
* **Usage:** Used for translating English to French and generating concise summaries of longer paragraphs.

---

## 🔧 Installation & Setup

To run the experiments locally, install the required libraries:

```bash
pip install transformers torch