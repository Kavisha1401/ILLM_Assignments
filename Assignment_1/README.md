# Language Identification using Custom TF-IDF

A language identification system for **23 Indian languages** using the **IndicCorpV2** dataset.

## Features

* 1000 sentences per language
* 80:10:10 stratified train/validation/test split
* Custom TF-IDF vectorizer

  * Word unigrams & bigrams
  * Character 2, 3 & 4-grams
* Custom Multiclass Logistic Regression
* Custom Macro-F1 evaluation
* Designed to run efficiently on Google Colab

## Dataset

**IndicCorpV2 – AI4Bharat**

[Dataset](https://huggingface.co/datasets/ai4bharat/IndicCorpV2)

Total: **23,000 sentences** across 23 languages.

## Implementation

The project implements TF-IDF, Logistic Regression, and Macro-F1 **from scratch**, without using predefined sklearn classes for these components.

## Results

The notebook reports:

* Test Accuracy
* Test Macro-F1
* Per-language F1 scores

## Files

```text
├── Assignment_1.ipynb
├── ILLM-Lab1-Assignment.pdf
└── README.md
```

## Requirements

```bash
pip install datasets
```
## Roll Number

U23AI016

Run the notebook cells sequentially in **Google Colab**.
