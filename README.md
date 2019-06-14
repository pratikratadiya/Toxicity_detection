# Toxicity_detection

Detection of toxic nature of comment using the toxic comment dataset(https://github.com/vzhou842/profanity-check/blob/master/profanity_check/data/clean_data.csv)

The data includes both tweets as well as wikipedia edits as obtained from the Toxic comment classification challenge on Kaggle.

The following implementations are done:
1. LSTM
2. LSTM with GLoVE 100D word embeddings
3. LSTM with GLoVE 300D word embeddings
4. Attention mechanism with GLoVe 300D word embeddings

The results obtained were as follows:

| Model | Training accuracy(%) | Testing accuracy(%) |
| ----- | ----------------- | ---------------- |
| LSTM | 82 | 80 |
| LSTM + GLoVe(100D) | 95 | 96.12 |
| LSTM + GLoVe(300D) | 95.34 | 95.94 |
| Multi layer LSTM + GLoVe(300D) | 97.06 | 96.14 |
| LSTM + Attention + GLoVe(300D) | 98.16 | 95.87|

Future scope includes improvement in the attention layer to increase testing accuracy.

Also, transformer architecture can be used to improve the performance further
