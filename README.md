# PDF Chatbot using LangChain and Google Generative AI

## Overview

This project is a Streamlit application that allows users to interact with PDF documents through a chatbot interface. It uses the LangChain framework, Google Generative AI, and FAISS for semantic search and conversational responses.

## Features

- Upload PDF documents.
- Extract text from PDFs and chunk it for processing.
- Generate embeddings for the extracted text.
- Use semantic search to find relevant information based on user queries.
- Provide detailed responses to user questions using Google Generative AI.

### Prerequisites

- Python 3.9 or higher
- anaconada

### Steps

1. **Create a Virtual Environment**
    python -m venv myenv    
    conda activate venv

2. **Install the Required Dependencies(libraries)**
    pip install -r requirements.txt
streamlit
google-generativeai
python-dotenv
langchain
PyPDF2
chromadb
faiss-cpu
langchain_google_genai


3. **Set Up Your API Key**
    - Create a `.env` file in the project directory and add your Gemini Pro API key:
        ```
        GEMINI_API_KEY=your_gemini_pro_api_key_here

GOOGLE_API_KEY="AIzaSyBjS3NrMjEi_CZy_fTSRVfdYkOyc0EQgG8"


4. **Create the file app.py and write the code for the structure**


## Usage

1. **Run the Streamlit App**
    streamlit run app.py
    

2. **Open the App in Your Browser**
    - Navigate to `http://localhost:8501` to interact with the chatbot.

## File Structure
.env # Environment variables file (API keys, etc.)
app.py # Main Streamlit app script
requirements.txt # Python dependencies
README.md # Project documentation

