# 📚 Text Analysis and Sentiment Project: "Miracle in the Andes"

This project is an accompanying notebook for a Python course focusing on advanced text processing, data cleaning, and natural language processing (NLP) fundamentals using the `re` and `nltk` libraries.

## 🚀 Getting Started

### Prerequisites

To run this project, you need to have **Python 3.x** installed.

### Installation

All necessary dependencies are listed in the `requirements.txt` file. You can install them using `pip`:

```bash
pip install -r requirements.txt
Data
The analysis is performed on the provided text file: miracle_in_the_andes.txt.

🧠 Project Goals and Learnings
This Jupyter Notebook demonstrates practical skills in handling raw text data and converting it into structured insights.

Core Objectives:
File Handling and Encoding: Safely reading text files using with open(...) and handling common errors like UnicodeDecodeError by specifying encoding="utf8".

Regular Expressions (Regex): Mastering the use of the re module for complex pattern matching, including:

Tokenization: Extracting clean words using patterns like [a-zA-Z]+.

Boundary Management: Defining clear text boundaries (e.g., using [^\n] to find paragraphs, or using capturing groups () to extract specific sections like chapter titles).

Pattern Compilation: Utilizing re.compile() for performance and cleaner code.

Data Cleaning (NLP Pre-processing): Implementing a logic to count word frequencies and performing normalization (using .lower()) and Stop Word removal using the NLTK library to focus on meaningful vocabulary.

Sentiment Analysis: Applying the VADER (Valence Aware Dictionary and sEntiment Reasoner) tool from NLTK to:

Quantify the emotional tone (positive, negative, neutral) of various text sections.

Analyze the change in sentiment score across different chapters of the book, revealing the emotional arc of the narrative.