# Cricket Text Generation with PyTorch

A deep learning project that uses an **LSTM (Long Short-Term Memory)** network to perform **next-word prediction and text generation** from cricket-related text.

##  Overview

The project demonstrates a simple NLP pipeline:

* Text preprocessing and tokenization
* Vocabulary and word-to-index mapping
* Sequence generation using a sliding window
* Word embeddings with PyTorch
* LSTM-based next-word prediction
* Automated text generation

##  Model Architecture

```text
Input Sequence
      ↓
Embedding
      ↓
LSTM
      ↓
Linear Layer
      ↓
Next Word Prediction
```

**Configuration:**

| Parameter        |            Value |
| ---------------- | ---------------: |
| Embedding Size   |               48 |
| LSTM Hidden Size |               64 |
| Sequence Length  |                4 |
| Batch Size       |               32 |
| Learning Rate    |            0.001 |
| Epochs           |              100 |
| Optimizer        |             Adam |
| Loss             | CrossEntropyLoss |

## 🛠️ Technologies

* Python
* PyTorch
* NumPy
* Jupyter Notebook
```
## Task

**Domain:** Natural Language Processing
**Task:** Next-Word Prediction & Text Generation
**Model:** LSTM
**Framework:** PyTorch

## Author

**Indunil Udayanga**
Computer Science Undergraduate | AI/ML Enthusiast
