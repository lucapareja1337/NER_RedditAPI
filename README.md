# Entity Recognition and Sentiment Analysis for Financial Topics

## Overview

This repository provides a solution for identifying financial entities in text using spaCy for entity recognition and the Reddit API for fetching relevant content. The primary focus is on recognizing financial organizations ('ORG') within the context of Reddit discussions. Additionally, the repository includes a sentiment analysis notebook to aid in the classification of content as either negative or positive.

## Requirements

Before using the provided code, make sure you have the following dependencies installed:

- spaCy: The leading open-source library for advanced natural language processing in Python.
- flar: Used for creating the model 

You can install the required packages using:

```bash
pip install spacy 
pip install flair 
python -m spacy download en_core_web_sm
