# XML Text Mining

This project demonstrates how to extract structured information from a collection of XML patent documents using Python.

## Workflow

1. **Import Libraries**  
   Uses `re` (Regex) and `pandas` for text processing and data handling.

2. **Read XML Data**  
   The `file_reader()` function reads a text file containing multiple XML patent records and splits them into a list.

3. **Extract Information**  
   Several functions extract fields such as grant ID, patent kind, title, abstract, inventors, claims, and citation counts from each XML record using regular expressions.

4. **Build DataFrame**  
   All extracted data is collected into a pandas DataFrame for further analysis.

5. **Export Results**  
   The DataFrame is exported to both CSV and JSON formats.

## Output

- `result.csv`: CSV file containing the extracted patent data.
- `result.json`: JSON file with the same data.

See [xml_text_mining.ipynb](XML%20Text%20Mining/xml_text_mining.ipynb) for