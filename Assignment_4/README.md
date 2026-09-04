# ILLM Assignment 4 – N-Gram Language Models

## Overview

This assignment implements and evaluates N-Gram Language Models for Gujarati text using the **AI4Bharat IndicCorpV2** corpus.

The objective is to compare different N-Gram orders and smoothing techniques using **Perplexity** as the evaluation metric.

## Dataset

- **Dataset:** AI4Bharat IndicCorpV2
- **Language:** Gujarati
- **Corpus:** `gu.txt`
- **Number of sentences used:** 1,000,000
- **Train set:** 800,000 sentences
- **Development set:** 100,000 sentences
- **Test set:** 100,000 sentences

## N-Gram Models

The following N-Gram models were implemented:

- Unigram (1-Gram)
- Bigram (2-Gram)
- Trigram (3-Gram)
- 4-Gram

## Smoothing Techniques

Each N-Gram model was evaluated using the following methods:

1. **Unsmoothed Model**
2. **Add-1 (Laplace) Smoothing**
3. **Add-K Smoothing** (`K = 0.1`)
4. **Interpolated Smoothing**
5. **Kneser-Ney Smoothing** (`D = 0.75`)

## Evaluation

The models were evaluated using **Perplexity** on the development set.

A lower perplexity indicates better language-model performance.

The notebook includes:

- Perplexity calculation
- Comparison of all smoothing methods
- Results table
- Perplexity comparison graph
- Best model identification
- Final evaluation on the test set

## Implementation

The project was implemented using **Python** in **Google Colab/Jupyter Notebook**.

### Main Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Collections

## Results

The notebook automatically identifies the model and smoothing technique with the lowest development-set perplexity and evaluates the selected model on the test set.

The final results are available in the notebook's **Results**, **Best Model**, and **Final Test Result** sections.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the cells from top to bottom.
3. The Gujarati corpus is loaded directly from AI4Bharat IndicCorpV2.
4. The dataset is split into training, development, and test sets.
5. N-Gram models are trained.
6. Different smoothing techniques are evaluated.
7. Perplexity results and comparisons are generated automatically.

## Conclusion

This assignment demonstrates how N-Gram language models perform with different model orders and smoothing techniques. Perplexity provides a quantitative way to compare the models and determine the most effective configuration for the Gujarati corpus.
