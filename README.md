# Translation Pipeline

This Python script provides a translation pipeline for various language pairs using the Hugging Face `transformers` library. The script allows you to translate text between multiple languages, including English, French, Hindi, Spanish, German, and Chinese.

## Languages Supported
- **English to French** (T5 model)
- **English to Hindi** (Helsinki-NLP model)
- **Hindi to English** (Helsinki-NLP model)
- **Spanish to English** (Helsinki-NLP model)
- **German to English** (Helsinki-NLP model)
- **French to English** (Helsinki-NLP model)
- **Chinese to English** (Helsinki-NLP model)

## Setup

To use this script, you'll need to have the following dependencies installed:

- Python 3.6+
- [transformers](https://pypi.org/project/transformers/)
- [torch](https://pytorch.org/)

You can install the required dependencies using pip:

```bash
pip install transformers torch
