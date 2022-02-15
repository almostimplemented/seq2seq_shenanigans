# Seq2Seq Shenanigans

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/almostimplemented/seq2seq_shenanigans/blob/main/Silly%20Seq2Seq%20Shenanigans.ipynb)


This is a small experiment of training a sequence-to-sequence (\"seq2seq\") model to learn a prescribed mapping between two sequences of decimal digits.

The input string specifies its own substring with the starting index offset and the substring length.

The output string is simply that substring, padded at the end with zeros.
