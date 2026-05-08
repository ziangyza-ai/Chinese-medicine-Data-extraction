# Chinese-medicine-Data-extraction

## Overview

The goal of this project was to transform unstructured and semi-structured PDF data into a structured format suitable for downstream analysis. The pipeline extracted over 10,000 records from medical PDFs using Python, pandas, and regular expressions, then applied basic NLP preprocessing techniques to standardize text fields.

## Key Features

- Extracted 10,000+ records from semi-structured medical PDF files
- Used regular expressions to identify and parse key information from inconsistent text layouts
- Cleaned and organized extracted data using pandas
- Applied NLP preprocessing techniques including:
  - Text normalization
  - Lowercasing
  - Punctuation removal
  - Lemmatization
- Produced structured datasets for downstream analysis and modeling

## Tools & Technologies

- Python
- pandas
- regex
- NLP preprocessing
- PDF text extraction

## Pipeline Workflow

1. Load medical PDF documents
2. Extract raw text from the file
3. Parse relevant fields using regular expressions
4. Clean and validate extracted records
5. Normalize and lemmatize text fields
6. Export structured data for analysis

## Project Impact

This pipeline reduced manual data processing effort by converting complex medical PDF documents into clean, structured datasets. The final output enabled more efficient downstream analysis and improved consistency across extracted records.

## Example Data Source and Output

Both the data source and Sample outcome of the pipeline is provided.

## Future Improvements

- Add OCR support for scanned PDFs
- Improve field extraction using named entity recognition
- Add automated data validation checks
- Build dashboards for extracted data summaries
