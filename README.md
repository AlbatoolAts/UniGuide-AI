# UniGuide AI

## Overview

UniGuide AI is an intelligent university assistant built using Retrieval-Augmented Generation (RAG) technology to help students access academic information through natural language conversations.

The system combines semantic search with Generative AI to retrieve relevant university information and generate accurate, context-aware responses.

The project aims to simplify access to academic information such as admission, registration, academic regulations, colleges, majors, and student services through an interactive AI-powered chatbot.

---

## Features

* AI-powered academic chatbot
* Support for Arabic and English queries
* Semantic search instead of traditional keyword matching
* Retrieval of relevant university information
* Natural language question answering
* Context-aware AI-generated responses
* Interactive web-based user interface
* RAG pipeline combining retrieval and generation

---

## System Architecture

The system follows a Retrieval-Augmented Generation (RAG) pipeline:

1. Data Collection

University information is collected from official sources and FAQ data.

2. Data Processing

* Text cleaning
* Text normalization
* FAQ extraction
* Document chunking

3. Embedding Generation

Text is converted into vector representations using:

multilingual-e5-large

4. Vector Database

FAISS is used for efficient similarity search and information retrieval.

5. Response Generation

Retrieved information is provided to the Generative AI model to generate accurate answers.

---

## Technologies Used

### Backend

* Python
* FastAPI
* FAISS Vector Database
* BeautifulSoup
* Retrieval-Augmented Generation (RAG)

### AI Models

* multilingual-e5-large Embedding Model
* Gemini 2.5 Flash Generative Model

### Frontend

* React
* JavaScript
* HTML
* CSS

---

## Project Structure

```
UniGuide-AI
│
├── backend
│   ├── main.py
│   ├── rag_engine.py
│   ├── requirements.txt
│   ├── FAISS index files
│   └── Dataset files
│
├── Frontend
│   ├── React components
│   ├── Pages
│   └── User interface
│
├── Deep_Learning_Report.pdf
│
└── User_Interface.jpeg
```

---

## Evaluation Results

The system was evaluated using university-related questions focusing on retrieval quality and response accuracy.

Results:

* Retrieval Accuracy: 92%
* Arabic Query Success Rate: 89%
* Average Response Time: 1.4 seconds
* Retrieval Similarity Score: 0.81

---

## User Interface

The project includes an interactive chatbot interface that allows students to ask university-related questions and receive AI-generated responses.

---

## How It Works

```
User Question
      |
      v
Text Embedding
      |
      v
FAISS Similarity Search
      |
      v
Relevant Information Retrieval
      |
      v
Generative AI Response
      |
      v
Final Answer
```

---

## Future Improvements

* Voice-based interaction support
* Expansion of the university knowledge base
* Integration with live university databases
* OCR support for university PDF documents
* Improved Arabic language understanding
* Production-scale deployment

---

## Author

Albatool Alattas

---

## License

This project is developed for educational and research purposes.
