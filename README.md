# Flight_Prediction
# Project: Document & JSON Data Processing

## Overview
This project extracts and processes data from `.docx` files and JSON datasets. It utilizes Python libraries such as `docx`, `pandas`, and `numpy` to manipulate and analyze structured data, potentially related to flight or transport information.

## Features
- Extracts text from `.docx` files.
- Parses and flattens JSON data for easy processing.
- Uses Pandas for data transformation and analysis.
- Handles IATA and ICAO codes for departure and arrival information.

## Installation & Requirements
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Required dependencies:
  ```sh
  pip install pandas numpy python-docx
  ```

## Usage
1. Place your `.docx` files inside the `Train` folder.
2. Run the script to extract text and process JSON data:
   ```sh
   python script.py
   ```
3. Processed data will be stored in a structured format for further analysis.

## Folder Structure
```
/project-root
│-- Train/  # Contains .docx files
│-- script.py  # Main processing script
│-- data.json  # Example JSON data
│-- README.md  # Project documentation
```

## License
This project is open-source and available under the MIT License.

## Credits
Developed by Huzaifa Azam

