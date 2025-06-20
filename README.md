# 🕌 Arabic Text Simplification
## [ ON GOING ]
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
- Custom simplifier for synonyms, passive-to-active conversion, and short sentence restructuring
- Evaluation tools using SARI and BLEU

---

## Model Architecture 

Uses a seq2seq Transformer (e.g. T5 / BART) fine-tuned on:
- Paired Arabic corpora (complex ↔ simplified)

  
- Datasets from The SAMER text simplification corpus which is the first manually
annotated Arabic parallel corpus for text simplification
targeting school-aged learners. The corpus comprises texts
of 159K words selected from 15 publicly available Arabic
fiction novels most of which were published between 1865
and 1955. The corpus includes readability level annotations
at both the document and word levels, as well as two
simplified parallel versions for each text targeting
learners at two different readability levels..

---

## 🚀 Getting Started

### 1. Install dependencies
```bash
pip install -r requirements.txt
