# LUKE for Entity Span Classification

## Repository Description
This repository contains a Jupyter Notebook demonstrating how to fine-tune and use the LUKE (Language Understanding with Knowledge-based Embeddings) model for **Entity Span Classification**. The notebook includes data preprocessing, training, inference, and performance evaluation steps, making it a comprehensive guide for Entity Span Classification (NER) using **Hugging Face Transformers**.

## Features
- **Preprocessing**: Tokenizing text and extracting entity spans using **SpaCy**.
- **Model Training**: Fine-tuning a **LUKE-based model** for entity classification.
- **Inference**: Running predictions on text and extracting named entities.
- **Performance Evaluation**: Measuring model accuracy using the **seqeval** library.

## Installation
To use this notebook, install the required dependencies:
```bash
pip install datasets seqeval git+https://github.com/huggingface/transformers.git
```

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Zain-Haider-ML/Fine-Tune-LukeForEntitySpanClassification.git
   ```
2. Navigate to the directory:
   ```bash
   cd LukeForEntitySpanClassification
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook LukeForEntitySpanClassification.ipynb
   ```
4. Follow the steps inside the notebook to train and evaluate the model.

## Dataset
The notebook loads a dataset in **JSONL format**, containing named entity annotations. Make sure your dataset is structured appropriately before running the code.

## Model
The notebook uses **LukeForEntitySpanClassification** from Hugging Face. It is trained on a custom dataset and evaluated using standard NER metrics.

## Performance Evaluation
The model's performance is measured using **seqeval**, which calculates precision, recall, and F1-score.

## Acknowledgments
- **Hugging Face** for the Transformers library.
- **SpaCy** for tokenization.
- **seqeval** for performance metrics.

## License
This project is licensed under the MIT License.

