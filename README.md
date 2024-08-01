# Natural-language-processing.

## Sentiment-analysis loyihasi:

## Overview

Hissiyotlarni tahlil qiluvchi dastur

Ijobiy va salbiy hissiyotga ajratadi.

### Prerequisites

- Google colab
- import pandas as pd
- import numpy as np
- import tensorflow as tf
- from sklearn.feature_extraction.text import CountVectorizer
- from sklearn.model_selection import train_test_split
- from tensorflow.keras.preprocessing.text import Tokenizer
- from tensorflow.keras.preprocessing.sequence import pad_sequences
- from tensorflow.keras.models import Sequential
- from tensorflow.keras.layers import Dense, Embedding, LSTM, SpatialDropout1D, SimpleRNN
- from tensorflow.keras.utils import to_categorical
- import re

## Dataset

Hugging Face platformasiga yuklangan uzbek tilidagi commentlardan tayyorlangan dataset

<div align="center">
  <img height="400" src="https://github.com/Philomath2020/Natural-language-processing/blob/main/pic/data.png"  />
</div>

## Models and Algorithms

## Model Train

Traning jarayonida natija accuracy : 96 % ga erishdi.
Test set bilan tekshrilganda accuracy : 83 % ga teng bo'ldi

## Usage

Deploy: Gradio orqali interfeys yaratildi, Ijobiy va salbiy hissiyotga ajratadigan Machine learning Calssification modelidan foydalanildi.

Foydalanish uchun Sentiment-analysis colab notebooknini yuklab yuritilsa oxirida gradio interfays paydo bo'ladi:

<div align="center">
  <img height="500" src="https://github.com/Philomath2020/Natural-language-processing/blob/main/pic/pic%20gradio.png"  />
</div>

Interfaysning chap qismidagi bo'lmaga text yozilib submit tugamasi bosilsa , o'ng tamonda positive yoki negativa natija ko'rinadi.
