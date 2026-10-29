# Assignment 10: Language Identification

## About
This project identifies the language of a given text using the IndicCorpV2 dataset, which contains text from 23 Indian language groups.

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Hugging Face Datasets

## Methodology
1. Collected sentences from the IndicCorpV2 dataset.
2. Split the dataset into training, validation, and testing sets.
3. Implemented a custom TF-IDF vectorizer using word and character n-grams.
4. Implemented a logistic regression classifier from scratch.
5. Evaluated the model using Macro-F1.

## Results
The initial model achieved:
- Test Accuracy: 90.42%
- Macro-F1 Score: 89.84%

*These are the initial results and may change after dataset and evaluation corrections.*

## How to Run
1. Open the notebook `U23AI016_Assignment_10.ipynb` in Google Colab.
2. Run the cells sequentially.
3. Check the final evaluation results.

## Dataset
[IndicCorpV2 on Hugging Face](https://huggingface.co/datasets/ai4bharat/IndicCorpV2)

## Author
Kavisha Vaja  
SVNIT Surat
