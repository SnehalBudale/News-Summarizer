# News Article Summarizer

A simple web application that generates concise summaries from news articles using extractive text summarization. Users can enter a news article URL and get a quick summary of the key content.

---

## Overview

This project extracts article text directly from a news website and summarizes it into a shorter version using Natural Language Processing (NLP). It helps users quickly understand the main points without reading the full article.

The application is built using Streamlit for the interface and Sumy (LSA algorithm) for extractive summarization. 

---

## Features

* Extracts article content from any news URL
* Generates concise summaries using extractive NLP
* Simple and interactive web interface
* Displays original text and summarized output
* Handles invalid URLs and extraction errors

---

## Tech Stack

* Python
* Streamlit
* BeautifulSoup (Web scraping)
* Requests
* Sumy (LSA Summarizer)
* NLP

---

## How It Works

1. User enters a news article URL
2. The app fetches webpage content using requests
3. Article text is extracted from paragraph tags using BeautifulSoup
4. Text is processed using the LSA algorithm
5. A summary of key sentences is displayed to the user

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/news-summarizer.git
cd news-summarizer
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the app:

```bash
streamlit run ext_app.py
```

---


## Use Cases

* Quick news consumption
* Content preview before reading full articles
* Information filtering for busy users

---

## Future Improvements

* Support for multiple languages
* Abstractive summarization using transformers
* Option to adjust summary length
* Deployment on cloud (Streamlit Cloud / AWS)

---

## Author

Snehal Budale
Final Year Engineering Student | AI & Data Science


