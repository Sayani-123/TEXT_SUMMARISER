# Text Summarization

## Overview

This project provides a text summarization tool that uses the Term Frequency-Inverse Document Frequency (TF-IDF) algorithm to condense long articles or texts into shorter summaries. The program supports multiple input methods, making it versatile and user-friendly.

### Purpose

To save time while reading by summarizing large articles or texts into fewer lines.

## Features

You can input the text in four different ways:

1. **Typing Text**: Manually input or copy-paste the text.
2. **From .txt File**: Load text from a plain text file.
3. **From .pdf File**: Summarize an entire PDF or select a specific page range for summarization.
4. **From Wikipedia Page**: Provide the URL of a Wikipedia page, and the program will automatically scrape the text and summarize it for you.

### Output

The program generates a summary of the provided article. It also compares the word count of the original content versus the summarized content. 

**Example Output**:


## Requirements

- Python 3.x
- SpaCy Module (short, medium, or long model)
- NLTK Module
- PyPDF2
- Beautiful Soup (bs4)
- urllib (included with Python)

### Installation Instructions

1. **Python**: Install Python 3 from the [official site](https://www.python.org/) or use an Anaconda environment.

2. **Install Dependencies**:
   - For **Anaconda Environment**:
     ```bash
     conda install -c conda-forge spacy
     conda install -c anaconda nltk
     conda install -c conda-forge pypdf2
     conda install -c anaconda beautifulsoup4
     ```
   - For **Other Environments**:
     ```bash
     pip3 install spacy
     pip3 install nltk
     pip3 install PyPDF2
     pip3 install beautifulsoup4
     ```
   - **Download SpaCy English Model**:
     ```bash
     python3 -m spacy download en
     ```

## Getting Started

1. Download or clone the repository.
2. Open the command prompt or terminal in the same directory where the `text1.py` file is stored.
3. Run the following command:
   ```bash
   python3 text1.py
4.Follow the prompts in the program to summarize your text.   
