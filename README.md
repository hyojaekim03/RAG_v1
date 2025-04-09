# RAG Chatbot

## Overview

This project is a simple prototype RAG implementation of an AI English Tutor using Langchain, Pinecone, and OpenAI API. 

## Set-up Instructions

1. Prerequisites
Make sure you have the following installed on your machine:

  - Python 3.12^
  - pip
  - Pinecone account + API key, Environment/Region
  - OpenAI API key

2. Clone the Repository
``` bash
git clone <repository-url>
cd <repository-name>
```

3. Install Dependencies
```bash
pip install requirements.txt
```

4. Set Env variables
Set your environment variables in a .env file. 

5. Load data -> Currently set to custom textbook data.
```bash
python3 load.py
```

6. Query data (start conversation)
```bash
python3 query.py
```



