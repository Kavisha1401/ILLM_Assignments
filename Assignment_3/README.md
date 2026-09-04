# ILLM Assignment 3 IndicCorp v2 – BPE and WordPiece Tokenization

## Overview
This assignment implements **BPE** and **WordPiece** tokenization on Gujarati text from the IndicCorp v2 dataset.

## Dataset
- Dataset: AI4Bharat IndicCorp v2
- Language: Gujarati
- Split: `guj_Gujr`
- Sentence tokenization is performed because the original data contains paragraphs.

## Experiments
- Development set: 1000 sentences
- Test set: 1000 sentences
- Training sizes: 100K, 300K, 500K, 1M
- Vocabulary sizes: 20K, 30K, 50K
- Tokenizers: BPE and WordPiece

The experiments compare how training-data size and vocabulary size affect tokenization.

## Libraries
- Python
- Hugging Face Datasets
- Hugging Face Tokenizers
- NumPy
- Pandas
- Matplotlib

## Files
- `*.ipynb` – Google Colab notebook
