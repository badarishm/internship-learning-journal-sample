# Data Cleaning Steps

This document outlines the standard workflow followed to clean and prepare raw datasets before analysis or modeling.

---

## 1. Data Collection
Collect raw data from various sources such as:
- CSV / Excel files
- APIs
- Web scraping
- JSON datasets
- Databases
- Media files (images, audio)

The goal is to gather all required data into a workable format.

---

## 2. Data Inspection
Before cleaning, inspect the dataset to understand:
- Data structure
- Column types
- Missing values
- Duplicate rows
- Inconsistent formats

Tools used:
- Excel
- Command line tools
- DuckDB / SQL queries

---

## 3. Removing Duplicates
Duplicate entries can distort analysis.

Steps:
- Identify duplicate records
- Remove repeated rows
- Keep only unique entries

Methods:
- Excel duplicate removal
- SQL `DISTINCT`
- CLI filtering tools

---

## 4. Handling Missing Values
Datasets often contain incomplete information.

Possible approaches:
- Remove rows with missing values
- Fill values with default placeholders
- Use statistical values (mean, median)

---

## 5. Standardizing Data Formats
Ensure consistent formatting across the dataset.

Examples:
- Date formats → `YYYY-MM-DD`
- Text formatting → consistent casing
- Numbers → correct numeric types

Standardization improves reliability.

---

## 6. Splitting and Structuring Fields
Sometimes columns contain combined information.

Example:

Splitting fields improves filtering and analysis.

---

## 7. Data Transformation
Transform data into usable structures.

Examples:
- Aggregating values
- Reshaping tables
- Filtering unnecessary columns
- Converting data types

---

## 8. Parsing JSON Data
Many APIs provide JSON data.

Steps:
- Parse JSON structure
- Extract nested fields
- Convert into tabular format

This allows easier querying and analysis.

---

## 9. Media Data Processing
Data preparation also applies to non-text data.

Tasks include:
- Image transformation
- Audio extraction
- Generating transcripts from audio

These processes convert media into structured information.

---

## 10. Data Validation
After cleaning, verify dataset quality.

Checks include:
- Correct data types
- Consistent formatting
- No missing critical fields
- Accurate transformations

---

## Final Output

The final cleaned dataset should be:
- Structured
- Consistent
- Analysis-ready
- Reliable for modeling or reporting

