# Data Preprocessing for Search Engine using Apache Spark in EMR Studio

## Overview

This project analyzes a subset of Wikipedia data using Apache Spark in EMR Studio. The dataset is loaded from an S3 bucket and processed to extract relevant information using Spark's DataFrame API. The analysis includes cleaning the data, tokenizing the text, and computing TF/IDF scores for each document. The project utilizes parallel processing for efficient computation. Finally, the project demonstrates how to search for specific terms (e.g., "Gettysburg") and retrieve the most relevant articles based on TF/IDF scores.

## Requirements

- Apache Spark
- Python (with PySpark)
- S3 bucket with Wikipedia data (subset-small.tsv)

## Usage

1. **Loading Data:** Load the Wikipedia data from the S3 bucket into a Spark DataFrame.
2. **Cleaning Data:** Clean the data by removing any null documents.
3. **Tokenization:** Tokenize the text to split it into words for further processing.
4. **TF/IDF Calculation:** Compute TF/IDF scores for each term in each document to represent the importance of each term.
5. **Search:** Use the TF/IDF scores to search for specific terms (e.g., "Gettysburg") and retrieve the most relevant articles.

## Conclusion

This project demonstrates how to load, clean, preprocess, and analyze a subset of Wikipedia data using Spark in EMR Studio, focusing on TF-IDF analysis for term relevance with the use of parallel processing.
