# Data Extraction from XLSB Files

This repository contains a Python script to read and extract data from XLSB (Excel Binary Workbook) files. The script uses the `pyxlsb` library to access and parse the data from the binary format, making it easy to extract relevant information such as titles, numerical values, or any other structured content from the file.

## Features
- Read data from `.xlsb` files.
- Extract specific data, such as movie titles or other categories.
- Convert the extracted data into Python-readable formats (e.g., lists or dataframes).
- Easy integration with other Python libraries for further analysis or processing.

## Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `pyxlsb`

You can install the required libraries by running:
```bash
pip install pandas pyxlsb
