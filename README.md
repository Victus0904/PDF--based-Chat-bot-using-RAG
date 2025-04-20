# Project README

## Project Overview

This project involves loading and utilizing a robust machine learning model within a Jupyter notebook. The provided notebook (`Submission.ipynb`) efficiently executes machine learning inference tasks and provides capabilities for processing multiple PDFs simultaneously. Additionally, it supports multilingual inputs and can handle text in various languages.

## Key Features

- **Multiple PDF Handling**: The model can process and analyze multiple PDF documents simultaneously, extracting relevant information effectively.
- **Multilingual Support**: Designed to support and accurately process text in multiple languages, enhancing its utility in diverse linguistic environments.

## Dependencies

To ensure smooth execution, install the following Python dependencies. It is recommended to use a virtual environment:

### Step-by-Step Installation

1. **Create and Activate Virtual Environment**

```bash
python3 -m venv env
source env/bin/activate  # On Windows use: .\env\Scripts\activate
```

2. **Install Dependencies**

Run the following commands to install the necessary libraries:

```bash
pip install torch
pip install transformers
pip install langchain
pip install faiss-cpu
pip install streamlit
pip install PyMuPDF  # for fitz
pip install langdetect
pip install sentence-transformers
```

Alternatively, install all at once using:

```bash
pip install torch transformers langchain faiss-cpu streamlit PyMuPDF langdetect sentence-transformers
```

## Running the Notebook

To execute the notebook:

1. Activate your environment:

```bash
source env/bin/activate
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook Submission.ipynb
```

## Important Notes

- **Model Loading Time**: The model used in this notebook is substantial and may take a few minutes to load. This delay is normal and expected.
- **If Loading Fails**: If the model loading process fails or times out, simply refresh or restart the notebook kernel and re-execute. The model will successfully load upon retrying.
- **System Resources**: Ensure sufficient system resources (RAM and CPU/GPU) are available to manage the model's size and computational demands effectively.

## Advantages of This Model

- Efficiently manages and interprets data from complex and large PDF documents.
- Provides reliable multilingual processing, facilitating broader usability.
- Enhanced accuracy and robustness in text extraction and analysis tasks.

## Support

For further issues or troubleshooting, ensure your environment and dependencies are correctly configured as described above.

