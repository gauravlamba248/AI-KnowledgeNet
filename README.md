# Interactive AI Knowledge Base with Web Scraping and Translation Support

## Project Overview

This project is an interactive AI-driven system designed to help users build and maintain a knowledge base. The system allows users to:
- Add new knowledge points interactively.
- Save and load the knowledge base in a structured JSON format.
- Scrape and extract information from websites using web scraping techniques.
- Translate scraped content into English for better accessibility.
- Append comments, characteristics, and properties to main points in the knowledge base.

The main goal is to allow for dynamic and flexible management of a knowledge base with support for multilingual content and structured data storage.

## Features

- **Knowledge Base Management**: Users can add, update, and save information to the knowledge base interactively.
- **Web Scraping**: Extracts relevant information from specified websites using Python's `BeautifulSoup` and `requests`.
- **Translation Support**: Translates non-English content from scraped web pages into English.
- **File Persistence**: Load and save the knowledge base as a JSON file for easy reuse and management.

## Technologies Used

- Python
- `json` for knowledge base storage
- `requests` for web requests
- `BeautifulSoup` for web scraping
- `IPython.display` for interactive display

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/interactive-ai-knowledge-base.git
   cd interactive-ai-knowledge-base
   
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook PORTABLE-Copy1.ipynb

4. Follow the instructions in the notebook to add knowledge, scrape websites, and translate content.


