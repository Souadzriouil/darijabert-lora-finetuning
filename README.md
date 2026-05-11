# Fine-Tuning DarijaBERT for Moroccan Darija Text Classification using LoRA

## Overview

This project focuses on fine-tuning the SI2M-Lab/DarijaBERT model for Moroccan Darija text classification using LoRA (Low-Rank Adaptation). The project demonstrates an end-to-end NLP workflow including data preprocessing, tokenization, model fine-tuning, evaluation, and performance analysis using Hugging Face Transformers and PyTorch.

The objective is to build an efficient and lightweight NLP model capable of understanding and classifying Moroccan Darija text.

---

## Features

- Moroccan Darija text classification
- Fine-tuning DarijaBERT
- LoRA integration for parameter-efficient training
- Dataset preprocessing and tokenization
- Model evaluation using multiple metrics
- Visualization of training performance
- Confusion matrix analysis

---

## Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- PEFT (LoRA)
- Datasets
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```bash
darijabert-lora-finetuning/
│
├── data/
│   └── dataset_darija2.csv
│
├── notebooks/
│   └── darijabert_finetuning.ipynb
│
├── results/
│   ├── confusion_matrix.png
│   └── training_metrics.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Workflow

1. Load and preprocess the dataset
2. Encode labels
3. Tokenize Darija text using DarijaBERT tokenizer
4. Configure LoRA parameters
5. Fine-tune the model
6. Evaluate model performance
7. Visualize results and metrics

---

## Training Results

The model achieved strong performance after 10 training epochs.

### Final Metrics

| Metric | Score |
|---|---|
| Accuracy | 79.67% |
| F1-Score | 78.91% |
| Precision | 80.28% |
| Recall | 79.67% |

---

## Results Visualization

### Training Metrics

![Training Metrics](results/training_metrics.png)

### Confusion Matrix

![Confusion Matrix](results/confusion_matrix.png)

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Souadzriouil/darijabert-lora-finetuning.git
cd darijabert-lora-finetuning
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
notebooks/darijabert_finetuning.ipynb
```

---

## Requirements

Main libraries used:

- transformers
- torch
- peft
- datasets
- accelerate
- huggingface_hub
- scikit-learn
- pandas
- numpy
- matplotlib

---

## Future Improvements

- Hyperparameter optimization
- Larger Darija datasets
- Model deployment with Streamlit
- Integration with real-world Moroccan NLP applications

---

## Author

Souad Zriouil

AI Engineer | Data Scientist | Machine Learning | NLP | LLM

- GitHub: https://github.com/Souadzriouil
- LinkedIn: www.linkedin.com/in/souad-zriouil-54b19b267
