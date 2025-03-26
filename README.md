# News Summarization and Text-to-Speech Application

## Overview

This project is designed to automate news processing by extracting articles, summarizing content, analyzing sentiment, and converting text into speech. Built with **Python**, the application features a **Streamlit web interface** and is deployed on **Hugging Face Spaces** for easy accessibility.

## Features

- **News Extraction**: Retrieves news articles from various sources using **BeautifulSoup**.
- **Content Summarization**: Generates concise summaries of extracted articles.
- **Sentiment Analysis**: Determines whether the news sentiment is **positive, negative, or neutral**.
- **Comparative Analysis**: Evaluates multiple news sources on the same topic.
- **Text-to-Speech (TTS)**: Converts summarized Hindi text into audio.
- **User-Friendly Interface**: Interactive **Streamlit UI** for easy navigation.
- **API Support**: FastAPI integration for backend functionality.
- **Cloud Deployment**: Hosted on **Hugging Face Spaces** for online access.

## Project Structure

```
├── news_scraping.py    # Handles web scraping
├── api.py              # FastAPI for backend processing
├── app.py              # Streamlit frontend for user interaction
├── requirements.txt    # Lists required dependencies
├── hindi_summary.mp3   # Output  
├── README.md           # Project documentation

```

## Installation & Setup

### Prerequisites
Ensure the following are installed:

```
Python 3.7+
pip (Python package manager)
(Optional) Virtual environment
```

### Steps to Run Locally

![image](https://github.com/user-attachments/assets/d7162a0a-044c-4f1e-a871-104e2dc87042)


**Access the application**: https://huggingface.co/spaces/AyshaFathima/News_Summarization_and_TTS

## Deployment on Hugging Face Spaces

### 1. Preparing the Repository
- Ensure `app.py` is the entry point.
- Include a `requirements.txt` file.

### 2. Uploading to Hugging Face Spaces
- Create a new **Space** on Hugging Face.
- Choose **Streamlit** as the SDK.
- Push the project files to the repository.

### 3. Running the Application
- Hugging Face will automatically build and deploy the application.
- Access the deployed app through the provided **URL**.

## Future Enhancements

- Support for additional languages.
- Improved summarization accuracy using advanced NLP models.
- Integration with more news sources.
- Enhanced UI with better user interaction and design.

