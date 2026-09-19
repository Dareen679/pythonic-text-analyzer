# Pythonic Text Analyzer

## Project Overview

This project refactors a poorly written Python text analyzer into a cleaner, more efficient, and more readable program.

The program reads a text file, analyzes the words, and displays:
- The total number of words
- The number of unique words
- The top 5 most frequent words
- The number of words longer than three characters

## Files

- `unpythonic_analyzer.py` - the original starter code
- `text_analyzer.py` - the refactored Python program
- `sample.txt` - the sample text file used for testing

## How to Run the Program

Open the project folder in VS Code.

Open the terminal and run:

```bash
python3 text_analyzer.py
```

## Key Improvements

### PEP 8
The refactored program follows PEP 8 guidelines by using clear snake_case names, proper indentation, consistent spacing, and organized functions.

### Context Manager
The program uses a `with` statement when opening the text file. This automatically closes the file when it is finished being used.

### List Comprehension
A list comprehension is used to find words that have more than three characters.

### collections.Counter
The `Counter` class is used to count how often each word appears. This replaces the longer manual dictionary loop.

### Modular Functions
The program was divided into smaller functions for reading the file, processing the text, counting words, finding long words, and displaying the results.

## Screencast

Loom video link: https://www.loom.com/share/8fbfae6128984346b3c122085a7b781c