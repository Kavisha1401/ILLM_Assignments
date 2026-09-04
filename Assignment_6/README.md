## Assignment 6 -Language Identification using Machine Learning and Deep Learning

This assignment implements a language identification system for 23 Indian languages using the dataset created in Assignment 1. The models are evaluated using Macro-F1 score.

### Models Implemented

- Logistic Regression using averaged FastText word vectors
- MLP with 0 hidden layers
- MLP with 1 hidden layer
- MLP with 2 hidden layers
- LSTM
- GRU
- FastText Supervised Classification

## Dataset

- Total languages: 23
- Total samples: 23,000
- Training: 18,400
- Validation: 2,300
- Testing: 2,300

FastText Wiki word vectors are used for feature representation.

## Results

| Model | Macro-F1 |
|---|---:|
| Logistic Regression | 0.8490 |
| MLP - 0 Hidden Layers | 0.8434 |
| MLP - 1 Hidden Layer | 0.8480 |
| MLP - 2 Hidden Layers | 0.8480 |
| LSTM | 0.8722 |
| GRU | **0.9005** |
| FastText Classification | 0.8820 |

## Conclusion

GRU achieved the highest Macro-F1 score of **0.9005**, followed by FastText Classification and LSTM. The experiment shows that sequential neural network models perform effectively for multilingual language identification.

## Technologies

Python, PyTorch, FastText, NumPy, Pandas, Matplotlib and Scikit-learn.
