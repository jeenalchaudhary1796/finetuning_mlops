
---

# 1. README.md

````md
# MLOps Assignment 2

## Hugging Face Fine-Tuning, Experiment Tracking & Model Deployment

### Project Overview

This project demonstrates a complete MLOps workflow using Hugging Face Transformers, Weights & Biases (W&B), and Hugging Face Hub deployment. The workflow includes dataset loading, preprocessing, tokenizer setup, transformer fine-tuning, experiment tracking, evaluation, artifact logging, and deployment of the trained model.

The DistilBERT transformer model was fine-tuned for text classification using Hugging Face Trainer API. Weights & Biases was used for experiment tracking and metric visualization. The trained model was deployed publicly to Hugging Face Hub.

---

## Model Used

### DistilBERT (`distilbert-base-cased`)

DistilBERT was selected because it is lightweight, computationally efficient, and faster than traditional BERT models while still maintaining strong NLP performance.

Advantages:

- Faster training
- Lower memory usage
- Strong transformer-based contextual understanding
- Easy integration with Hugging Face ecosystem
- Suitable for cloud notebook environments such as Kaggle and Google Colab

---

## Technologies Used

- Python
- Hugging Face Transformers
- Weights & Biases (W&B)
- Hugging Face Hub
- PyTorch
- Scikit-learn
- Pandas
- Google Colab / Kaggle

---

## Setup Instructions

### Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## Run the Notebook

```bash
jupyter notebook (Executed In Kaggle Notebook)
```

Open:

```text
mlops_assignment2.ipynb
```

---

## Workflow Steps

1. Dataset Loading
2. Data Preprocessing
3. Tokenization using DistilBERT Tokenizer
4. Fine-Tuning DistilBERT Model
5. Experiment Tracking using W&B
6. Model Evaluation
7. Artifact Logging
8. Hugging Face Model Deployment

---

## Evaluation Results

| Metric   | Score|
|----------|------|
| Accuracy | 0.52 |
| F1 Score | 0.51 |
| Eval Loss| 2.78 |

---

## Project Links

### GitHub Repository

https://github.com/jeenalchaudhary1796/finetuning_mlops

---

### Hugging Face Model

https://huggingface.co/jeenal1796/distilbert-bookgenre-classifier

---

### Weights & Biases Dashboard

https://wandb.ai/jeenalchaudhary1796-education/mlops-assignment2-jeenal/workspace

---

### Kaggle Notebook

https://www.kaggle.com/code/jeenal2027/jc-v1

---

## Challenges & Learnings

Some challenges faced during the assignment included:

- Configuring cloud notebook environments
- Managing W&B and Hugging Face authentication
- Handling package compatibility issues
- Internet permission restrictions in Kaggle

The assignment provided practical understanding of:

- Experiment tracking
- Transformer fine-tuning
- MLOps workflows
- Cloud-based training
- Model deployment pipelines

---

## Conclusion

This assignment successfully demonstrated a complete MLOps workflow using Hugging Face Transformers, W&B experiment tracking, and Hugging Face deployment. The project helped build understanding of practical machine learning deployment pipelines and reproducible workflows.
````

---

# 2. requirements.txt

```txt
transformers
datasets
accelerate
wandb
huggingface_hub
scikit-learn
pandas
numpy
torch
jupyter
```

---

# Final Submission Links

## GitHub Repository

```text
https://github.com/jeenalchaudhary1796/finetuning_mlops
```

## Hugging Face Model

```text
https://huggingface.co/jeenal1796/distilbert-bookgenre-classifier
```

## W&B Dashboard

```text
https://wandb.ai/jeenalchaudhary1796-education/mlops-assignment2-jeenal/workspace
```

## Kaggle Notebook

```text
https://www.kaggle.com/code/jeenal2027/jc-v1
```
