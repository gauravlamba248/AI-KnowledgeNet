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
   git clone https://github.com/gauravlamba248/AI-KnowledgeNet.git
   cd AI-KnowledgeNet
   
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook PORTABLE-Copy1.ipynb

4. Follow the instructions in the notebook to add knowledge, scrape websites, and translate content.

## File Structure
   ```bash
   smart-knowledge-manager/
   ├── data/
   │   └── Cleaned_output_file.xlsx
   ├── models/
   │   └── voting_classifier_model.joblib
   ├── knowledge_base.json        # File where the knowledge base is stored
   ├── PORTABLE-Copy1.ipynb       # Main application file
   ├── requirements.txt           # List of dependencies
   └── README.md                  # Project documentation

```
## Example Interaction
```bash
- What topic do you want to add information about? Supervised Learning
- Enter a main point (or type 'stop' to finish): Definition
- Enter a comment for 'Definition' (or type 'stop' to finish): A type of machine learning.
- Enter a main point (or type 'stop' to finish): Characteristics
- Enter a comment for 'Characteristics' (or type 'stop' to finish): Uses labeled data.
- Enter a main point (or type 'stop' to finish): stop
- AI: I learned your answer about 'Supervised Learning'
