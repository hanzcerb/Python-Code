# PDF Text Mining

This project demonstrates how to extract and process information from a collection of research PDF files using Python.

## Workflow

1. **Import Libraries**  
   Uses `pdfminer`, `re`, `pandas`, and Google Drive API libraries for file handling and text processing.

2. **Extract PDF Links**  
   Converts a PDF containing Google Drive links to a text file, then extracts filenames and URLs into a DataFrame.

3. **Download PDF Files**  
   Downloads each PDF from Google Drive using the extracted URLs and saves them in the `files/` directory.

4. **Convert PDFs to Text**  
   Converts each downloaded PDF file to a text file using `pdfminer`.

5. **Extract Information**  
   Reads each text file and extracts metadata such as filename, title, author, abstract, and body using regular expressions.

6. **Build DataFrame and Export**  
   Collects all extracted information into a pandas DataFrame and exports it to a CSV file (`result.csv`).

## Output

- `result.csv`: CSV file containing the extracted data from all processed PDF files.

See [pdf_text_mining.ipynb](pdf_text_mining.ipynb) for the full