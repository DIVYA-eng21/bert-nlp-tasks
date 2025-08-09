# NLP with BERT & Hugging Face Transformers

This repository contains my hands-on work exploring **Natural Language Processing (NLP)** using modern Transformer-based models.  
It includes both **custom BERT-based sentiment analysis** and **Hugging Face pipeline demonstrations** for multiple NLP tasks.

While building these notebooks, I aimed to understand:
- How Transformer architectures like **BERT** and **GPT** work for different tasks.
- How to preprocess, tokenize, and prepare data for models.
- How to leverage Hugging Face's pre-trained pipelines for rapid experimentation.

---

## 📂 Project Structure

### 1. `bert_working.ipynb`
A complete workflow for **Sentiment Analysis** using BERT on a product reviews dataset.  
Covers:
- Data loading & preprocessing
- Tokenization & padding
- Fine-tuning a BERT model
- Model evaluation and performance metrics

### 2. `bertt.pdf`
A multi-task demonstration using Hugging Face Transformers pipelines:
- **Sentiment Analysis** – Detecting positive/negative sentiment in text.
- **Zero-Shot Classification** – Assigning custom labels to text without retraining.
- **Text Generation** – Generating human-like text with GPT-2 & DistilGPT2.
- **Fill-Mask** – Predicting masked words using BERT.

---

## ⚙️ Installation

Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/nlp-transformers-demo.git
cd nlp-transformers-demo
pip install datasets evaluate "transformers[sentencepiece]"


## 🧠 Learning Note
This repository reflects my practical learning process in NLP , Bert and Generative AI.
The work is self-implemented but a few concepts were learned from the Intellipaat – Generative AI course.
The goal was not just to run code, but to understand each step, modify it, and extend it for my own datasets and experiments.

Key takeaways from building this:
How tokenization and attention masks are handled in BERT.
The difference between task-specific fine-tuning and using pre-trained pipelines.
How to experiment quickly using Hugging Face’s pipeline() API.
How model outputs can be interpreted and evaluated.



📚 Tech Stack

Python 3.x
PyTorch
Hugging Face Transformers
Datasets & Evaluate libraries
Jupyter Notebook


