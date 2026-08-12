# ILLM Assignment 2 – TF-IDF Normalization

This assignment compares different **TF and IDF normalization techniques** for Indian language identification using the dataset from Assignment 1.

## Objective

Compare normalized and unnormalized TF-IDF representations using a custom Logistic Regression classifier.

## Experiments

Six combinations were evaluated:

1. Unnormalized TF + Unnormalized IDF
2. Word-count normalized TF + Unnormalized IDF
3. Max-frequency normalized TF + Unnormalized IDF
4. Unnormalized TF + Normalized IDF
5. Word-count normalized TF + Normalized IDF
6. Max-frequency normalized TF + Normalized IDF

## Results

| TF | IDF | Accuracy | Macro-F1 |
|---|---|---:|---:|
| Unnormalized | Unnormalized | 92.83% | 91.95% |
| Word Count | Unnormalized | 90.70% | 89.42% |
| Max Frequency | Unnormalized | **93.00%** | **92.86%** |
| Unnormalized | Normalized | 91.30% | 90.79% |
| Word Count | Normalized | 89.65% | 88.09% |
| Max Frequency | Normalized | 89.09% | 87.73% |

### Best Result

**Max-frequency normalized TF + Unnormalized IDF**

- Accuracy: **93.00%**
- Macro-F1: **92.86%**

## Implementation

- 23 Indian languages
- 1000 sentences per language
- 80:10:10 train/validation/test split
- Custom TF-IDF
- Custom Logistic Regression
- Custom Macro-F1

## Files

- `ILLM-Lab-Assignment-2.pdf` – Assignment question
- `ILLM_Assignment_2.ipynb` – Google Colab implementation
- `README.md` 

## Roll Number

**U23AI016**
