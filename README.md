# Introduction to Transformers - IOAI 2025

This repository contains materials for the workshop designed for participants of the International Olympiad in Artificial Intelligence (IOAI).

## 🕒 Workshop Structure

### Part 1: Transformer Architecture Deep Dive
- Learn the building blocks of Transformer models, including embeddings, encoders, and position encodings.
- Understand how input sequences are processed through the model and how representations evolve.
  
### Part 2: Attention Mechanism and Multi-Head Attention
- Inspect attention weights and hidden states across layers and heads.

### Part 3: Embeddings and Weight Manipulation
- Restore model performance under embedding corruption constraints in a zero-shot setting. Inspired by [NEOAI 2025 Task 5](https://www.kaggle.com/code/ilseyaralimova/broken-bert-baseline), this challenge requires recovering sentiment classification accuracy for a "Broken BERT" model without retraining or external resources.

### Part 4: Cross-Lingual Adaptation
- Develop systems for zero-shot slot filling and intent detection in a cross-lingual setting using English training data and Romanian evaluation. Inspired by [NEOAI 2025 Task 8](https://www.kaggle.com/competitions/neoai-2025-intent-detection-and-slot-filling), under strict constraints (no translation, no external models).

## 📚 Notebooks

Before starting the workshop, **make a personal copy of the notebook**. You will work on your own version during the session. To do so, go to the **_File_** menu in Colab and select _**Save a copy in Drive**_.

Workshop: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yQXBNEiga9kLd7ZMvBtJsF5GEkTTpQvm?usp=sharing)


## ⚙️ Local Development Setup

_Coming soon..._

1. Clone the repository:
   ```bash
   # Placeholder setup
   git clone https://github.com/YOUR_ORG/transformers-ioai-2025.git
   cd transformers-ioai-2025
   # TODO: Add virtualenv/poetry/conda instructions
   ```

The notebooks are tested with Python 3.10+.


## 🛠️ Contributing
Everyone is welcome to contribute, and we value all contributions — whether it's fixing a typo, improving explanations, adding new insights, or suggesting new tasks. If you’ve found something that could be improved, we encourage you to open a discussion or submit a pull request.


To contribute:

1. Open an issue describing the problem or idea.

2. Fork the repository and clone your fork:
   ```bash
   git clone git@github.com:<your-github-handle>/ioai-transformer-workshop.git
   cd ioai-transformer-workshop
   ```

3. Add the upstream repository:
   ```bash
   git remote add upstream https://github.com/danadascalescu00/ioai-transformer-workshop.git
   ```

4. Create a new branch for your changes:
   ```bash
   git checkout -b your-feature-name
   ```

5. Make your changes, commit and push:
   ```bash
   git add .
   git commit -m "Brief description of the change"
   git push origin your-feature-name
   ```

6. Submit a pull request with a clear description of what you’ve done.


## 🔗 References
- Vaswani et al., 2023 – ["Attention is All You Need"](https://arxiv.org/abs/1706.03762)

- Hugging Face – [LLM Course](https://huggingface.co/learn/llm-course/chapter1/1)

- UVADLC – [Tutorial 6: Transformers and MH Attention](https://uvadlc-notebooks.readthedocs.io/en/latest/tutorial_notebooks/tutorial6/Transformers_and_MHAttention.html)

- Northern Eurasia OAI 2025 [Kaggle Competition](https://www.kaggle.com/competitions/neoai-2025/overview)


## 📖 Additional Resources

- [Jay Alammar – The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)

- [Hugging Face Transformers Notebooks](https://huggingface.co/docs/transformers/notebooks)

---
