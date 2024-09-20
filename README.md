# PIxtract NER Tool

PersonAware is a FastAPI-based application that allows users to upload text files and perform Named Entity Recognition (NER) using various libraries: spaCy, NLTK, and Hugging Face Transformers (HFT).

## Features

- **Upload Files**: Upload text files in various formats.
- **NER Processing**: Choose between spaCy, NLTK, and HFT for NER processing.
- **Text Conversion**: Converts uploaded files to plain text for processing.
- **NER Extraction**: Extracts entities from the text and returns them in a structured format.

## Installation

1. **Clone the repository**:
   ```sh
   git clone https://github.com/zarcaxm/PersonAware.git
   cd PersonAware
    ```
2. **Requirements**: 

- **Calibre**: Install Calibre from the [official Calibre website](https://calibre-ebook.com/download).
  Ensure that the `ebook-convert` command is accessible from your command line.

- **Python**:
    ```sh
    pip install -r requirements.txt
    ```

- **Unoconv**:
  ```sh
  sudo apt-get install unoconv
  sudo apt-get install libreoffice
    ```

- **Soffice**:
  ```sh
  sudo apt-get install libreoffice
  ```

## Start
  ```sh
  cd backend 
  uvicorn app.main:app --reload --port 8090
  ```
