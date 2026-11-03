# English to Hindi Neural Machine Translation

## Overview
This project implements an English-to-Hindi Neural Machine Translation system using the **OpenNMT-py** framework and the ILCI subset of the BPCC dataset.

## Dataset
- Dataset: [AI4Bharat BPCC](https://huggingface.co/datasets/ai4bharat/BPCC)
- Subset: ILCI
- Source Language: English (`eng_Latn`)
- Target Language: Hindi (`hin_Deva`)

## Methodology
1. Load and preprocess parallel English-Hindi sentences.
2. Divide sentences into four bins based on English sentence length:
   - Bin 1: ≤ 10 words
   - Bin 2: 11–20 words
   - Bin 3: 21–29 words
   - Bin 4: ≥ 30 words
3. Create training, validation, and testing datasets.
4. Apply SentencePiece tokenization.
5. Train a Transformer model using OpenNMT-py.
6. Evaluate translations using SacreBLEU.

## Model Configuration
- Encoder/Decoder Layers: 3
- Attention Heads: 4
- Hidden Size: 256
- Vocabulary Size: 8,000
- Training Steps: 5,000
- Optimizer: Adam

## Results

**Overall Evaluation**

| Metric | Score |
|---|---:|
| BLEU | 0.70 |
| chrF | 7.88 |

**Bin-wise BLEU Scores**

| Bin | BLEU |
|---|---:|
| Bin 1 | 1.36 |
| Bin 2 | 0.78 |
| Bin 3 | 0.41 |
| Bin 4 | 0.67 |

## Analysis
Bin 1 achieves the highest BLEU score, while Bin 3 achieves the lowest. The results show that translation performance varies across sentence lengths and does not decrease consistently as sentence length increases.

## How to Run
1. Open `08_lab_illm.ipynb` in Jupyter Notebook or Google Colab.
2. Install the required dependencies.
3. Run all notebook cells sequentially.
4. Train the model and evaluate the translations.

## References
- [OpenNMT-py](https://github.com/OpenNMT/OpenNMT-py)
- [BPCC Dataset](https://huggingface.co/datasets/ai4bharat/BPCC)
- [SacreBLEU](https://github.com/mjpost/sacrebleu)
