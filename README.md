# Sentiment Analysis for MCA E-Consultation

An AI-powered tool to analyze stakeholder comments for the Ministry of Corporate Affairs' E-consultation module.

## Features (Planned)
- Sentiment Analysis of comments
- Automated Summary Generation
- Word Cloud visualization
- Web-based dashboard

## Tech Stack
- **Backend:** Python, FastAPI
- **ML Models:** Hugging Face Transformers, NLTK/Spacy
- **Frontend:** React.js
- **Database:** SQLite (Dev), PostgreSQL (Prod)

## Development Setup

1.  Clone the repo: `git clone <repo-url>`
2.  `cd sentiment-analysis-mca`
3.  Create a virtual environment: `python -m venv venv`
4.  Activate it:
    - Windows: `.\venv\Scripts\activate`
    - Unix/MacOS: `source venv/bin/activate`
5.  Install dependencies: `pip install -r requirements.txt`
6.  Run the backend: `uvicorn backend.main:app --reload`
