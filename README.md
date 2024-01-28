# Advanced NLP with Contextual Question Answering

## Overview
This project houses `contextual_answering.ipynb`, a Jupyter notebook that showcases advanced Natural Language Processing (NLP) techniques. It's designed to extract text from various files, clean the data, and use it for contextual question answering. The notebook employs several transformer models, including DistilBERT and DistilGPT-2, to demonstrate text extraction, contextual answering, and sentence generation capabilities.

## Features
1. **Text Extraction**: The notebook begins by extracting text from a list of files. This process involves reading various file formats and extracting the textual content from them.

2. **Data Cleaning**: After extraction, the notebook performs data cleaning operations. This includes removing copyright and other non-essential information to prepare the data for further processing. Data cleaning is crucial for improving the accuracy and relevance of the analysis that follows.

3. **Contextual Answering Using Transformer Models**: The notebook employs several transformer models for contextual answering. These models use the cleaned, extracted text as context to provide answers to queries. The specific transformer models used are:
  - DistilBERT: A lighter version of BERT that retains most of its performance while being more efficient.
  - Default Question-Answering Model (Pipeline): This could refer to a standard pre-built question-answering pipeline provided by libraries like Hugging Face's Transformers. These pipelines are often easy to use and provide robust performance for many question-answering tasks.
    
4. **Sentence Generation with DistilGPT-2**: Finally, the notebook uses DistilGPT-2, a distilled version of the GPT-2 model, to generate sentences. This part of the notebook  takes the results from the question-answering models and attempts to construct coherent, contextually relevant sentences.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python packages

### Installation
Clone this repository and install the required Python packages:

```bash
git clone [repository URL]
cd [repository directory]
pip install -r requirements.txt
```

### Usage
Open the contextual_answering.ipynb notebook in Jupyter Notebook or JupyterLab and run the cells sequentially to see the project in action.
