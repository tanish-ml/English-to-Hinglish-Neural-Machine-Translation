# Eng-Hin-Language-Translator-using-Word-Embedding-and-RNN


## Overview

This project implements a Neural Machine Translation (NMT) model to translate English sentences into Hinglish, a hybrid of Hindi and English. The model leverages TensorFlow, employing a Sequence-to-Sequence architecture with attention mechanisms.

## Methodology

The project follows a comprehensive methodology:

1. **Data Collection and Preprocessing:** Curated a diverse dataset containing English sentences and corresponding Hinglish translations. Preprocessed the data through normalization, tokenization, and sequence padding.

2. **Model Architecture:** Implemented a Sequence-to-Sequence model with attention mechanisms and the Transformer architecture. The design includes embedding layers, LSTM layers, RepeatVector, and TimeDistributed Dense layers to capture intricate language patterns.

3. **Training Strategy:** Utilized the Adam optimizer and categorical crossentropy loss for 30 epochs. Incorporated a ModelCheckpoint callback to save the best-performing model weights, preventing overfitting.

4. **Evaluation Metrics:** Assessed the model's performance using metrics such as BLEU score to quantify the similarity between predicted and reference translations.



## Results

The model demonstrates proficiency in translating English to Hinglish. Sample translations on training and test sequences indicate accurate predictions, aligning well with ground truth.

## Contributing

Contributions are welcome! Feel free to report issues, submit feature requests, or contribute enhancements.


