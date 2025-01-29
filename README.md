# Financial Bot Colab Notebook

This Google Colab notebook is designed for document processing and retrieval using natural language processing (NLP) techniques. It utilizes FAISS for efficient similarity search and SentenceTransformers for embedding generation. Additionally, it supports PDF text extraction and manipulation.

## Features
- Extract text and tables from PDF files using `pdfplumber`
- Generate text embeddings using `SentenceTransformers`
- Perform efficient document search using FAISS
- Handle user queries with NLP pipelines from Hugging Face Transformers
- Interactive file handling with Google Colab

## Dependencies
The notebook requires the following libraries:
```python
import faiss
from sentence_transformers import SentenceTransformer
import pdfplumber
import pandas as pd
import numpy as np
from io import BytesIO
from google.colab import files
from transformers import pipeline
```

## Usage
1. Open the notebook in Google Colab.
2. Upload PDF files for processing.
3. Run the cells to extract and search content.
4. Query the system for relevant document sections.

## Installation
To run this notebook locally, install the dependencies using:
```bash
pip install faiss-cpu sentence-transformers pdfplumber pandas numpy transformers
```

## License
This project is open-source and available for use and modification under an appropriate license.

