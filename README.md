# PDF Text Extraction Web App

This is a simple Flask-based web application that allows you to upload PDF files and extract text from them. The app uses **pdfplumber** to extract text content from PDFs.

## Requirements

To run this application locally, ensure you have the following installed:

- Python 3.8+ (recommended: 3.11 or higher)
- pip (Python's package installer)

## Installation

1. Clone this repository to your local machine:
```bash
   git clone https://github.com/yourusername/pdf-extract.git
   cd pdf-extract
```

2. Virtual environment is activated:
```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows use .venv\Scripts\activate
````

3. Install requirements text:
```bash
   pip install -r requirements.txt
````

4. Run the file app.py
```bash
gunicorn app:app
```

Upload any pdf and see its extracts

