# 🧠 LLM from Scratch — GPT-style Architecture (In Progress)

> Building a Transformer-based Large Language Model (LLM) pipeline from the ground up.

This project is an ongoing deep-dive into the mechanics of GPT-style models, focusing on replicating the key steps behind how LLMs process and understand text — from raw input to embedded tensors. Ideal for those curious about the inner workings of modern NLP.

---

## 🚧 Current Status: In Progress

I'm actively building this project step-by-step to deeply understand the architecture and training process of LLMs. Core components like tokenization, embedding, and data pipelines are already functional — model training and optimization are next.

---

## ✅ Completed So Far

### 🔹 Raw Text Processing
- Loaded and cleaned a `.txt` corpus (~1.5M words) for training
- Used the *Harry Potter & The Verdict* dataset for experimental input

### 🔹 Tokenization (BPE)
- Implemented Byte Pair Encoding (BPE) using OpenAI’s `tiktoken` library
- Converted raw text into compact, learnable tokens

### 🔹 Input Pipeline
- Created input-target pairs using a **sliding window** over tokenized data
- Packed into a custom `PyTorch Dataset` and `DataLoader`

### 🔹 Token Embedding Layer
- Designed an embedding matrix to convert token IDs into dense vectors
- Lays the foundation for multi-head attention

---

## 🛠️ In Progress

- 🔄 Positional Encoding
- 🧮 Multi-Head Self-Attention
- 🧠 Transformer Blocks
- 🏋️‍♂️ Training Loop (Causal Language Modeling)
- 📈 Loss tracking, evaluation & inference

---

## 📚 Tech Stack

- **Language**: Python
- **Libraries**: PyTorch, NumPy, tiktoken
- **Tools**: Jupyter Notebooks, Colab, Git

---

## 📌 Goal

To fully understand and build each component of a GPT-like model, and eventually scale this into a functional language model capable of generating coherent text from scratch.

---

## 🚀 Future Scope

- Train on custom domain datasets (healthcare, legal, etc.)
- Add evaluation scripts (perplexity, BLEU, etc.)
- Fine-tune on downstream tasks like summarization or Q&A
- Deploy via Flask or FastAPI

---

## 🙋‍♂️ Author

**GurSanjjam Singh Alang**  
BCA Student · Aspiring AI Engineer  
https://www.linkedin.com/in/gursanjjamsinghalang/ · https://github.com/GurSanjjamSingh · Email: sanjjam@gmail.com

---

> ⚠️ This is a work-in-progress, research-driven project built for educational purposes and portfolio development. Feedback and contributions are welcome!
