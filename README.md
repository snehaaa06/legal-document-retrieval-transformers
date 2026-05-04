# Legal Document Retrieval using Transformer-Based Models

This project focuses on improving legal case retrieval using transformer-based models on the COLIEE 2025 dataset.

##  Overview
Legal documents are complex and lengthy, making retrieval challenging. This project compares traditional and semantic retrieval methods.

##  Models Implemented
- TF-IDF (Baseline)
- Vanilla BERT
- Sentence-BERT (SBERT)
- Hybrid TF-IDF + SBERT
- Fine-Tuned Legal-BERT

##  Results
- TF-IDF MAP: 0.1368
- Hybrid MAP: 0.1761 (**+28.7%**)
- Legal-BERT MAP: 0.3412 (**+149.4% improvement**)

##  Key Contributions
- Built hybrid lexical + semantic retrieval pipeline
- Applied transformer-based embeddings for legal text
- Fine-tuned Legal-BERT for domain-specific retrieval

## Tech Stack
- Python
- HuggingFace Transformers
- Sentence-BERT
- scikit-learn
