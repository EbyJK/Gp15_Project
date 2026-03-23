# Corporate Email Summarization and Task Extraction

AI-based system for summarizing corporate emails and extracting actionable tasks with priority ranking.  
Developed as a BTech Final Year Project.

## Team Members
- Eby J Kavungal  
- Elena Thomas Kochupurakal  
- Meera Santhosh  

## Project Overview
This project helps corporate users manage emails efficiently by automatically:
- Classifying emails
- Generating summaries
- Extracting tasks and deadlines
- Prioritizing tasks
- Syncing with calendar

The system uses Machine Learning, NLP, FastAPI backend, Supabase database, and multiple frontend clients.

## Modules

### 1. Classification
Detects whether an email is corporate or non-corporate using TF-IDF + Logistic Regression.

### 2. Summarization
Hybrid summarization:
- Extractive (TextRank)
- Abstractive (Transformer)
Produces concise summaries.

### 3. Task Extraction + Prioritization
- Keyphrase extraction
- Named Entity Recognition
- Deadline detection
- Weighted priority scoring

## Frontend Clients

- Google Chrome Extension 
- Electron Desktop Sidebar 

Both clients use the same backend.

## Backend
- FastAPI
- ML pipeline integration
- Calendar integration
- REST API endpoints

## Database
Supabase used for storing:
- Emails
- Summaries
- Tasks
- User accounts

## Features
- Email classification
- Email summarization
- Task extraction
- Task prioritization
- Calendar sync
- Chrome extension UI
- Desktop sidebar UI

## Technologies
Python, FastAPI, Scikit-learn, Transformers, Supabase, JavaScript, Electron, Chrome Extension API

