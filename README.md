# Medical Data Extraction

## Project Objective
The objective of this project is to automate the extraction of medical data from PDF documents, specifically focusing on patient details and prescription information. This automation could eliminate manual data entry entirely, achieving a 100% reduction in such tasks.

## Data Types
- **Patient Details**: Information about patients extracted from the PDFs.
- **Prescription Information**: Details of prescriptions from the documents.

## Technology Utilization

## Libraries Required

To automate the extraction of medical data from PDF documents, the following libraries are needed:

1. **pdf2image**  
   Converts PDF files into images for further processing.

2. **OpenCV**  
   A library for image processing tasks, such as cleaning images using adaptive thresholding techniques.

3. **pytesseract**  
   A wrapper for Google's Tesseract-OCR Engine, used for optical character recognition (OCR) to extract text from images.

4. **regex** (or `re`)  
   A library for using regular expressions to extract specific patterns and data from the extracted text.

5. **pytest**  
   A framework for writing and running tests to ensure code quality.
## Process Improvement

### Reduce Manual Effort
This project aims to minimize the need for manual data entry and review, automating the extraction process.

### Enhance Efficiency
By automating data extraction, we aim to speed up the process, facilitating faster access and analysis of medical data.

## Overall Goal
Streamline the extraction process to improve accuracy and workflow in handling medical data.

## Setup

1. **Install Dependencies**: Run the following command to install required libraries:
   ```bash
   pip install -r requirements.txt
