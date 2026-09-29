# AI-Powered Text Paraphraser with Automated Quality Evaluation

An end-to-end Python pipeline that leverages deep learning transformers and NLP packages to paraphrase input text while ensuring grammar precision, semantic fidelity, and structural originality.

---

## 📌 Project Overview

This project implements a sequence-to-sequence deep learning paraphrasing engine utilizing Hugging Face Transformers. The tool rephrases input sentences to improve clarity and structure, performs post-generation grammar and fluency corrections, and evaluates output quality using semantic vector similarity and lexical diversity metrics.

---

## ✨ Key Features

* **Deep Learning Rephrasing**: Uses `T5-base` transformer fine-tuned for paraphrasing tasks (`Vamsi/T5_Paraphrase_Paws`).
* **Automated Grammar & Fluency Check**: Integrates `LanguageTool` and `spaCy` to verify spelling, grammar, and sentence structure post-generation.
* **Semantic Meaning Preservation**: Employs Sentence-BERT (`all-MiniLM-L6-v2`) to calculate dense cosine similarity scores between source and target text.
* **Lexical Diversity & Evaluation**: Measures overlap and originality using ROUGE scores (`ROUGE-1`, `ROUGE-2`, `ROUGE-L`).
* **CLI & Notebook Ready**: Runs via console input scripts or inside Google Colab environments.

---

