# PDF-and-Image-to-Word-Conversion-and-Translation-Script
Automatiser la Conversion de PDF et d'Images en Document Word et Traduction avec Python

Article de Blog associé à ce projet: https://medium.com/@nikiemaboubacar/automatiser-la-conversion-de-pdf-et-dimages-en-document-word-et-traduction-avec-python-bf99b57fc21a 

A travers ce projet, nous allons vous présenter un script Python qui automatise la conversion de fichiers PDF et d'images en documents Word, puis traduit le contenu de l'anglais vers le français en utilisant Tesseract OCR, PDF2Image et Google Translate.


## Description
This script converts PDF files and images to Word documents and translates the text from English to French using Tesseract OCR, PDF2Image, and Google Translate.

## Prerequisites
Ensure you have the following installed:
- Python
- Tesseract OCR
- Poppler
- Python libraries: `pytesseract`, `Pillow`, `python-docx`, `pdf2image`, `googletrans`

## Installation
Install the required Python libraries using pip:
```sh
pip install pytesseract Pillow python-docx pdf2image googletrans==4.0.0-rc1

