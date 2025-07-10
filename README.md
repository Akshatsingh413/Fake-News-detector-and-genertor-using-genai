# 📰 Fake News Generator & Detector using Transformers

This project combines the power of **GPT-2** and **BERT** using Hugging Face's Transformers library to:

- 🔹 Generate fake news headlines or content (GPT-2)
- 🔹 Detect whether a news statement is real or fake (BERT)

---

## 🧠 Models Used

### 🔸 Generator
- Model: `gpt2`
- Task: `text-generation` using Hugging Face `pipeline`

### 🔸 Detector
- Model: `jy46604790/Fake-News-Bert-Detect`
- Task: `text-classification` using Hugging Face `pipeline`

---
## 🧰 Tech Stack & Tools

| Category       | Technology / Tool                            |
|----------------|----------------------------------------------|
| Language       | Python 🐍                                    |
| NLP Library    | [Hugging Face Transformers](https://huggingface.co/transformers) |
| ML Models      | GPT-2 (Generator), BERT (Detector)           |
| Pipelines Used | `text-generation`, `text-classification`     |
| Inference      | Hugging Face `pipeline()` API                |
| Dependencies   | `transformers`, `torch`                      |
