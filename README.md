# KRBERT Sentiment Analysis Trainer

This repository contains a trainer for sentiment analysis using KRBERT (Bidirectional Encoder Representations from Transformers). The trainer allows you to train a KRBERT model for sentiment classification and evaluate its performance on validation data. It also supports early stopping based on the F1-micro score.

## Requirements

- Python 3.9
- torch==2.0.1
- transformers==4.30.0
- pandas==2.0.2
- tqdm==4.65.0
- scikit-learn==1.2.2

## Usage

Install the required dependencies:

   ```
   pip install -r requirements.txt
   ```

## Reference
KoRean based Bert pre-trained (KR-BERT)
This is a release of Korean-specific, small-scale BERT models with comparable or better performances developed by Computational Linguistics Lab at Seoul National University, referenced in KR-BERT: A Small-Scale Korean-Specific Language Model.

   ```
   https://github.com/snunlp/KR-BERT
   ```
   ```
   @article{lee2020krbert,
    title={KR-BERT: A Small-Scale Korean-Specific Language Model},
    author={Sangah Lee and Hansol Jang and Yunmee Baik and Suzi Park and Hyopil Shin},
    year={2020},
    journal={ArXiv},
    volume={abs/2008.03979}
  }
   ```