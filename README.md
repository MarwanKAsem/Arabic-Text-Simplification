# 🕌 Arabic Text Simplification

A custom project to simplify Modern Standard Arabic (MSA) or Egyptian Colloquial Arabic (ECA) sentences for educational, assistive, or readability applications.

---

##  What is Text Simplification?

Text simplification is the task of rewriting text to make it easier to read and understand, while preserving its original meaning.

**In Arabic**, this is crucial for:
- Language learners
- Children
- People with reading or cognitive difficulties
- Preprocessing for NLP models

---

##  Features

- Arabic-specific preprocessing
- Rule-based and ML-based simplification
- Custom simplifier for synonyms, passive-to-active conversion, and short sentence restructuring
- CLI and script usage
- Evaluation tools using SARI and BLEU

---

## Model Architecture 

Uses a seq2seq Transformer (e.g. T5 / BART) fine-tuned on:
- Paired Arabic corpora (complex ↔ simplified)
- Datasets from [Shamela](https://shamela.ws/), [Arabic Wikipedia Simplified](https://ar.wikipedia.org/wiki/), etc.

---

## 🚀 Getting Started

### 1. Install dependencies
```bash
pip install -r requirements.txt
