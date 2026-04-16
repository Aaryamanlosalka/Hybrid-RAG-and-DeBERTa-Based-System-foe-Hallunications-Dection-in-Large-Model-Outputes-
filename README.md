# Hybrid RAG + DeBERTa Hallucination Detection

## 📌 Overview

This project focuses on detecting hallucinations in Large Language Model (LLM) outputs using two approaches:

1. BERT-based supervised classification
2. Hybrid Retrieval-Augmented Generation (RAG) with DeBERTa and NLI-based explainability

## 🚀 Features

* Binary classification of factual vs hallucinated text
* FAISS-based semantic retrieval
* DeBERTa-v3 classification
* NLI-based explainability module
* Comparative analysis between baseline and hybrid model

## 📊 Results

* BERT Accuracy: ~94%
* Hybrid Model Accuracy: ~50%
* Hybrid model provides explainability but depends on knowledge base quality

## 🛠️ Tech Stack

* Python
* PyTorch
* HuggingFace Transformers
* FAISS
* Sentence Transformers
* Scikit-learn

## ⚙️ Setup Instructions

1. Clone the repository:

```
git clone https://github.com/your-username/hallucination-detection.git
cd hallucination-detection
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the notebook:

```
jupyter notebook notebooks/hybrid_rag_model.ipynb
```

## 📁 Project Structure

* `/data` → sample datasets
* `/notebooks` → implementation notebooks
* `/results` → graphs and outputs
* `report.pdf` → final IEEE paper

## 📌 Note

Due to computational constraints, full dataset and trained models are not included.
