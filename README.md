# Cross-lingual-Summarization

This repository contains the code and data for a project that addresses the problem of cross-lingual text summarization. Specifically, the goal is to generate a summary in English from a French document as input, using two types of transformers: attention-based and convolution-based.

## Dataset

We created a cross-lingual summarization dataset based on an existing French summarization corpus. We used the Google Translate API to automatically translate the French summaries to English. The resulting dataset consists of pairs of French documents and their English summaries.

## Models
We implemented two models for this task: an end-to-end attention-based transformer and a convolution-based transformer. Both models take the French document as input and generate an English summary as output.

The baseline attention LSTM model code is adapted from the open-source repository available at https://github.com/gabrielloye/Attention_Seq2seq-Translation.


