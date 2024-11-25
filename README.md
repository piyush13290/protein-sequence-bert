# BERT for Amino Acid Sequence Analysis

A PyTorch implementation of BERT (Bidirectional Encoder Representations from Transformers) adapted for amino acid sequence analysis. This model performs masked language modeling on amino acid sequences to learn meaningful representations of protein sequences.

## 🧬 Overview

This project implements a BERT model specifically designed for processing and understanding amino acid sequences. The model can:
- Learn bidirectional representations of amino acid sequences
- Predict masked amino acids in sequences
- Handle multiple sequence alignments with gap tokens
- Process variable-length protein sequences

## 🛠️ Implementation Details

- **Embedding Layer**: 
  - Amino acid embeddings
  - Sinusoidal positional encodings
  - Dimension: 64

- **BERT Architecture**:
  - Multi-head self-attention mechanism
  - Layer normalization
  - Feed-forward neural networks
  - Dropout for regularization
  - GELU activation functions

- **Training**:
  - Masked Language Modeling (MLM) objective
  - Dynamic masking with 1-5 masks per sequence
  - Scheduled learning rate optimization
  - Support for CPU and MPS (Apple Silicon) acceleration

